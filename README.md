# 🚀 Apex Pro Launcher 3.0

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey.svg)

**Apex Pro Launcher** — это современный, быстрый и кастомизируемый лаунчер для Minecraft, написанный на Python с использованием библиотеки `customtkinter`. 

Разработан как стильная и легкая альтернатива стандартным клиентам, объединяющая в себе минималистичный интерфейс и мощный функционал AAA-лаунчеров.

---

## ✨ Главные возможности

* 🟢 **Официальная авторизация (OAuth 2.0):** Безопасный вход через аккаунт Microsoft Xbox Live. Лаунчер автоматически загружает ваш никнейм и лицо скина.
* 📦 **Менеджер модов:** Установка Forge и Fabric в пару кликов. Встроенная вкладка для быстрого включения и отключения модов в профиле.
* 🎮 **Discord Rich Presence:** Автоматическая трансляция вашего статуса в Discord (версия игры, загрузчик, время в игре).
* ⏱️ **Трекер времени:** Лаунчер подсчитывает каждую секунду, проведенную в игре на конкретном профиле.
* 🎨 **Кастомизация:** Поддержка светлой и темной темы, выбор цвета акцентов (синий, зеленый, темный), настройка выделения ОЗУ и аргументов JVM.
* ☕ **Умная загрузка Java:** Лаунчер сам анализирует выбранную версию игры и скачивает нужную версию JRE (Java Runtime Environment) в фоновом режиме.

---

## 📸 Скриншоты

*(Добавьте сюда ссылки на скриншоты вашего лаунчера, когда загрузите их на GitHub)*

|<img src="https://via.placeholder.com/400x250.png?text=Main+Menu" alt="Главное меню">|<img src="https://via.placeholder.com/400x250.png?text=Mod+Manager" alt="Менеджер модов">|
|:---:|:---:|
| *Главный экран и авторизация* | *Встроенный менеджер модов* |

---

## 🛠️ Установка для разработчиков (Исходный код)

Если вы хотите запустить лаунчер из исходников или внести свои изменения:

1. Склонируйте репозиторий:
   ```bash
   git clone [https://github.com/zetnik112/apex-launcher-web.git](https://github.com/zetnik112/apex-launcher-web.git)
   cd apex-launcher-web
2. Установите необходимые библиотеки:

   ```bash
   pip install customtkinter minecraft-launcher-lib pypresence Pillow requests
3. Запустите лаунчер:

   ```Bash
   python main.py
📦 Компиляция в .EXE (Для Windows)
Чтобы собрать лаунчер в готовое приложение для обычных пользователей (без установки Python):

1. Установите PyInstaller:

   ```Bash
   python -m pip install pyinstaller
2. Выполните команду сборки (убедитесь, что папка assets с иконкой и фоном находится рядом с main.py):

   ```Bash
   python -m PyInstaller --noconfirm --noconsole --onedir --name "ApexProLauncher" --icon "assets\icon.ico" --add-data "assets;assets" main.py
3. Готовый лаунчер появится в папке dist/ApexProLauncher.
🌐 Веб-сайт
Официальная страница проекта (Landing Page) доступна по ссылке:
Сайт Apex Pro Launcher

⚠️ Отказ от ответственности
Этот проект создан в образовательных целях и не связан с Mojang AB или Microsoft Corporation. Minecraft является торговой маркой Mojang Synergies AB.


***

### Пару советов по GitHub:
1. Замени заглушки `https://via.placeholder.com/...` в разделе **Скриншоты** на прямые ссылки на свои картинки. Чтобы получить прямую ссылку, просто перетащи скриншот своего лаунчера прямо в окно редактирования `README.md` на сайте GitHub, и он сам сгенерирует код картинки!
2. Обязательно загрузи свой финальный `main.py` и папку `assets` в этот же репозиторий, чтобы код не потерялся и другие люди могли его оценить.
