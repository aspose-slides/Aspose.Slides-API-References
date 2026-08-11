---
title: SetSuperscript()
second_title: Aspose.Slides لـ C++ مرجع API
description: ينشئ كتابة علوية
type: docs
weight: 79
url: /ar/aspose.slides.mathtext/mathelementbase/setsuperscript/
---
## MathElementBase::SetSuperscript(System::SharedPtr\<IMathElement\>) طريقة

ينشئ كتابة علوية

```cpp
System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSuperscript(System::SharedPtr<IMathElement> superscript) override
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | كتابة علوية (مؤشر علوي على اليمين) |

### قيمة الإرجاع

عنصر رياضي جديد من النوع [IMathSuperscriptElement](../../imathsuperscriptelement/)
## ملاحظات



مثال: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"4");
auto superscript = element->SetSuperscript(index);
```

## MathElementBase::SetSuperscript(System::String) طريقة

ينشئ كتابة علوية

```cpp
System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSuperscript(System::String superscript) override
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| superscript | [System::String](../../../system/string/) | كتابة علوية (مؤشر علوي على اليمين) |

### قيمة الإرجاع

عنصر رياضي جديد من النوع [IMathSuperscriptElement](../../imathsuperscriptelement/)
## ملاحظات



مثال: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto superscript = element->SetSuperscript(u"4");
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathSuperscriptElement](../../imathsuperscriptelement/)
* فئة [IMathElement](../../imathelement/)
* فئة [MathElementBase](../)
* فئة [String](../../../system/string/)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)