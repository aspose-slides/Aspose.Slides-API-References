---
title: get_Separator()
second_title: Aspose.Slides для C++ API Reference
description: "Устанавливает или возвращает Variant, представляющий разделитель, используемый для меток данных на диаграмме. См. System::String."
type: docs
weight: 326
url: /ru/aspose.slides.charts/datalabelformat/get_separator/
---
## DataLabelFormat::get_Separator() метод

Устанавливает или возвращает Variant, представляющий разделитель, используемый для меток данных на диаграмме. См. [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::Charts::DataLabelFormat::get_Separator() override
```

## Примечания

Если родитель этого объекта [DataLabelFormat](../) является коллекцией [DataLabelCollection](../../datalabelcollection/) меток данных, то это свойство получает или задает значение по умолчанию свойства Separator для новых меток данных в коллекции [DataLabelCollection](../../datalabelcollection/). Установка этого свойства со значением также задает это значение свойству Separator для всех меток данных в коллекции [DataLabelCollection](../../datalabelcollection/) (например, "DataLabels.DefaultDataLabelFormat.Separator = val;" что приводит к тому, что у всех DataLabels[i].Separator будет равно val).

## См. также

* Класс [String](../../../system/string/)
* Класс [DataLabelFormat](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)