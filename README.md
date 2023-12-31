# Проектный практикум, Инженерия машинного обучения @ УрФУ, лето 2023

В рамках дисциплины «Проектный практикум» вам предстоит самостоятельно решить настоящую задачу машинного обучения, направленную на автоматизацию бизнес-процессов. Мы построим модель, которая будет предсказывать общую **продолжительность поездки на такси в Нью-Йорке**.

Представьте, что вы заказываете такси из одной точки Нью-Йорка в другую, причём необязательно, что конечная точка должна находиться в пределах города. Сколько вы должны будете заплатить за поездку?

Известно, что стоимость такси в США рассчитывается на основе фиксированной ставки и тарифной стоимости, величина которой зависит от времени и расстояния. Тарифы варьируются в зависимости от города.

В свою очередь, время поездки зависит от множества факторов, таких как направление поездки, время суток, погодные условия и так далее.

Таким образом, если мы разработаем алгоритм, способный определять длительность поездки, мы сможем прогнозировать её стоимость самым тривиальным образом, например, просто умножая стоимость на заданный тариф.

Сервисы такси хранят огромные объёмы информации о поездках, включая такие данные, как конечная и начальная точки маршрута, дата поездки и её продолжительность. Эти данные можно использовать для того, чтобы прогнозировать длительность поездки в автоматическом режиме с привлечением искусственного интеллекта.

Задача, которую мы будем решать, была представлена в качестве Data Science-соревнования с призовым фондом в 30 000 $ на платформе Kaggle в 2017 году.

Вам будет предоставлен набор данных, содержащий информацию о поездках на жёлтом такси в Нью-Йорке за 2016 год. Первоначально данные были выпущены Комиссией по Такси и Лимузинам Нью-Йорка. Они включают в себя информацию о времени поездки, географических координатах, количестве пассажиров и несколько других переменных.

Бизнес-задача: определить характеристики и с их помощью спрогнозировать длительность поездки на такси.

Техническая задача для вас как для специалиста в Data Science: построить модель машинного обучения, которая на основе предложенных характеристик клиента будет предсказывать числовой признак — время поездки такси, то есть решить задачу регрессии.