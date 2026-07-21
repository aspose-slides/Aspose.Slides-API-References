---
title: set_ShowValue()
second_title: Справочник API Aspose.Slides для C++
description: Представляет поведение отображения процентного значения подписи данных заданной диаграммы. True отображает процентное значение. False скрывает. Записывается bool.
type: docs
weight: 131
url: /ru/aspose.slides.charts/idatalabelformat/set_showvalue/
---
## IDataLabelFormat::set_ShowValue(bool) метод

Представляет поведение отображения процентного значения подписи данных заданной диаграммы. True отображает процентное значение. False скрывает. Записывается **bool**.

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowValue(bool value)=0
```

## Примечания

Если родитель этого [DataLabelFormat](../../datalabelformat/) объекта является [DataLabelCollection](../../datalabelcollection/) коллекцией подписей данных, то это свойство получает или задает значение по умолчанию свойства ShowValue для новых подписей данных в коллекции [DataLabelCollection](../../datalabelcollection/). Установка этого свойства значением также задаёт это значение свойству ShowValue для всех подписей данных в коллекции [DataLabelCollection](../../datalabelcollection/) (т. е. \"DataLabels.DefaultDataLabelFormat.ShowValue = val;\" приводит к тому, что все DataLabels[i].ShowValue равны val).

## См. также

* Класс [IDataLabelFormat](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)