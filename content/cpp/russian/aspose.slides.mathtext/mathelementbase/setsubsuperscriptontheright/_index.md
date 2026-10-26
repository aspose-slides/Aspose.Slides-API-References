---
title: SetSubSuperscriptOnTheRight()
second_title: Справочник API Aspose.Slides для C++
description: Создает подстрочный и надстрочный индексы справа
type: docs
weight: 92
url: /ru/aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright/
---
## MathElementBase::SetSubSuperscriptOnTheRight(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method

Создает подстрочный и надстрочный индексы справа

```cpp
System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheRight(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Подстрочный (нижний индекс справа) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Надстрочный (верхний индекс справа) |

### Возвращаемое значение

Новый математический элемент типа [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
## Примечания



Пример: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(subscript, superscript);
```

## MathElementBase::SetSubSuperscriptOnTheRight(System::String, System::String) method

Создает подстрочный и надстрочный индексы справа

```cpp
System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheRight(System::String subscript, System::String superscript) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Подстрочный (нижний индекс справа) |
| superscript | [System::String](../../../system/string/) | Надстрочный (верхний индекс справа) |

### Возвращаемое значение

Новый математический элемент типа [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
## Примечания



Пример: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(u"i", u"j");
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
* Класс [IMathElement](../../imathelement/)
* Класс [MathElementBase](../)
* Класс [String](../../../system/string/)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)