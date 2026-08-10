![Python](https://img.shields.io/badge/Python-3.9-blue)
![DataLens](https://img.shields.io/badge/DataLens-Yandex-blue)
# coffee-prices-analysis (2024-2026)
## Описание проекта
Дашборд и анализ региональных цен на кофе в России. Выявлены аномалии, построен прогноз на 6 месяцев.

## Задача
Проанализировать динамику цен в 274 городах, найти региональные различия и построить прогноз.

## Инструменты
- **Yandex DataLens** — визуализация дашборда
- **Python (pandas, statsmodels)** — прогноз ARIMA
- **Excel / Google Sheets** — подготовка данных

## Результаты
- **Дашборд:** [ссылка на DataLens](https://datalens.yandex/f6b6cirutnlcy)
- **Ключевые выводы:**
  - Региональный разрыв: Дальний Восток на 40% дороже Приволжья.
  - Города-рекордсмены: Усть-Нера (+67,9%), Вилюйск (+66,9%).
  - Прогноз: снижение цен на 6% к декабрю 2026.

## Файлы
- `forecast_coffee_rf_ipnb.py` — код для прогноза ARIMA
- `forecast_6m.csv` — результат прогноза
- `analisys_coffee.ipynb` — базовый анализ данных с загрузкой, фильтрацией, построением графиков:
- Линейный график динамики цен
- Столбчатая диаграмма по годам
- Гистограмма распределения цен
- `coffee_dashboard_overview.png` — скриншот дашборда
- `coffee_dashboard_filtered.1.png` — скриншот дашборда
- `coffee_dashboard_filtered.2.png` — скриншот дашборда

## Скрин дашборда
<img width="3104" height="1601" alt="image" src="https://github.com/user-attachments/assets/18a8293a-458e-49d4-a407-47ca75cf5e35" />

## Контакты
[Вадим] — [vad.litko@yandex.ru]
