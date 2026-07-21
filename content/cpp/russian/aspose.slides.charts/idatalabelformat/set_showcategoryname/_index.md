---
title: set_ShowCategoryName()
second_title: Aspose.Slides для C++ справки по API
description: Представляет поведение отображения имени категории подписи данных заданной диаграммы. Истина — отображать имя категории для подписей данных на диаграмме. Ложь — скрывать. Записать bool.
type: docs
weight: 157
url: /ru/aspose.slides.charts/idatalabelformat/set_showcategoryname/
---
## IDataLabelFormat::set_ShowCategoryName(bool) метод

Представляет поведение отображения имени категории подписи данных заданной диаграммы. Истина — отображать имя категории для подписей данных на диаграмме. Ложь — скрывать. Записать **bool**.

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowCategoryName(bool value)=0
```

## Примечания

Если родитель объекта [DataLabelFormat](../../datalabelformat/) является [DataLabelCollection](../../datalabelcollection/) коллекцией подписей данных, то это свойство получает или задает значение по умолчанию свойства ShowCategoryName для новых подписей данных в коллекции [DataLabelCollection](../../datalabelcollection/). Установка этого свойства значением также задает это значение свойству ShowCategoryName для всех подписей данных в коллекции [DataLabelCollection](../../datalabelcollection/) (например, "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" приводит к тому, что у всех DataLabels[i].ShowCategoryName будет равно val).

## См. также

* Класс [IDataLabelFormat](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)