---
title: GetEffective()
second_title: Aspose.Slides برای مرجع API C++
description: داده‌های قالب‌بندی گلوله مؤثر را با اعمال وراثت دریافت می‌کند.
type: docs
weight: 248
url: /fa/aspose.slides/bulletformat/geteffective/
---
## BulletFormat::GetEffective() متد


داده‌های قالب‌بندی گلوله مؤثر را با اعمال وراثت دریافت می‌کند.

```cpp
System::SharedPtr<IBulletFormatEffectiveData> Aspose::Slides::BulletFormat::GetEffective() override
```


### مقدار بازگردانده شده

یک [IBulletFormatEffectiveData](../../ibulletformateffectivedata/).
## توضیحات



این مثال دریافت برخی از خصوصیات قالب‌بندی گلوله مؤثر را نشان می‌دهد.
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

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IBulletFormatEffectiveData](../../ibulletformateffectivedata/)
* کلاس [BulletFormat](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)