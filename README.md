# Сагантай Адиль CS-204(s)

## Практическая работа №8. Квест-мастер: Генератор приключений

### ЦЕЛИ ПРОЕКТА
- Создать полноценное GUI-приложение на PyQt6 для управления квестами
- Реализовать систему шаблонизации документов с экспортом в PDF/DOCX
- Освоить работу с графикой (QPainter) для визуального редактирования
- Интегрировать базу данных

### 🚀Проект имеет:
### 🧩Создание квестов
- Название
- Описание (с проверкой на минимум 50 слов)
- Уровень сложности (Лёгкий → Эпический)
- Награда
- Дедлайн
- Автоматическая валидация полей

### 📄Экспорт документов
- PDF (через HTML-шаблоны)
- DOCX
- Поддержка трёх PDF-шаблонов: royal_decree.html , guild_contract.html и ancient_scroll.html

### 🗺Редактор карты
- Встроенный Map Editor позволяет визуально редактировать карту квеста.

### 🎮Геймификация (XP + уровни)
- Получение XP за действия (создание, экспорт, карта и т.д.)
- Прогресс-бар опыта
- Список достижений
- Внутренняя система уровней

### 🧪Босс-Файт (стресс-тест)
**Отдельный режим нагрузки, создающий 100 квестов подряд.**
- Выполняется в отдельном QThread
- Показывает результат: успешно / слишком медленно
- Даёт +20 XP при победе

### 🔍Подсчёт статистики
- Слова
- Символы
- Автоматическое выделение ошибок

### 📦 База данных
- Используется SQLite, реализована через модуль core/database.py.

### Структура папки
<img width="484" height="485" alt="image" src="https://github.com/user-attachments/assets/6d7e4910-63b4-4704-a338-6b1f9df87d22" />

### Результат
**🚨 P.S Стресс-тест (создание 100 квестов) выполняется заметно медленнее в графическом интерфейсе, потому что Qt-интерфейс нагружается большим количеством операций — обновлениями списка, прогрессбара, базы данных и сигналов UI.
Это нормально: тест предназначен для проверки логики и скорости движка, а не визуальной части.**

**Поэтому я сделал стресс-тест в отдельном файле**

<img width="810" height="632" alt="image" src="https://github.com/user-attachments/assets/4c042099-d173-40c3-939c-f9544d31ff00" />

<img width="810" height="632" alt="image" src="https://github.com/user-attachments/assets/bf1564fc-001f-4bd8-92d4-374851ea96f3" />

<img width="308" height="125" alt="image" src="https://github.com/user-attachments/assets/d7b955b5-f7fe-4c60-b541-f2520c9c0235" />


<img width="811" height="206" alt="image" src="https://github.com/user-attachments/assets/13df2ae0-d765-4a3b-8279-03e2b78431ef" />

<img width="340" height="125" alt="image" src="https://github.com/user-attachments/assets/f957621a-fc09-499c-b091-c67620d08cde" />

<img width="358" height="125" alt="image" src="https://github.com/user-attachments/assets/b438b64d-faef-4fe8-81d7-e6dc50bcb7df" />

<img width="383" height="125" alt="image" src="https://github.com/user-attachments/assets/25ee8c89-6dc5-4def-894b-6a5beaf6178f" />

<img width="831" height="612" alt="image" src="https://github.com/user-attachments/assets/c2d71b7e-07c6-4c1e-81a2-4dbe34b9ece6" />

<img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/ea37b464-61ef-411a-9870-875e569e0729" />

<img width="1920" height="1040" alt="image" src="https://github.com/user-attachments/assets/b330f40a-e09a-46ee-94c4-faf9d896967e" />

<img width="1426" height="746" alt="image" src="https://github.com/user-attachments/assets/22799a36-c581-491b-bd5c-d5bd01ba06d9" />

<img width="799" height="249" alt="image" src="https://github.com/user-attachments/assets/48cd124b-409d-450f-8d00-66466c577a74" />

<img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/717cda6e-22a2-47fb-b597-e62a73445148" />

<img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/875d6391-2de4-40d5-8fce-74372f05d36a" />

<img width="826" height="686" alt="image" src="https://github.com/user-attachments/assets/c81d07bc-6e4c-49be-af92-7e909ab67b7c" />

<img width="946" height="533" alt="image" src="https://github.com/user-attachments/assets/b6a904bf-f4f8-4031-a230-9c7496237ce6" />

<img width="826" height="686" alt="image" src="https://github.com/user-attachments/assets/72cfce59-313b-487a-a6a8-3b912cc028f0" />

<img width="826" height="686" alt="image" src="https://github.com/user-attachments/assets/ad79ef2d-f21a-454c-b27c-4b35a710f7b4" />

<img width="826" height="686" alt="image" src="https://github.com/user-attachments/assets/a9625ccf-b084-4f3d-ac5f-3a4b6aa013f1" />

<img width="826" height="686" alt="image" src="https://github.com/user-attachments/assets/ad7473a7-4c04-4ec7-b073-3d7144b372c5" />

<img width="202" height="128" alt="image" src="https://github.com/user-attachments/assets/db670833-6367-41d2-97f6-a8ed6459af2f" />

<img width="826" height="686" alt="image" src="https://github.com/user-attachments/assets/9345b48e-420c-465b-81cf-df712d193ead" />

<img width="826" height="686" alt="image" src="https://github.com/user-attachments/assets/bc7bacad-2b63-4fff-99f5-bd5a588521a6" />

<img width="831" height="612" alt="image" src="https://github.com/user-attachments/assets/88bb1f51-10b8-41b7-8c59-00360e0ef40c" />

<img width="1426" height="746" alt="image" src="https://github.com/user-attachments/assets/77183d74-dd42-48f2-b677-4de51be746cb" />

<img width="804" height="631" alt="image" src="https://github.com/user-attachments/assets/2b3b6cce-24a7-4ff8-991b-92b2d63b12a1" />

<img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/0c43aae0-69e1-4819-8ac6-36856514c0a9" />

<img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/dd07759b-1a66-467d-b392-5f9815b875a8" />

## Видео-демо 
### Работы программы  - 
### Генерации 100 квестов - 

























