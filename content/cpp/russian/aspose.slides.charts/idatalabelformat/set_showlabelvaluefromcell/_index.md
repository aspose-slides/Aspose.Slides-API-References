---
title: set_ShowLabelValueFromCell()
second_title: Aspose.Slides для C++ справочник API
description: Представляет поведение отображения значения ячейки подписи данных указанной диаграммы. True отображает значение ячейки. False скрывает её. Записывайте bool.
type: docs
weight: 313
url: /ru/aspose.slides.charts/idatalabelformat/set_showlabelvaluefromcell/
---
## IDataLabelFormat::set_ShowLabelValueFromCell(bool) метод

Представляет поведение отображения значения ячейки подписи данных указанной диаграммы. True отображает значение ячейки. False скрывает её. Записывайте **bool**.

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowLabelValueFromCell(bool value)=0
```

## Примечания

Если родителем этого объекта [DataLabelFormat](../../datalabelformat/) является коллекция [DataLabelCollection](../../datalabelcollection/) подписей данных, то это свойство получает или задаёт значение по умолчанию свойства ShowLabelValueFromCell для новых подписей данных в коллекции [DataLabelCollection](../../datalabelcollection/). Установка этого свойства со значением также задаёт это значение свойству ShowLabelValueFromCell для всех подписей данных в коллекции [DataLabelCollection](../../datalabelcollection/) (например, "DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;" приводит к тому, что все DataLabels[i].ShowLabelValueFromCell равны val).

## См. также

* Класс [IDataLabelFormat](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)