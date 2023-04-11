# Блокноты к курсу Интеллектуальный анали данных (Data Mining)

## Установка
1. Клонировать репозиторий. 

* Рекомендуется использовать [Github Desktop](https://desktop.github.com/).
* В командной строке можно воспользоваться [git](https://git-scm.com/downloads)
```
git clone https://github.com/stipot/dscience.git
```

2. Для редактирования рекомендуется воспользоваться средой разработки [Visual Studio Code](https://code.visualstudio.com/download) - далее VSCode

3. Установить в VS Code следующие расширения:
* По отдельности:
    * [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
    * [Jupiter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)
    * [Python Environment Manager](https://marketplace.visualstudio.com/items?itemName=donjayamanne.python-environment-manager)
* Или одним пакетом
    * [Python Extension Pack](https://marketplace.visualstudio.com/items?itemName=donjayamanne.python-extension-pack)

3. Установить локальное виртуальное окружение
    * Открыть настройки пользователя Ctrl+Shift+P
    * В открывшейся строке поиска набрать Env
    * Выбрать опцию "Python: Create environment"
    * Выбрать venv
    * Выбрать установленный интерпретатор Python. Для Linux введите абсолютный путь к вашей среде «path/to/myenv/bin» или «path/to/myenv/Script/»
    * Перезапустить терминальное окно (если открыто Ctrl+~) или перезапустить VSCode

4. Установить необходимые нам модули для python
```
pip install -r ./requirements.txt
```

5. Открываем блокнот module2
