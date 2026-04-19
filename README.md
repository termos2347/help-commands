## 1. Настройка Git
```bash
git config --global user.name "termos2347"
git config --global user.email "termos2347@gmail.com"
```
## 2. Создание виртуального окружения
```bash
python -m venv venv
```
## 3. Активация окружения (для Windows)
```bash
.\venv\Scripts\activate
```
## 4. Обновление самого пакетного менеджера
```bash
python -m pip install --upgrade pip
```
## 5. Установка всех библиотек из проекта
```bash
pip install -r requirements.txt
```
## 6. Если нужно быстро сохранить все новые библиотеки в файл
```bash
pip freeze > requirements.txt
```
