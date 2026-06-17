# Лабораторная работа 1
## Использование системы Git, Организация удалённого репозитория

### Задание 1: Регистрация на GitHub
✅ Выполнено — создан аккаунт на github.com

### Задание 2: Создание пустого удалённого репозитория
✅ Выполнено — репозиторий `react-labs-it3k6` создан

### Задание 3: Создание проекта на основе исходного кода
✅ Выполнено — разработан проект React Labs

### Задание 4: Инициализация локального репозитория
```bash
git init
```

### Задание 5: Создание нескольких коммитов
```bash
git add index.html css/style.css js/app.js
git commit -m "feat: add project structure and styles"

git add README_GIT.md
git commit -m "docs: add git lab documentation"
```

### Задание 6: Синхронизация с удалённым репозиторием
```bash
git remote add origin https://github.com/username/react-labs-it3k6.git
git push -u origin main
```

### Задание 7: Создание новой ветки
```bash
git checkout -b feature/add-redux
```

### Задание 8: Коммиты в новой ветке
```bash
git add js/app.js
git commit -m "feat: integrate Redux Toolkit for state management"
git push origin feature/add-redux
```

### Задание 9: Push новой ветки
```bash
git push origin feature/add-redux
```

### Задание 10: Слияние ветки на удалённом репозитории
✅ Выполнено через GitHub Pull Request → Merge

### Задание 11: Получение изменений из main
```bash
git checkout main
git pull origin main
```

### Задание 12: Присоединение коллеги
✅ Коллега добавлен в Settings → Collaborators

### Задание 13: Передача ветки коллеге
```bash
git checkout -b feature/login-page
git push origin feature/login-page
```

### Задание 14: Коллега вносит изменения и создаёт PR
✅ Коллега внёс изменения в компонент входа
✅ Создан Pull Request

### Задание 15: Принятие Pull Request
✅ PR проверен и объединён с main
```bash
git checkout main
git pull origin main
```

---
**Выполнил:** Sun Kepeng (孙可鹏)  
**Группа:** IT3K6
