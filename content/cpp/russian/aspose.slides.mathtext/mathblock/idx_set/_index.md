---
title: idx_set()
second_title: Справочник API Aspose.Slides для C++
description: Устанавливает IMathElement по указанному индексу.
type: docs
weight: 40
url: /ru/aspose.slides.mathtext/mathblock/idx_set/
---
## MathBlock::idx_set(int32_t, System::SharedPtr\<IMathElement\>) метод

Устанавливает [IMathElement](../../imathelement/) по указанному индексу.

```cpp
void Aspose::Slides::MathText::MathBlock::idx_set(int32_t index, System::SharedPtr<IMathElement> value)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Нулевой индекс элемента |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Математический элемент. |
## Примечания



Пример:
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto firstElem = mathBlock->idx_get(0);
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [MathBlock](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)