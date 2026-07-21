---
title: JoinBlock()
second_title: Справочник API Aspose.Slides для C++
description: Объединяет другой математический блок с этим
type: docs
weight: 27
url: /ru/aspose.slides.mathtext/imathblock/joinblock/
---
## IMathBlock::JoinBlock(System::SharedPtr\<IMathBlock\>) метод

Объединяет другой математический блок с этим

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlock::JoinBlock(System::SharedPtr<IMathBlock> other)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| other | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../)\> | Присоединяемый блок |

### Возвращаемое значение

этот математический блок после объединения
## Примечания



Пример:
```cpp
auto block1 = System::MakeObject<MathSuperscriptElement>(
    System::MakeObject<MathematicalText>(u"c"),
    System::MakeObject<MathematicalText>(u"2")
)->Join(System::MakeObject<MathematicalText>(u"="));
auto block2 = System::MakeObject<MathSuperscriptElement>(
    System::MakeObject<MathematicalText>(u"a"),
    System::MakeObject<MathematicalText>(u"2")
)->Join(System::MakeObject<MathematicalText>(u"+"))->Join(System::MakeObject<MathSuperscriptElement>(System::MakeObject<MathematicalText>(u"b"), System::MakeObject<MathematicalText>(u"2")));
auto block3 = block1->JoinBlock(block2);
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathBlock](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)