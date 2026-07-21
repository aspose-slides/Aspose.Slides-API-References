---
title: get_Count()
second_title: Aspose.Slides для C++: справочник API
description: Возвращает количество элементов, фактически содержащихся в коллекции. Только для чтения int32_t.
type: docs
weight: 1
url: /ru/aspose.slides.mathtext/imathelementcollection/get_count/
---
## IMathElementCollection::get_Count() метод

Возвращает количество элементов, фактически содержащихся в коллекции. Только для чтения **int32_t**.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathElementCollection::get_Count()=0
```

## Примечания

Пример: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
int32_t count = collection->get_Count();
```

## Смотрите также

* Класс [IMathElementCollection](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)