---
title: Add()
second_title: Справочник API Aspose.Slides для C++
description: Добавляет математический элемент в конец коллекции.
type: docs
weight: 79
url: /ru/aspose.slides.mathtext/mathblock/add/
---
## MathBlock::Add(System::SharedPtr\<IMathElement\>) метод

Добавляет математический элемент в конец коллекции.

```cpp
void Aspose::Slides::MathText::MathBlock::Add(System::SharedPtr<IMathElement> item) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | [IMathElement](../../imathelement/) для добавления в конец коллекции. |
## Примечания

Пример: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
mathBlock->Add(System::MakeObject<MathematicalText>(u"+"));
mathBlock->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [MathBlock](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)