---
title: get_ShowLabelValueFromCell()
second_title: Aspose.Slides для C++ — справочник API
description: Представляет поведение отображения значения ячейки подписи данных указанной диаграммы. Истина отображает значение ячейки. Ложь — скрыть. Читает **bool**.
type: docs
weight: 274
url: /ru/aspose.slides.charts/datalabelformat/get_showlabelvaluefromcell/
---
## DataLabelFormat::get_ShowLabelValueFromCell() метод

Представляет поведение отображения значения ячейки подписи данных заданной диаграммы. Истина отображает значение ячейки. Ложь — скрыть. Читает **bool**.

```cpp
bool Aspose::Slides::Charts::DataLabelFormat::get_ShowLabelValueFromCell() override
```

## Примечания

Если родитель объекта [DataLabelFormat](../) является коллекцией [DataLabelCollection](../../datalabelcollection/) подписей данных, то это свойство получает или задаёт значение по умолчанию свойства ShowLabelValueFromCell для новых подписей данных в коллекции [DataLabelCollection](../../datalabelcollection/). Установка этого свойства со значением также задаёт это значение свойству ShowLabelValueFromCell для всех подписей данных в коллекции [DataLabelCollection](../../datalabelcollection/) (т. е. "DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;" приводит к тому, что у всех DataLabels[i].ShowLabelValueFromCell будет значение val).

## См. также

* Класс [DataLabelFormat](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)