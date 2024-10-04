# Классификация цветков ириса

## Описание проекта

Этот проект посвящен разработке и обучению модели машинного обучения для классификации цветков ириса на три категории на основе морфологических признаков. Датасет содержит 150 экземпляров цветов ириса с четырьмя признаками и одним целевым классом.

## Задача

Целью проекта является создание модели, способной классифицировать цветы ириса на три вида:
- Iris Setosa
- Iris Versicolour
- Iris Virginica

на основе следующих признаков:
- Длина чашелистика (см)
- Ширина чашелистика (см)
- Длина лепестка (см)
- Ширина лепестка (см)

## Используемые модели

В проекте были реализованы и сравнены две модели машинного обучения:
1. Логистическая регрессия
2. Дерево решений

## Метрики оценки

Для оценки качества моделей использовались следующие метрики:
- Точность (accuracy)
- F1-мера (для каждого класса)
- Матрица ошибок (confusion matrix)

## Основные результаты

- Обе модели показали высокую точность в классификации видов ириса.
- Логистическая регрессия немного превзошла дерево решений по точности.
- Подбор гиперпараметров значительно улучшил производительность дерева решений.
- Наиболее информативными признаками для классификации оказались длина и ширина лепестка.

## Структура проекта

- `iris_classification.ipynb`: Jupyter Notebook с полным анализом и кодом
- `README.md`: Описание проекта (этот файл)
- `requirements.txt`: Список необходимых Python-пакетов

## Как использовать

1. Клонируйте репозиторий:
   ```
   git clone https://github.com/mms-tbe/Multiclass-classification-on-iris-flower-data
   ```
2. Установите необходимые зависимости:
   ```
   pip install -r requirements.txt
   ```
3. Откройте и запустите Jupyter Notebook:
   ```
   jupyter notebook Multiclass_classification_on_iris_flower_data.ipynb
   ```

## Зависимости

Проект использует следующие основные библиотеки:
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn

Полный список зависимостей находится в файле `requirements.txt`.

## Автор

Мурат Манасов

## Лицензия

Этот проект распространяется под лицензией MIT. Подробности смотрите в файле LICENSE.
