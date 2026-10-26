---
title: SetSuperscript()
second_title: Aspose.Slides для справки API C++
description: Создает надстрочный индекс
type: docs
weight: 79
url: /ru/aspose.slides.mathtext/mathelementbase/setsuperscript/
---
## MathElementBase::SetSuperscript(System::SharedPtr\<IMathElement\>) метод

Создает надстрочный индекс

```cpp
System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSuperscript(System::SharedPtr<IMathElement> superscript) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Надстрочный индекс (верхний индекс справа) |

### Возвращаемое значение

Новый математический элемент типа [IMathSuperscriptElement](../../imathsuperscriptelement/)
## Замечания



Пример: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"4");
auto superscript = element->SetSuperscript(index);
```

## MathElementBase::SetSuperscript(System::String) метод

Создает надстрочный индекс

```cpp
System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSuperscript(System::String superscript) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| superscript | [System::String](../../../system/string/) | Надстрочный индекс (верхний индекс справа) |

### Возвращаемое значение

Новый математический элемент типа [IMathSuperscriptElement](../../imathsuperscriptelement/)
## Замечания



Пример: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto superscript = element->SetSuperscript(u"4");
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathSuperscriptElement](../../imathsuperscriptelement/)
* Класс [IMathElement](../../imathelement/)
* Класс [MathElementBase](../)
* Класс [String](../../../system/string/)
* Пространство имен [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)