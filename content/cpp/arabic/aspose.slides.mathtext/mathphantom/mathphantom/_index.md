---
title: MathPhantom()
second_title: مرجع واجهة برمجة تطبيقات Aspose.Slides للغة C++
description: يَنشئ نسخةً جديدةً من فئة MathPhantom باستخدام عنصر الرياضيات الأساسي المحدد.
type: docs
weight: 144
url: /ar/aspose.slides.mathtext/mathphantom/mathphantom/
---
## MathPhantom::MathPhantom(System::SharedPtr\<IMathElement\>) constructor

يُنشئ مثيلاً جديداً للفئة [MathPhantom](../) باستخدام عنصر الرياضيات الأساسي المحدد.

```cpp
Aspose::Slides::MathText::MathPhantom::MathPhantom(System::SharedPtr<IMathElement> element)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | العنصر الأساسي [IMathElement](../../imathelement/) الذي ستُتحكم في رؤيته وتخطيطه بواسطة عنصر الفانتوم. يحدد هذا العنصر المحتوى الذي قد يُخفى أو يُظهر، مع استمرار تأثيره على المحاذاة الهندسية للرياضيات المحيطة. |

## ملاحظات

يُستخدم عنصر الفانتوم لحجز أو قمع المساحة البصرية لتعبيره الأساسي دون ضرورة عرضه. وهو يتوافق مع عنصر OMML **<m:phant>**.

مثال:
```cpp
System::SharedPtr<IMathElement> fraction = System::MakeObject<MathFraction>(
    System::MakeObject<MathematicalText>(u"1"),
    System::MakeObject<MathematicalText>(u"2"));
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElement](../../imathelement/)
* فئة [MathPhantom](../)
* مساحة الاسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)