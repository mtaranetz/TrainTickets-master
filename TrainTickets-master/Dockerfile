# Используем официальный .NET рантайм
FROM mcr.microsoft.com/dotnet/runtime:8.0

# Создаем рабочую директорию внутри контейнера
WORKDIR /app

# Копируем опубликованные файлы из папки publish
COPY publish/ .

# Указываем, какой файл запускать
ENTRYPOINT ["dotnet", "TrainTickets.UI.dll"]
