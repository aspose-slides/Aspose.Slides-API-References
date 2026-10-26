---
title: GetEffective()
second_title: راهنمای API Aspose.Slides برای C++
description: داده‌های قالب‌بندی بولت مؤثر را با اعمال ارث‌بری دریافت می‌کند.
type: docs
weight: 248
url: /fa/aspose.slides/ibulletformat/geteffective/
---
## IBulletFormat::GetEffective() متد


داده‌های قالب‌بندی بولت مؤثر را با اعمال ارث‌بری دریافت می‌کند.

```cpp
virtual System::SharedPtr<IBulletFormatEffectiveData> Aspose::Slides::IBulletFormat::GetEffective()=0
```


### مقدار بازگشت

یک [IBulletFormatEffectiveData](../../ibulletformateffectivedata/).
## توضیحات



این مثال نشان می‌دهد که چگونه برخی از ویژگی‌های قالب بولت مؤثر را دریافت می‌کنیم. 
```cpp
using namespace System;
using namespace Aspose::Slides;

auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<Aspose::Slides::IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveBulletFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_ParagraphFormat()->get_Bullet()->GetEffective();

Console::WriteLine(String(u"Bullet type: ") + ObjectExt::ToString(effectiveBulletFormat->get_Type()));
if (effectiveBulletFormat->get_Type() == Aspose::Slides::BulletType::Numbered)
{
    Console::WriteLine(String(u"Numbered style: ") + ObjectExt::ToString(effectiveBulletFormat->get_NumberedBulletStyle()));
    Console::WriteLine(String(u"Starting number: ") + effectiveBulletFormat->get_NumberedBulletStartWith());
}
```

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IBulletFormatEffectiveData](../../ibulletformateffectivedata/)
* کلاس [IBulletFormat](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)