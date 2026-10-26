---
title: idx_get()
second_title: Aspose.Slides для справки API C++
description: Получает IMathElement по указанному индексу.
type: docs
weight: 27
url: /ru/aspose.slides.mathtext/mathblock/idx_get/
---
## MathBlock::idx_get(int32_t) метод


Получает [IMathElement](../../imathelement/) по указанному индексу.

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBlock::idx_get(int32_t index) override
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Индекс элемента, начинающийся с нуля |

### Возвращаемое значение

Математический элемент.
## Замечания



Пример: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto firstElem = mathBlock->idx_get(0);
```

## См. также

* Тип-определение [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [MathBlock](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)