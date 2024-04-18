# Проект 1. Музыка больших городов
**Навыки и инструменты:** Pandas,Python

**Задачи проекта:** На реальных данных Яндекс.Музыки c помощью библиотеки Pandas и её возможностей проверить данные и сравнить поведение и предпочтения пользователей двух столиц — Москвы и Санкт-Петербурга.

**Сферы деятельности:** Интернет-сервисы, Стриминговый сервис

**Ключевые слова:** data analyst, аналитик данных, аналитик, analyst

**Ссылка на тетрадку:** 

**Вывод:** Мы проверили три гипотезы и установили:
1. День недели по-разному влияет на активность пользователей в Москве и Петербурге.
2. Музыкальные предпочтения не сильно меняются в течение недели — будь то Москва или Петербург. Небольшие различия заметны в начале недели, по понедельникам:
- в Москве слушают музыку жанра “world”,
- в Петербурге — джаз и классику.
  
3. Во вкусах пользователей Москвы и Петербурга больше общего чем различий. Вопреки ожиданиям, предпочтения жанров в Петербурге напоминают московские.
   
# Проект 2. Исследование надежности заемщиков
**Навыки и инструменты:** Pandas, Python, предобработка данных

**Задачи проекта:** На основе статистики о платёжеспособности клиентов исследовать влияет ли семейное положение и количество детей клиента на факт возврата кредита в срок.

**Сферы деятельности:** Банковская сфера, Кредитование

**Ключевые слова:** data analyst, аналитик данных, аналитик, финансовый аналитик, analyst

**Ссылка на тетрадку:**

**Вывод:** Исследование зависимости между количеством детей и возвратом кредита в срок показало, что меньшая доля должников среди клиентов без детей, несмотря на то, что таких клиентов больше по сравнению с остальными, доля задолженностей составляет 7,5%, что является наименьшим значением. Задолженностей среди людей с 1-2 детьми больше, их доля почти на 2% превышает задолженности бездетных клиентов.

Анализ зависимости семейного положения и возврата кредита в срок показал, что заемщики, состоящие или состоявшие в браке реже допускают просрочку по кредиту. Аналогичный показатель у свободных людей или находящихся в гражданском браке на 2-3% больше.

В ходе исследования выяснилось, что чаще берут кредит люди, имеющие доход от 50001 до 1000000 рублей в месяц, при этом доля задолженностей от общего числа кредитов составляет 7-8,5%. Более ответственными являются клиенты с доходом 200001-1000000 рублей в месяц. Проанализировать остальные группы по доходу не удалось, так как данных по ним крайне мало для получения выводов.
Самой обширной категорией по цели получения кредита являются клиенты, приобретающие недвижимость, при этом они оказались самыми ответственными, среди них меньше всего должников, на втором месте оказались кредитополучатели, целью которых было проведение свадьбы, их показатель отличается всего на 0,5 процента
Таким образом, были проанализированы зависимости разных критериев и погашение кредита в срок и выявлены самые ответственным клиенты в каждой категории.

# Проект 3. Продажа квартир в Санкт-Петербурге — анализ рынка недвижимости
**Навыки и инструменты:** Matplotlib,  Pandas, Python, визуализация данных, исследовательский анализ данных, предобработка данных

**Задачи проекта:** Используя данные сервиса Яндекс.Недвижимость, определить рыночную стоимость объектов недвижимости и типичные параметры квартир

**Сферы деятельности:** Интернет-сервисы, Площадки объявлений

**Ключевые слова:** маркетинговый аналитик, фрод аналитик, fraud analyst, data analyst, аналитик данных, аналитик, analyst

**Ссылка на тетрадку:**

**Вывод**
Был проведен исследовательский анализ данных на выявление зависимости различных факторов на конечную цену квартиры. Было выявлено, за сколько дней в среднем продается квартира. Результат-96 дней. Быстрыми продажами считаются те, срок размещения объявлений которых меньше этого числа, долгими- те, срок размещения которых больше 96 дней.

Была изучена зависимость цены от общей площади, жилой площади, площади кухни, количества комнат, типа этажа квартиры и даты размещения объявления. Практически во всех случаев, за исключением типа этажа и даты размещения объявления, корреляция положительна, то есть цена растет пропорционально увеличению площади или количества комнат.

Была найдена средняя цена одного квадратного метра в 10 населенных пунктах с наибольшим числом объявлений. Самая высокая цена за кв.м в Санкт-Петербурге, а самая низкая - в Всеволжске.

Была так же вычислена средння цена каждого километра от центра Санкт-Петербурга. Оказалось, что средняя цена каждого километра все меньше при удалении от центра.

Таким образом, можно сказать, что на цену квартиры влияет совокупность факторов, таких как, количество комнат, площадь квартиры, этаж, удаленность от центра и другие.


# Проект 4. Исследование поведения пользователей сервиса аренды самокатов
**Навыки и инструменты:** Matplotlib, NumPy, Pandas, Python, SciPy, описательная статистика, проверка статистических гипотез

**Задачи проекта:** Проверите гипотезы сервиса аренды самокатов, чтобы помочь вырастить бизнес.

**Сферы деятельности:** Телеком

**Ключевые слова:** аналитик, analyst, аналитик данных, data analyst

**Ссылка на тетрадку:**

**Вывод:**
В ходе работы была создана общая таблица с данными и 2 отдельных, с данными о поездках пользователей с подпиской и без. По ним была визуализирована информация о расстоянии и времени поездок для пользователей обеих категорий.
Была найдена помесячная выручка, которую принёс каждый пользователь.
Также были проверены три гипотезы и были сделаны следующие выводы:
1.	Пользователи с подпиской тратят больше времени на поездки в сервисе
2.	Расстояние, которое проезжают пользователи с подпиской не превышает оптимальное с точки зрения износа самоката
3.	Помесячная выручка от пользователей с подпиской по месяцам выше, чем выручка от пользователей без подписки.

Подводя итог, можем сказать, что пользователи с подпиской действительно являются более выгодными для компании, так как они тратят больше времени на поездки и приносят больше выручки каждый месяц по сравнению с пользователями, не использующими подписку. Компании следует расширять долю пользователей с подпиской, привлекая различные рекламные кампании и акции, это поможет сервису нарастить свою прибыль и привлечь новых пользователей.

# Проект 5. Изучение закономерностей, определяющих успешность игр
**Навыки и инструменты:** Matplotlib, NumPy, Pandas, Python, исследовательский анализ данных, описательная статистика, предобработка данных, проверка статистических гипотез

**Задачи проекта:** Используя исторические данные о продажах компьютерных игр, оценки пользователей и экспертов, жанры и платформы, выявить закономерности, определяющие успешность игры 

**Сферы деятельности:** Gamedev, Интернет-магазины

**Ключевые слова:** игровой аналитик, game analyst, аналитик игрового проекта, продуктовый аналитик, product analyst, gamedev analyst, аналитик геймдев

**Ссылка на тетрадку:**

**Вывод:**
В ходе работы было изучено, сколько игр выпускалось каждый год. Оказалось, что нужны не все данные, а лишь с 1994 года. Были найдены платформы с наибольшими продажами и построено их распределение по годам.

Актуальными лидерами в промежутке за 2005-2015 год стали PS4, XOne и 3DS.Было выявлено, что каждая платформа живет в среднем около 10 лет, затем на смену ей приходит новая.

Было выявлено довольно сильное влияние оценок критиков на продажи, корреляция около 0.4.

Самым прибыльными жанрами оказались action, sports и shooter

Был составлен портрет пользователя каждого региона. При этом можно отметить, что по всем параметрам Европа и Америка были очень похожи между собой, в то время как Япония всегда чем-либо выделялась.

Также было замечено, что самые прибыльные игры- возрастной категории для всех, в каждом регионе они пользуются большим спросом.

В завершение были проверены две гипотезы. Их результаты:

Средние пользовательские оценки платформ Xbox One и PC не одинаковые

Средние пользовательские рейтинги жанров Action и Sports равны

Подводя итоги, можно сказать, что на успешность игры влияет множестов факторов: жанр, возрастная категория, оценка критиков и даже регион, в котором они планируют продаваться. Вкусы людей разные и выбрать самые успешные продукты, для которых будет готовиться рекламная кампания некорректно, так как каждый любит свое. Тем не менее, можно сказать, что игры в жанре экшен для любых возрастов будут точно беспроигрышным вариантом для продвижения. Их всегда любили и до сих пор любят люди по всему миру.

# Проект 6. Исследование данных об инвестиции венчурных фондов в компании-стартапы
**Навыки и инструменты:** PostgreSQL, SQL

**Задачи проекта:** Произвести различные выгрузки данных венчурных фондов с помощью SQL

**Сферы деятельности:** Инвестиции, Стартапы

**Ключевые слова:** аналитик sql, sql analyst, аналитик, analyst, reporting analyst

**Вывод:** Проект автоматически проверяется в тренажёре SQL. В самостоятельном проекте этого курса работа идёт с базой данных, которая хранит информацию о венчурных фондах и инвестициях в компании-стартапы. Эта база данных основана на датасете Startup Investments, опубликованном на популярной платформе для соревнований по исследованию данных Kaggle.

# Проект 7. Анализ убытков приложения ProcrastinatePRO+
**Навыки и инструменты:** Matplotlib, Pandas, Python, Seaborn, когортный анализ, продуктовые метрики, юнит-экономика

**Задачи проекта:** Задача для маркетингового аналитика развлекательного приложения Procrastinate Pro+. Несмотря на огромные вложения в рекламу, последние несколько месяцев компания терпит убытки. Ваша задача — разобраться в причинах и помочь компании выйти в плюс.

**Сферы деятельности:** Интернет-сервисы, Стартапы

**Ключевые слова:** маркетолог аналитик, marketing analyst, маркетинговый аналитик, веб-аналитик, web-analyst, продуктовый аналитик, product analyst

**Ссылка на тетрадку:**

**Вывод:**
В ходе исследовательского анализа были составлены профили пользователей, определены минимальную и максимальную даты привлечения пользователей. Также была найдена доля платящих пользователей для разных регионов, устройств и каналов привлечения.

Был проведен анализ маркетинга компании:
- Общая сумма расходов на рекламу за все время составила 105497 д.е.
-	Было выявлено что больше всего денег тратили такие каналы привлечения, как TipTop и FaceBoom, они же и привели больше всего клиентов, и их расходы на привлечение одного пользователя оказались максимальными (2.8 и 1.1 соответственно).
-	Среднее значение САС по всем каналам составило менее 1 денежной единицы, а точнее 0.69 д.е.

На последнем этапе была произведена оценка окупаемости рекламы, из чего был сделан вывод, что реклама неэффективна. По направлениям, на которые компания тратит больше всего денег, наблюдаются отрицательные результаты. Причинами этого служат чрезмерные расходы на привлечение одного пользователя. У компании есть удачные кейсы с привлечением клиентов, например, во Франции, Великобритании и Германии. Рекомендация- снизить расходы в Америке, ведь они не приносят выгоды для компании. Нужно обратить внимание также на каналы привлечения, перестать вкладывать деньги в каналы, по типу TipTop. На первый взгляд кажется, что они работают, но при детальном рассмотрении получается, что затраты на одного пользователя очень большие и реклама не окупается. В общем, фирме стоить сократить финансирование на маркетинг по тем каналам, регионам и устройствам, которые не работают.

# Проект 8. Анализ сервиса вопросов и ответов по программированию
**Навыки и инструменты:** PostgreSQL,SQL

**Задачи проекта:** С помощью SQL посчитаете и визуализируете ключевые метрики сервис-системы вопросов и ответов о программировании.

**Сферы деятельности:** Интернет-сервисы

**Ключевые слова:** аналитик sql, sql analyst, аналитик, analyst, reporting analyst, product analyst, продуктовый аналитик


**Вывод:** Написаны все сложные SQL-запросы для подсчёта требуемых значений и метрик.

# Проект 9. Проверка гипотез по увеличению выручки в интернет-магазине — оценить результаты A/B теста
**Навыки и инструменты:** A/B-тестирование, Matplotlib, Pandas, Python, SciPy, проверка статистических гипотез

**Задачи проекта:** Используя данные интернет-магазина приоритезировать гипотезы, произвести оценку результатов A/B-тестирования различными методами

**Сферы деятельности:** Интернет-магазины

**Ключевые слова:** продуктовый аналитик, product analyst, аналитик продукта, product data analyst

**Ссылка на тетрадку:**

**Вывод:** 

Выводы по анализу А/В-теста:
1.	Есть статистически значимое различие по конверсии между группами как по сырым данным, так и после фильтрации аномалий.
2.	Статистически значимых отличий по среднему чеку как по сырым данным, так и после удаления аномалий нет.
3.	График различия конверсии между группами сообщает, что результаты группы B лучше группы A: имеют тенденцию к росту, либо зафиксировались около среднего значения (0.1).
4.	График различия среднего чека колеблется: он-то и позволил нам найти аномалии. Сделать из этого графика определённые выводы нельзя.

Таким образом, тест можно считать успешным. Рекомендую остановить тест, признать его успешным и перейти к проверке следующей гипотезы. Признаем победу группы В.

# Проект 10. Анализ пользовательского поведения в мобильном приложении
**Навыки и инструменты:** A/B-тестирование, Matplotlib, Pandas, Plotly, Python, Seaborn, визуализация данных, проверка статистических гипотез, продуктовые метрики, событийная аналитика

**Задачи проекта:** На основе данных использования мобильного приложения для продажи продуктов питания проанализировать воронку продаж, а также оценить результаты A/A/B-тестирования

**Сферы деятельности:** Бизнес, Интернет-сервисы, Стартапы

**Ключевые слова:** аналитик мобильного приложения, аналитик продукта, продуктовый аналитик, product analyst, mobile app analyst

**Ссылка на тетрадку:**

**Вывод:**
В ходе работы была проанализирована воронка. Воронка пользователей включает 4 события: главная страница - каталог - корзина - оформление заказа. Руководство в воронку мы не брали, так как количество пользователей, совершавших это событие мало на фоне остальных. С самого начала и до последнего события доходят около 48% пользователей приложения. Большинство пользователей отпадает на этапе перехода к странице с предложениями.

Исследование результатов A/A/B-эксперимента показало, что шрифт никак не влияет на поведение пользователей. Значимых различий между контрольными и экспериментальной группами нет.

# Проект 11. Исследования рынка общепита в Москве для принятия решения об открытии нового заведения

**Навыки и инструменты:** Pandas, Plotly, Python, Seaborn, визуализация данных

**Задачи проекта:** Исследование рынка общественного питания на основе открытых данных, подготовка презентации.

**Сферы деятельности:** Бизнес, Оффлайн, Стартапы

**Ключевые слова:** data analyst, аналитик данных, аналитик, analyst

**Ссылка на тетрадку:**

**Вывод:**
В ходе работы был проанализирован рынок заведений общественного питания Москвы. Рынок перенасыщен кафе и ресторанами, а вот тематические кофейни всегда будут актуальны. Концепция заведения, похожая на «Central Pаrk», интересная, но заведение не обязательно должно находиться в центре Москвы. Конкуренция и высокие цены на аренду помещения не дадут кофейне развиться и,скорее всего, она будет постоянно работать в минус.

# Проект 12. Создание дашборда по пользовательским событиям для агрегатора новостей
**Навыки и инструменты:** Tableau, построение дашбордов, продуктовые метрики

**Задачи проекта:** TED— некоммерческий фонд, который проводит популярные конференции. На них выступают специалисты из разных областей и читают лекции на актуальные социальные, культурные и научные темы. Исследуете историю TED-конференций и создадите дашборд в Tableau на основе полученных данных.

**Сферы деятельности:** Стартапы

**Ключевые слова:** bi analyst, bi-аналитик, аналитик данных, data analyst, разработчик системы отчетности, reporting analyst

**Ссылка на тетрадку:**

**Вывод:** Были построены дашборды «История выступлений», «Тематики выступлений», «Авторы выступлений» и дашборд на свободную тему. Также с помощью story была создана презентация и размещена на сайте Tableau Public.

# Проект 13. E-commerce
**Навыки и инструменты:** A/B-тестирование, Matplotlib, Pandas, Plotly, Python, Seaborn, визуализация данных, проверка статистических гипотез, Tableau, построение дашбордов, продуктовые метрики, PostgreSQL, SQL

**Задачи проекта:** На основе всех полученных данных в курсе выполнить буткемп-проект по области e-commerce.

**Сферы деятельности:** Интернет-магазины

**Ключевые слова:** data analyst, аналитик данных

**Ссылка на тетрадку:**

**Вывод:**
В ходе работы мы исследовали профили потребителей интернет-магазина товаров для дома.
-	Определен период исследования: с 1 октября 2018 года и до 31 января 2020 года.
-	Было выявлено, что большая часть покупателей совершали 1 покупку
-	В одном заказе обычно один товар
-	Медианная сумма покупки - 584 д.е.
-	Выручка и количество заказов значительно больше в зимние месяцы.
-	Пользователи были разделены на 8 сегментов по истории их покупок, а конкретно по частоте покупок, давности и стоимости.
-	Все товары были разделены на категории: товары для кухни, спальни, ванной комнаты, уборки, ремонта и растения.
-	Была рассмотрена сезонность покупок по категориям в каждом сегменте.
-	Были проверены гипотезы о наличие статистической значимости средней выручки и давности покупок между сегментами.
-	В целом, разделение на сегменты можно считать корректным, так как большая часть гипотез подтвердилась и разница между сегментами значительная.

В ходе работы были оценены результаты A/B-тестирования.

Была проведена оценка корректности проведения теста:
-	Проверены пользователи по периоду набора, региону регистрации. Количество пользователей из региона EU составило 15% от общего числа пользователей из целевого региона, зарегистрированных в период набора пользователей в тест.
-	Была оценена динамика набора в группы и равномерность распределения пользователей по группам. Оказалось, что группы распределены неравномерно, в контрольной группе значительно больше пользователей. Динамика набора в группы примерно одинаковая, но группа А всегда опережает группу В по количеству набранных людей за исключением 10 декабря.
-	Также были изучены данные о пользовательской активности. Много людей проходили этап авторизации несколько раз. До конца воронки доходит не очень много людей. Есть и те, для которых этап авторизации был первым и последним.
-	Был изучен лайфтайм. Половина пользователей совершают действия в первые 1-2 дня с момента регистрации. Больше чем 5 дней с момента регистрации до события проходит у 25% пользователей.

2.	В ходе исследовательского анализа данных получены следующие выводы:
-	Чаще всего на пользователя приходится до 12 событий. Относительно группы А можно сказать, что большая часть пользователей совершает 4,6,8 и 12 событий. В то время как для пользователей группы В свойственно 4-6 событий. Для группы А медианное значение количества событий на человека равно 6, а для группы В- всего 4 события.
-	Динамика количества событий у двух групп имеет различия. У группы В нет резких всплесков в какой-либо день, события распределены довольно-таки равномерно, в то время как у группы А наблюдается резкий рост количества событий с 13 по 21 декабря, затем такой же резкий спад.
-	Также было выявлено, что в период проведения теста попала маркетинговая кампания Christmas&New Year Promo. Но она не повлияла на динамику событий, наоборот во время ее начала наблюдается спад количества событий обеих групп.
-	Была составлена воронка: авторизация, посещение карточки товара, корзина и оплата. При этом на этапе оплаты уникальных пользователей больше, чем на этапе корзины. Возможно, платформа предполагает такой вариант оплаты без перехода в корзину. Анализ воронок двух групп показал, что положительных различий в конверсии у тестовой группы по сравнению с контрольной нет, то есть ожидаемый эффект по техничскому заданию не достигнут.

3.	Была проведена оценка результатов A/B-тестирования.
-	Проверена статистическая разница долей z-критерием, который показал, что статистически значимых различий между долями двух групп нет. Ожидаемый эффект в изменении конверсии не достигнут.

В целом, можно сказать, что проведение теста было не совсем корректно: не все данные соответствовали требованиям, также выбран не самый лучший период для проведения теста: предновогодняя пора. Изменения в рекомендательной системе себя не оправдали. Из-за того что группа В оказалась даже хуже контрольной группы, скорее всего, при изменении периода тестирования, результаты не изменится кардинально. Значит, такое нововведение не нужно компании. Стоит попробовать другие изменения для повышения конверсии.

Была проанализирована база данных. В ней — информация о книгах, издательствах, авторах, а также пользовательские обзоры книг. Выгрузка данных помогла сформулировать ценностное предложение для нового продукта.
