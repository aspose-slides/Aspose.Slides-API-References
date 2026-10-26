---
title: get_ShowBubbleSize()
second_title: Aspose.Slides для C++ справка API
description: Представляет поведение отображения значения размера пузырька подписи данных заданной диаграммы. True отображает значение размера пузырька. False скрыть. Читает bool.
type: docs
weight: 222
url: /ru/aspose.slides.charts/datalabelformat/get_showbubblesize/
---
## DataLabelFormat::get_ShowBubbleSize() method

Представляет поведение отображения значения размера пузырька подписи данных заданной диаграммы. True отображает значение размера пузырька. False — скрыть. Читает **bool**.

```cpp
bool Aspose::Slides::Charts::DataLabelFormat::get_ShowBubbleSize() override
```

## Remarks

Если родитель этого [DataLabelFormat](../) объекта является коллекцией [DataLabelCollection](../../datalabelcollection/) подписей данных, то это свойство получает или задает значение по умолчанию свойства ShowBubbleSize для новых подписей данных в коллекции [DataLabelCollection](../../datalabelcollection/). Установка этого свойства со значением также задаёт это значение свойству ShowBubbleSize для всех подписей данных в коллекции [DataLabelCollection](../../datalabelcollection/) (т. е. "DataLabels.DefaultDataLabelFormat.ShowBubbleSize = val;" приводит к тому, что у всех DataLabels[i].ShowBubbleSize будет равно val).

## See Also

* Class [DataLabelFormat](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)