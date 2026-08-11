---
title: GetEffective()
second_title: Aspose.Slides برای C++ مرجع API
description: داده‌های فرمت‌بندی 3-بعدی مؤثر را با اعمال وراثت دریافت می‌کند.
type: docs
weight: 183
url: /fa/aspose.slides/threedformat/geteffective/
---
## ThreeDFormat::GetEffective() متد

داده‌های فرمت‌بندی 3-بعدی مؤثر را که وراثت اعمال شده است، دریافت می‌کند.

```cpp
System::SharedPtr<IThreeDFormatEffectiveData> Aspose::Slides::ThreeDFormat::GetEffective() override
```

### مقدار بازگشت

یک [IThreeDFormatEffectiveData](../../ithreedformateffectivedata/).

## ملاحظات

این مثال نشان می‌دهد که چگونه ویژگی‌های مؤثر برای دوربین، دستگاه نور و برجستگی بالایی شکل را دریافت کنید.

```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto threeDEffectiveData = pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_ThreeDFormat()->GetEffective();

Console::WriteLine(u"= Effective camera properties =");
Console::WriteLine(String(u"Type: ") + ObjectExt::ToString(threeDEffectiveData->get_Camera()->get_CameraType()));
Console::WriteLine(String(u"Field of view: ") + threeDEffectiveData->get_Camera()->get_FieldOfViewAngle());
Console::WriteLine(String(u"Zoom: ") + threeDEffectiveData->get_Camera()->get_Zoom());

Console::WriteLine(u"= Effective light rig properties =");
Console::WriteLine(String(u"Type: ") + ObjectExt::ToString(threeDEffectiveData->get_LightRig()->get_LightType()));
Console::WriteLine(String(u"Direction: ") + ObjectExt::ToString(threeDEffectiveData->get_LightRig()->get_Direction()));

Console::WriteLine(u"= Effective shape's top face relief properties =");
Console::WriteLine(String(u"Type: ") + ObjectExt::ToString(threeDEffectiveData->get_BevelTop()->get_BevelType()));
Console::WriteLine(String(u"Width: ") + threeDEffectiveData->get_BevelTop()->get_Width());
Console::WriteLine(String(u"Height: ") + threeDEffectiveData->get_BevelTop()->get_Height());
```

## مراجع

* نوع تعریف [SharedPtr](../../../system/sharedptr/)
* کلاس [IThreeDFormatEffectiveData](../../ithreedformateffectivedata/)
* کلاس [ThreeDFormat](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)