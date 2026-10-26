---
title: get_Separator()
second_title: Aspose.Slides для C++ справочник API
description: "Устанавливает или возвращает Variant, представляющий разделитель, используемый для подписей данных на диаграмме. См. System::String."
type: docs
weight: 326
url: /ru/aspose.slides.charts/idatalabelformat/get_separator/
---
## IDataLabelFormat::get_Separator() метод

Устанавливает или возвращает Variant, представляющий разделитель, используемый для подписей данных на диаграмме. См. [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Charts::IDataLabelFormat::get_Separator()=0
```

## Примечания

Если родитель этого [DataLabelFormat](../../datalabelformat/) объекта является коллекцией [DataLabelCollection](../../datalabelcollection/) подписей данных, то это свойство получает или задаёт значение по умолчанию свойства Separator для новых подписей данных в коллекции [DataLabelCollection](../../datalabelcollection/). Установка этого свойства со значением также задаёт это значение свойству Separator для всех подписей данных в коллекции [DataLabelCollection](../../datalabelcollection/) (т.е. \"DataLabels.DefaultDataLabelFormat.Separator = val;\" приводит к тому, что у всех DataLabels[i].Separator будет значение val). 

## См. также

* Класс [String](../../../system/string/)
* Класс [IDataLabelFormat](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)