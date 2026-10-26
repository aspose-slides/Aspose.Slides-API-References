---
title: GetEffective()
second_title: مرجع API Aspose.Slides برای C++
description: داده‌های مؤثر پس‌زمینه را با اعمال وراثت دریافت می‌کند.
type: docs
weight: 118
url: /fa/aspose.slides/background/geteffective/
---
## Background::GetEffective() متد

داده‌های مؤثر پس‌زمینه را با اعمال وراثت دریافت می‌کند.

```cpp
System::SharedPtr<IBackgroundEffectiveData> Aspose::Slides::Background::GetEffective() override
```

### مقدار بازگشتی

یک [IBackgroundEffectiveData](../../ibackgroundeffectivedata/).

## توضیحات

این مثال نحوه دریافت ویژگی‌های مؤثر پس‌زمینه را نشان می‌دهد.
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveBackground = pres->get_Slides()->idx_get(0)->get_Background()->GetEffective();
Console::WriteLine(String(u"Background fill type: ") + ObjectExt::ToString(effectiveBackground->get_FillFormat()->get_FillType()));
Console::WriteLine(String(u"Any effects applied: ") + !effectiveBackground->get_EffectFormat()->get_IsNoEffects());
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IBackgroundEffectiveData](../../ibackgroundeffectivedata/)
* کلاس [Background](../)
* فضای‌نام [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)