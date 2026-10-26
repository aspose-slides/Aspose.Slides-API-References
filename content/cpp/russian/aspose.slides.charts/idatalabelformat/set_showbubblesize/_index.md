---
title: set_ShowBubbleSize()
second_title: Aspose.Slides для C++ справочник API
description: Представляет поведение отображения значения размера пузыря подписи данных заданной диаграммы. True отображает значение размера пузыря. False скрывает его. Записать bool.
type: docs
weight: 235
url: /ru/aspose.slides.charts/idatalabelformat/set_showbubblesize/
---
## IDataLabelFormat::set_ShowBubbleSize(bool) метод

Представляет поведение отображения значения размера пузыря подписи данных заданной диаграммы. True отображает значение размера пузыря. False скрывает его. Записать **bool**.

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowBubbleSize(bool value)=0
```

## Замечания

Если родитель этого объекта [DataLabelFormat](../../datalabelformat/) является коллекцией [DataLabelCollection](../../datalabelcollection/) подписей данных, то это свойство получает или задаёт значение по умолчанию свойства ShowBubbleSize для новых подписей данных в коллекции [DataLabelCollection](../../datalabelcollection/). Установка этого свойства значением также задаёт это значение свойству ShowBubbleSize для всех подписей данных в коллекции [DataLabelCollection](../../datalabelcollection/) (например, "DataLabels.DefaultDataLabelFormat.ShowBubbleSize = val;" приводит к тому, что у всех DataLabels[i].ShowBubbleSize будет равно val).

## См. также

* Класс [IDataLabelFormat](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)