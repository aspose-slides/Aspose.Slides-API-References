---
title: set_NumberFormat()
second_title: Aspose.Slides для C++ справочник API
description: "Представляет строку формата для объекта DataLabels. Запишите System::String."
type: docs
weight: 40
url: /ru/aspose.slides.charts/datalabelformat/set_numberformat/
---
## DataLabelFormat::set_NumberFormat(System::String) метод

Представляет строку формата для объекта DataLabels. Запишите [System::String](../../../system/string/).

```cpp
void Aspose::Slides::Charts::DataLabelFormat::set_NumberFormat(System::String value) override
```

## Примечания

```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```

Если родитель объекта [DataLabelFormat](../) является коллекцией [DataLabelCollection](../../datalabelcollection/) меток данных, то это свойство получает или задает значение по умолчанию свойства NumberFormat для новых меток данных в коллекции [DataLabelCollection](../../datalabelcollection/). Когда этому свойству назначается значение, это значение также задаётся для свойства NumberFormat всех меток данных в коллекции [DataLabelCollection](../../datalabelcollection/) (т. е. "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" приводит к тому, что все DataLabels[i].NumberFormat будет равно val).

## См. также

* Класс [String](../../../system/string/)
* Класс [DataLabelFormat](../)
* Пространство имен [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)