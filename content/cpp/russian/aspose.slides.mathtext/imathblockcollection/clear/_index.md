---
title: Clear()
second_title: Справочник API Aspose.Slides для C++
description: Удаляет все элементы из коллекции.
type: docs
weight: 118
url: /ru/aspose.slides.mathtext/imathblockcollection/clear/
---
## IMathBlockCollection::Clear() метод


Удаляет все элементы из коллекции.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Clear()=0
```

## Примечания


Пример: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
blockCollection->Clear();
```

## Смотрите также

* Класс [IMathBlockCollection](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)