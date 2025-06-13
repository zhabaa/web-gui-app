# Handwriting Recognition Project.

Проект для распознавания рукописных цифр и букв с двумя интерфейсами: \
web-версией на Flask и GUI-версией.

## Структура проекта

```
handwriting_recognition/
├── web_app/                  # Веб-версия на Flask
│   ├── static/
│   │   ├── script.js         # Логика рисования и взаимодействия
│   │   └── style.css         # Стили для веб-интерфейса
│   ├── templates/
│   │   └── index.html        # HTML шаблон
│   └── app.py                # Flask приложение
│
├── gui_app/                  # GUI версия
│   ├── main.py               # Основной скрипт GUI
│   └── requirements.txt      # Зависимости для GUI
│
├── README.md                 # Этот файл
└── requirements.txt          # Основные зависимости Python
```

## Установка и запуск

### Общие требования
- Python 3.9+

### Веб-версия (Flask)

1. Установите зависимости:
```bash
pip install -r requirements.txt
```

2. Запустите Flask приложение:
```bash
cd ../..
python web_app/app.py
```

3. Откройте в браузере:
```
http://localhost:5000
```

### GUI-версия

1. Установите зависимости:
```bash
pip install -r requirements.txt
```

2. Запустите GUI приложение:
```bash
python gui_app/main.py
```

## Функционал

### Веб-версия
- Рисование на холсте 64x64 (отображается как 256x256)
- Кнопки:
  - Очистка холста
  - Сохранение рисунка

### GUI-версия
- Аналогичный функционал в нативном интерфейсе
