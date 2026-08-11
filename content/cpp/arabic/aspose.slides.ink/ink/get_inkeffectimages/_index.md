---
title: get_InkEffectImages()
second_title: Aspose.Slides للغة C++ – مرجع API
description: يحصل على مجموعة الصور المخصصة المستخدمة لمحاكاة التأثيرات البصرية لفرش الحبر. تُستخدم هذه الصور عند عرض الحبر مع قيم InkEffectType محددة، مثل Galaxy و Rainbow وغيرها. من خلال توفير صورك الخاصة، يمكنك التحكم في كيفية ظهور كل تأثير حبر.
type: docs
weight: 14
url: /ar/aspose.slides.ink/ink/get_inkeffectimages/
---
## Ink::get_InkEffectImages() طريقة

يحصل على مجموعة الصور المخصصة المستخدمة لمحاكاة التأثيرات البصرية لفرشاة الحبر. تُستخدم هذه الصور عند عرض الحبر مع قيم [InkEffectType](../../inkeffecttype/) محددة، مثل Galaxy و Rainbow وغيرها. من خلال توفير صورك الخاصة، يمكنك التحكم في كيفية ظهور كل تأثير حبر.

```cpp
static System::SharedPtr<System::Collections::Generic::IDictionary<InkEffectType, System::SharedPtr<IImage>>> Aspose::Slides::Ink::Ink::get_InkEffectImages()
```

## ملاحظات

تسمح هذه الخاصية باستبدال القوام الافتراضية لتأثير الحبر بأخرى يحددها المستخدم، وهو ما يكون مفيدًا بشكل خاص عندما تكون الأصول الافتراضية مقيدة بالترخيص أو غير متوفرة أثناء التشغيل.

يجب أن يرتبط كل إدخال في القاموس بقيمة [InkEffectType](../../inkeffecttype/) وكائن [IImage](../../../aspose.slides/iimage/) المقابل (مثل Bitmap، أو واجهة صورة **Aspose**).

```cpp
System::SharedPtr<IImage> image = Images::FromFile(u"image.png");
Ink::get_InkEffectImages()->Add(InkEffectType::Galaxy, image);
```

## انظر أيضًا

* تعداد [InkEffectType](../../inkeffecttype/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IDictionary](../../../system.collections.generic/idictionary/)
* فئة [IImage](../../../aspose.slides/iimage/)
* فئة [Ink](../)
* مساحة الاسم [Aspose::Slides::Ink](../../)
* مكتبة [Aspose.Slides](../../../)