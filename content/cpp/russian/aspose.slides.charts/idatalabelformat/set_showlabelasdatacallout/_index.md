---
title: set_ShowLabelAsDataCallout()
second_title: Справочник API Aspose.Slides для C++
description: Определяет, будет ли метка данных указанной диаграммы отображаться как выноска данных или как метка данных.
type: docs
weight: 287
url: /ru/aspose.slides.charts/idatalabelformat/set_showlabelasdatacallout/
---
## IDataLabelFormat::set_ShowLabelAsDataCallout(bool) method

Определяет, будет ли метка данных указанной диаграммы отображаться как выноска данных или как метка данных.

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowLabelAsDataCallout(bool value)=0
```

## Замечания

Если родитель этого [DataLabelFormat](../../datalabelformat/) объекта является коллекцией [DataLabelCollection](../../datalabelcollection/) меток данных, то это свойство получает или задаёт значение по умолчанию свойства ShowLabelAsDataCallout для новых меток данных в коллекции [DataLabelCollection](../../datalabelcollection/). Установка этого свойства со значением также задаёт это значение свойству ShowLabelAsDataCallout для всех меток данных в коллекции [DataLabelCollection](../../datalabelcollection/) (т. е. \"DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;\" приводит к тому, что все DataLabels[i].ShowLabelAsDataCallout равно val).

## См. также

* Класс [IDataLabelFormat](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)