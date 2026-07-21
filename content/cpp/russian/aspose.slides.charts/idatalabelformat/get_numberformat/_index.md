---
title: get_NumberFormat()
second_title: Aspose.Slides для C++ справка по API
description: "Представляет строку формата для объекта DataLabels. Читать System::String."
type: docs
weight: 27
url: /ru/aspose.slides.charts/idatalabelformat/get_numberformat/
---
## IDataLabelFormat::get_NumberFormat() метод


Представляет строку формата для объекта DataLabels. Читать [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Charts::IDataLabelFormat::get_NumberFormat()=0
```

## Примечания



```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```


Если родительский объект этого [DataLabelFormat](../../datalabelformat/) является [DataLabelCollection](../../datalabelcollection/) коллекцией подписей данных, то это свойство получает или задаёт значение свойства NumberFormat по умолчанию для новых подписей данных в коллекции [DataLabelCollection](../../datalabelcollection/). Когда этому свойству присваивается значение, оно также присваивается свойству NumberFormat для всех подписей данных в коллекции [DataLabelCollection](../../datalabelcollection/) (i.e. \"DataLabels.DefaultDataLabelFormat.NumberFormat = val;\" приводит к тому, что у всех DataLabels[i].NumberFormat будет равно val). 
## Смотрите также

* Класс [String](../../../system/string/)
* Класс [IDataLabelFormat](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)