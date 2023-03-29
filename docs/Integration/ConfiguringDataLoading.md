# Настройка загрузки данных

Все объекты загрузки находятся в подсистеме **"Обмен данными ИБ"** - **"Загрузка"**.

[![1][1]][1]

## Заполнение настроек загрузки

1. **Отправители**

    В справочнике **"Отправители"** хранится информация о текущей ИБ и базах отправителях.

    Для баз отправителей указывается наименование и тип.

    [![2][2]][2]

2. **Правила загрузки**

    Справочник **"Правила загрузки"** содержит информацию о отправителях и типах пакетов. Можно добавить дополнительные данные для загрузки, например значения по умолчанию, которые должны вставать при загрузке.

    [![3][3]][3]

## Загрузка данных

1. Данные из базы источника попадают в **"Очередь входящих пакетов"**

    [![4][4]][4]

    Здесь хранится информация аналогичная [**"Очереди исходящих пакетов базы источника"**](ConfiguringDataUnloading.md) за исключением *Получателя* – вместо него здесь *Отправитель*.

2. Затем нужно обработать очередь входящих пакетов в соответствии с правилами загрузки либо кнопкой **"Обработать"** из формы списка

    [![5][5]][5]

    либо с помощью регламентного задания **"Обмен данными ИБ: Обработка входящих пакетов"**

    [![6][6]][6]

    Если загрузка произошла корректно, то строка из **"Очереди входящих пакетов"** исчезнет. В противном случае – отобразится информация об ошибке.

    Посмотреть ее можно на форме списка **Входящего пакета** на вкладке **Журнал**.

    [![7][7]][7]

    Сам пакет данных можно посмотреть на вкладке **Основное**.

    [![8][8]][8]

3. Информация о всех загруженных пакетах хранится в **"Журнале входящих пакетов"**

[![9][9]][9]

[1]: ConfiguringDataLoading.assets/1.png
[2]: ConfiguringDataLoading.assets/2.png
[3]: ConfiguringDataLoading.assets/3.png
[4]: ConfiguringDataLoading.assets/4.png
[5]: ConfiguringDataLoading.assets/5.png
[6]: ConfiguringDataLoading.assets/6.png
[7]: ConfiguringDataLoading.assets/7.png
[8]: ConfiguringDataLoading.assets/8.png
[9]: ConfiguringDataLoading.assets/9.png