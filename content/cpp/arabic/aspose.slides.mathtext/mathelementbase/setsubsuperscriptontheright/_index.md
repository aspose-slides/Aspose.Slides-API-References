---
title: SetSubSuperscriptOnTheRight()
second_title: مرجع API Aspose.Slides للغة C++
description: ينشئ نصًا سفليًا ونصًا علويًا على اليمين
type: docs
weight: 92
url: /ar/aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright/
---
## MathElementBase::SetSubSuperscriptOnTheRight(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method


ينشئ نصًا سفليًا ونصًا علويًا على اليمين

```cpp
System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheRight(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript) override
```


### المعلمات

| معامل | نوع | الوصف |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | نص سفلي (مؤشر سفلي على اليمين) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | نص علوي (مؤشر علوي على اليمين) |

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

## MathElementBase::SetSubSuperscriptOnTheRight(System::String, System::String) method


ينشئ نصًا سفليًا ونصًا علويًا على اليمين

```cpp
System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheRight(System::String subscript, System::String superscript) override
```


### المعلمات

| معامل | نوع | الوصف |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | نص سفلي (مؤشر سفلي على اليمين) |
| superscript | [System::String](../../../system/string/) | نص علوي (مؤشر علوي على اليمين) |

### قيمة الإرجاع

عنصر رياضي جديد من النوع [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
## ملاحظات



مثال: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(u"i", u"j");
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
* فئة [IMathElement](../../imathelement/)
* فئة [MathElementBase](../)
* فئة [String](../../../system/string/)
* مساحة الاسم [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)