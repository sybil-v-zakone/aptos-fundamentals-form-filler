# APTOS FUNDAMENTALS GOOGLE FORM FILLER

## Настройка
* В файле `data/addresses.txt` записываем адрес Aptos кошелька. Каждый с новой строки.
* В файле `data/names.txt` записываем домен Aptos. Каждый с новой строки.

Заполняем `addresses` и `names` 1к1. 

Формат имен: Принимает имена которые либо ни на что не заканчиваются, либо заканчиваются на `.apt`. 
Пример: `test.apt`, `test`.


В файле `settings.py` выставляем:
* `SLEEP_TIME` - слип диапазон после каждого успешного заполнения формы
* `ERROR_SLEEP_TIME` - слип диапазон после ошибки
* `ADDRESSES_FILE_PATH` - путь к файлу с адресами
* `NAMES_FILE_PATH` - путь к файлу с доменами

# Установка:
#### *Установка для Windows:*
Открываем терминал в папке скрипта и пишем следующие команды:
1. `cd путь\к\проекту`
2. `python -m venv venv`
3. `.\venv\Scripts\activate`
4. `pip install -r requirements.txt`

#### *Установка для MacOS/Linux:*

Выполняем данные команды в терминале:

1. `cd путь/к/проекту`
2. `python3 -m venv venv`
3. MacOS/Linux `source venv/bin/activate`
4. `pip install -r requirements.txt`

# Запуск:
```
    python main.py


![image](https://github.com/sybil-v-zakone/aptos-fundamentals-form-filler/assets/33164477/01b6b238-edb3-480f-b6a9-9ef272732fb8)
