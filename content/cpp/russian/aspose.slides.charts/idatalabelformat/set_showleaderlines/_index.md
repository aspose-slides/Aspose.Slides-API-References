---
title: set_ShowLeaderLines()
second_title: Aspose.Slides для C++ справочник API
description: Представляет поведение отображения линий-соединителей подписей данных указанной диаграммы. True отображает линии-соединители. False скрывает их. Записывается bool.
type: docs
weight: 261
url: /ru/aspose.slides.charts/idatalabelformat/set_showleaderlines/
---
## IDataLabelFormat::set_ShowLeaderLines(bool) метод

Представляет поведение отображения линий-соединителей подписей данных заданной диаграммы. True отображает линии-соединители. False скрывает их. Записывается **bool**.

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowLeaderLines(bool value)=0
```

## Примечания

Если родитель этого объекта [DataLabelFormat](../../datalabelformat/) является коллекцией [DataLabelCollection](../../datalabelcollection/) подписей данных, то это свойство получает или устанавливает значение по умолчанию свойства ShowLeaderLines для новых подписей данных в коллекции [DataLabelCollection](../../datalabelcollection/). Установка этого свойства со значением также задаёт это значение свойству ShowLeaderLines для всех подписей данных в коллекции [DataLabelCollection](../../datalabelcollection/) (т. е. \"DataLabels.DefaultDataLabelFormat.ShowLeaderLines = val;\" приводит к тому, что для всех DataLabels[i].ShowLeaderLines равно val).

## См. также

* Класс [IDataLabelFormat](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)