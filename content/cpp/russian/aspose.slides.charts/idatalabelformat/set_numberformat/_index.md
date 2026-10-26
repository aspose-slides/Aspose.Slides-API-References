---
title: set_NumberFormat()
second_title: Aspose.Slides для справочника API C++
description: "Представляет строку формата для объекта DataLabels. Запишите System::String."
type: docs
weight: 40
url: /ru/aspose.slides.charts/idatalabelformat/set_numberformat/
---
## IDataLabelFormat::set_NumberFormat(System::String) метод


Представляет строку формата для объекта DataLabels. Запишите [System::String](../../../system/string/).

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_NumberFormat(System::String value)=0
```

## Примечания



```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```





Если родитель этого [DataLabelFormat](../../datalabelformat/) объекта является коллекцией [DataLabelCollection](../../datalabelcollection/) меток данных, то это свойство получает или задает значение свойства NumberFormat по умолчанию для новых меток данных в коллекции [DataLabelCollection](../../datalabelcollection/). Когда это свойство устанавливается значением, это значение также задаётся для свойства NumberFormat всех меток данных в коллекции [DataLabelCollection](../../datalabelcollection/) (т. е. \"DataLabels.DefaultDataLabelFormat.NumberFormat = val;\" приводит к тому, что DataLabels[i].NumberFormat равно val). 
## См. также

* Класс [String](../../../system/string/)
* Класс [IDataLabelFormat](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)