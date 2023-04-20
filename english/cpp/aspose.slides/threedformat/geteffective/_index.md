---
title: GetEffective()
second_title: Aspose.Slides for C++ API Reference
description: Gets effective 3-D formatting data with the inheritance applied.
type: docs
weight: 183
url: /cpp/aspose.slides/threedformat/geteffective/
---
## ThreeDFormat::GetEffective() method


Gets effective 3-D formatting data with the inheritance applied.

```cpp
System::SharedPtr<IThreeDFormatEffectiveData> Aspose::Slides::ThreeDFormat::GetEffective() override
```


### Return Value

A [IThreeDFormatEffectiveData](../../ithreedformateffectivedata/).
## Remarks



This example demonstrates how to get effective properties for camera, light rig and shape's top bevel. 
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

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IThreeDFormatEffectiveData](../../ithreedformateffectivedata/)
* Class [ThreeDFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)