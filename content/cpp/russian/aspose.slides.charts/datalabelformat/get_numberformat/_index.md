---
title: get_NumberFormat()
second_title: Справочник API Aspose.Slides для C++
description: "Представляет строку формата для объекта DataLabels. См. System::String."
type: docs
weight: 27
url: /ru/aspose.slides.charts/datalabelformat/get_numberformat/
---
## DataLabelFormat::get_NumberFormat() метод

Представляет строку формата для объекта DataLabels. См. [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::Charts::DataLabelFormat::get_NumberFormat() override
```

## Примечания

```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```

Если родитель этого [DataLabelFormat](../) объекта является коллекцией [DataLabelCollection](../../datalabelcollection/) меток данных, то это свойство получает или задает значение по умолчанию свойства NumberFormat для новых меток данных в коллекции [DataLabelCollection](../../datalabelcollection/). Когда это свойство устанавливается со значением, это значение также устанавливается для свойства NumberFormat для всех меток данных в коллекции [DataLabelCollection](../../datalabelcollection/) (т. е. \"DataLabels.DefaultDataLabelFormat.NumberFormat = val;\" приводит к тому, что все DataLabels[i].NumberFormat будет равно val).

## См. также

* Класс [String](../../../system/string/)
* Класс [DataLabelFormat](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)