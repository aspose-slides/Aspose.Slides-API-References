---
title: MathRadical()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بتهيئة نسخة جديدة من فئة MathRadical.
type: docs
weight: 53
url: /ar/aspose.slides.mathtext/mathradical/mathradical/
---
## MathRadical::MathRadical(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) منشئ

يقوم بتهيئة نسخة جديدة من الفئة [MathRadical](../).

```cpp
Aspose::Slides::MathText::MathRadical::MathRadical(System::SharedPtr<IMathElement> baseArgument, System::SharedPtr<IMathElement> degreeArgument)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | القاعدة |
| degreeArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | الدرجة |

## ملاحظات

مثال:
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
```

## انظر أيضاً

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElement](../../imathelement/)
* فئة [MathRadical](../)
* مساحة الأسماء [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)