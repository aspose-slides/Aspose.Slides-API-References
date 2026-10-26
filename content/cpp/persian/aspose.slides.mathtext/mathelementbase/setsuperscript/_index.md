---
title: SetSuperscript()
second_title: مرجع API Aspose.Slides برای C++
description: نمای فوقانی ایجاد می‌کند
type: docs
weight: 79
url: /fa/aspose.slides.mathtext/mathelementbase/setsuperscript/
---
## MathElementBase::SetSuperscript(System::SharedPtr\<IMathElement\>) متد

Creates superscript

```cpp
System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSuperscript(System::SharedPtr<IMathElement> superscript) override
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | فرانویس (شاخص بالایی در سمت راست) |

### مقدار بازگشت

New math element of type [IMathSuperscriptElement](../../imathsuperscriptelement/)
## یادداشت‌ها



Example: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"4");
auto superscript = element->SetSuperscript(index);
```

## MathElementBase::SetSuperscript(System::String) متد

Creates superscript

```cpp
System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSuperscript(System::String superscript) override
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| superscript | [System::String](../../../system/string/) | فرانویس (شاخص بالایی در سمت راست) |

### مقدار بازگشت

New math element of type [IMathSuperscriptElement](../../imathsuperscriptelement/)
## یادداشت‌ها



Example: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto superscript = element->SetSuperscript(u"4");
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathSuperscriptElement](../../imathsuperscriptelement/)
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)