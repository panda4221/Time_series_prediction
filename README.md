# Time_series_prediction

**Прогнозирование заказов такси**

Компания «Чётенькое такси» собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. 

**Цель проекта:** построить модель для предсказания количества заказов такси на следующий час - `RMSE < 48`.

В рамках данного проекта было выполнено следующее:
1. Загружены и обработаны данные с временным рядом по заказам такси.
2. Проанализированы данные, сделаны соответствующие выводы, добавлены дополнительные признаки для обучения.
3. Подобраны гиперпараметры и обучены четыре модели: `Линейная регрессия`, `Дерево решений`, `Случайный лес` и `XGBoost`.
4. Выбрана наилучшую по `RMSE` на тренировочной выборке модель `Случайный лес` с показателем метрики качества `19.59`.
5. Проведено тестирование, метрика качества составила `42.81` - поставленная по метрике задача выполнена.
