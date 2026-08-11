---
title: SetSubSuperscriptOnTheRight()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ كتابة سفلية وكتابة علوية على اليمين
type: docs
weight: 105
url: /ar/aspose.slides.mathtext/imathelement/setsubsuperscriptontheright/
---
## IMathElement::SetSubSuperscriptOnTheRight(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) طريقة

ينشئ كتابة سفلية وكتابة علوية على اليمين

```cpp
virtual System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheRight(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript)=0
```

### المعطيات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | كتابة سفلية (مؤشر سفلي على اليمين) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | كتابة علوية (مؤشر عُلوي على اليمين) |

### قيمة الإرجاع

عنصر رياضي جديد من النوع [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
## ملاحظات



مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(subscript, superscript);
```

## IMathElement::SetSubSuperscriptOnTheRight(System::String, System::String) طريقة

ينشئ كتابة سفلية وكتابة علوية على اليمين

```cpp
virtual System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheRight(System::String subscript, System::String superscript)=0
```

### المعطيات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | كتابة سفلية (مؤشر سفلي على اليمين) |
| superscript | [System::String](../../../system/string/) | كتابة علوية (مؤشر عُلوي على اليمين) |

### قيمة الإرجاع

عنصر رياضي جديد من النوع [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
## ملاحظات



مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(u"i", u"j");
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
* فئة [IMathElement](../)
* فئة [String](../../../system/string/)
* مساحة الاسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)