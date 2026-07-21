---
title: CopyTo()
second_title: Справка API Aspose.Slides для C++
description: Копировать в указанный массив.
type: docs
weight: 118
url: /ru/aspose.slides.mathtext/mathblock/copyto/
---
## MathBlock::CopyTo(System::ArrayPtr\<System::SharedPtr\<IMathElement\>\>, int32_t) method

Копировать в указанный массив.

```cpp
void Aspose::Slides::MathText::MathBlock::CopyTo(System::ArrayPtr<System::SharedPtr<IMathElement>> array, int32_t arrayIndex) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>\> | Массив, в который копировать. |
| arrayIndex | **int32_t** | Индекс, с которого начинать копирование. |
## Примечания



Пример: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
auto destinationArray = System::MakeArray<System::SharedPtr<IMathElement>>(mathBlock->get_Count());
mathBlock->CopyTo(destinationArray, 0);
```

## См. также

* Типовое определение [ArrayPtr](../../../system/arrayptr/)
* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [MathBlock](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)