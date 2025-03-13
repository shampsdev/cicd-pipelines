# Reusable CI/CD Pipelines

Этот репозиторий содержит переиспользуемые CI/CD пайплайны для автоматизации процессов в GitHub Actions. Пайплайны абстрагированы и могут быть легко интегрированы в проекты с минимальными изменениями.


## Использование
### GitHub Actions
Добавьте в ваш репозиторий в `.github/workflows/` нужный пайплайн:
```yaml
name: Some pipeline

jobs:
  build:
    uses: shampsdev/cicd-pipelines/.github/workflows/pipeline.yaml@main
```

## 📄 Лицензия
Этот проект лицензирован под MIT License – свободно используйте и модифицируйте!
