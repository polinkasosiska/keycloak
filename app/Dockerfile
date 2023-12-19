FROM python:3.9

# Устанавливаем рабочую директорию внутри контейнера
WORKDIR /app

# Копируем файлы проекта в рабочую директорию
COPY . /app

# Устанавливаем все необходимые пакеты
RUN pip install -r requirements.txt

# Запускаем приложение
CMD ["python", "main.py"]
