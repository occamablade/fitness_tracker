# Модуль фитнес-трекера
![Python](https://img.shields.io/badge/Python-3.9.10-blue)
## Описание проекта

Модуль для фитнес трекера, рассчитывающий и отображающий полную информацию о тренировках по данным от блока датчиков

## Функционал модуля
- принимает от блока датчиков информацию о прошедшей тренировке,
- определяет вид тренировки,
- рассчитывает результаты тренировки,
- выводит информационное сообщение о результатах тренировки, включающее в себя:
    - тип тренировки (бег, ходьба или плавание);
    - длительность тренировки;
    - дистанция, которую преодолел пользователь, в километрах;
    - среднюю скорость на дистанции, в км/ч;
    - расход энергии, в килокалориях.


## Установка и запуск

 Для MacOs и Linux вместо python использовать python3

1. Клонировать репозиторий.
   ```
   git@github.com:occamablade/fitness_tracker.git
   ```
2. Cоздать и активировать виртуальное окружение:
    ```
      $ cd fitness_tracker
      $ python -m venv venv
    ```
    Для Windows:
    ```
      $ source venv/Scripts/activate
    ```
    Для MacOs/Linux:
    ```
      $ source venv/bin/activate
    ```
3. Установить зависимости из файла requirements.txt:
    ```
    (venv) $ python -m pip install --upgrade pip
    (venv) $ pip install -r requirements.txt
    ```
4. Запустить проект
    ```
    python homework.py
    ```

## Контакты
**Иван Безбородников** 

[![Telegram Badge](https://img.shields.io/badge/-vanyshqa-blue?style=social&logo=telegram&link=https://t.me/vanyshqa)](https://t.me/vanyhsqa) [![Gmail Badge](https://img.shields.io/badge/-bezborodnikov18@gmail.com-c14438?style=flat&logo=Gmail&logoColor=white&link=mailto:bezborodnikov18@gmail.com)](mailto:bezborodnikov18@gmail.com)
