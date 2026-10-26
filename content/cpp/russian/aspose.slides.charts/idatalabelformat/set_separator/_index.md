---
title: set_Separator()
second_title: Aspose.Slides для C++ справочник API
description: "Устанавливает или возвращает Variant, представляющий разделитель, используемый для подписей данных на диаграмме. Запишите System::String."
type: docs
weight: 339
url: /ru/aspose.slides.charts/idatalabelformat/set_separator/
---
## IDataLabelFormat::set_Separator(System::String) метод

Устанавливает или возвращает Variant, представляющий разделитель, используемый для подписей данных на диаграмме. Запишите [System::String](../../../system/string/).

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_Separator(System::String value)=0
```

## Примечания

Если родитель этого [DataLabelFormat](../../datalabelformat/) объекта является коллекцией [DataLabelCollection](../../datalabelcollection/) подписей данных, то это свойство получает или задаёт значение по умолчанию свойства Separator для новых подписей данных в коллекции [DataLabelCollection](../../datalabelcollection/). Установка этого свойства значением также задаёт это значение свойству Separator для всех подписей данных в коллекции [DataLabelCollection](../../datalabelcollection/) (например, "DataLabels.DefaultDataLabelFormat.Separator = val;" приводит к тому, что все DataLabels[i].Separator равны val).

## Смотрите также

* Класс [String](../../../system/string/)
* Класс [IDataLabelFormat](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)