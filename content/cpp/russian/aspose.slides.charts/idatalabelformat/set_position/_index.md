---
title: set_Position()
second_title: Aspose.Slides для C++ справочник API
description: Представляет положение подписи данных. Запишите LegendDataLabelPosition.
type: docs
weight: 79
url: /ru/aspose.slides.charts/idatalabelformat/set_position/
---
## IDataLabelFormat::set_Position(LegendDataLabelPosition) method


Представляет положение подписи данных. Запишите [LegendDataLabelPosition](../../legenddatalabelposition/).

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_Position(LegendDataLabelPosition value)=0
```

## Примечания


Если родитель этого [DataLabelFormat](../../datalabelformat/) объекта является [DataLabelCollection](../../datalabelcollection/) коллекцией подписей данных, то это свойство получает или задает значение по умолчанию свойства Position для новых подписей данных в коллекции [DataLabelCollection](../../datalabelcollection/). Представляет положение для объектов [DataLabel](../../datalabel/). Установка этого свойства со значением также задает это значение свойству Position для всех подписей данных в коллекции [DataLabelCollection](../../datalabelcollection/) (например, "DataLabels.DefaultDataLabelFormat.Position = val;" приводит к тому, что все DataLabels[i].Position равны val).

## См. также

* Перечисление [LegendDataLabelPosition](../../legenddatalabelposition/)
* Класс [IDataLabelFormat](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)