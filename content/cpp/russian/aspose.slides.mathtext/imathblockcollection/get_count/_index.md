---
title: get_Count()
second_title: Справочник API Aspose.Slides для C++
description: Получает количество элементов, фактически содержащихся в коллекции. Только для чтения int32_t.
type: docs
weight: 1
url: /ru/aspose.slides.mathtext/imathblockcollection/get_count/
---
## IMathBlockCollection::get_Count() метод

Получает количество элементов, фактически содержащихся в коллекции. Только для чтения **int32_t**.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathBlockCollection::get_Count()=0
```

## Примечания

Пример: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
int32_t blocksCount = blockCollection->get_Count();
```

## См. также

* Класс [IMathBlockCollection](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)