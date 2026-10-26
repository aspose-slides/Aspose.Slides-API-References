---
title: get_ShowLabelValueFromCell()
second_title: Справочник API Aspose.Slides для C++
description: Представляет поведение отображения значения ячейки подписи данных заданной диаграммы. True отображает значение ячейки. False скрывает. Читает bool.
type: docs
weight: 300
url: /ru/aspose.slides.charts/idatalabelformat/get_showlabelvaluefromcell/
---
## IDataLabelFormat::get_ShowLabelValueFromCell() метод

Представляет поведение отображения значения ячейки подписи данных заданной диаграммы. True отображает значение ячейки. False скрывает. Читает **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowLabelValueFromCell()=0
```

## Примечания

Если родитель этого объекта [DataLabelFormat](../../datalabelformat/) является коллекцией [DataLabelCollection](../../datalabelcollection/) подпосрей данных, то это свойство получает или задаёт значение по умолчанию свойства ShowLabelValueFromCell для новых подписей данных в коллекции [DataLabelCollection](../../datalabelcollection/). Установка этого свойства со значением также задаёт это значение свойству ShowLabelValueFromCell для всех подписей данных в коллекции [DataLabelCollection](../../datalabelcollection/) (т.е. "DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;" приводит к тому, что у всех DataLabels[i].ShowLabelValueFromCell равно val).

## См. также

* Класс [IDataLabelFormat](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)