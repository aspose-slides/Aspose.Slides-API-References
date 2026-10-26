---
title: GetEffective()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar effektiv 3-D-formateringsdata med arv tillämpat.
type: docs
weight: 183
url: /sv/aspose.slides/threedformat/geteffective/
---
## ThreeDFormat::GetEffective() metod

Hämtar effektiv 3-D-formateringsdata med arv tillämpat.

```cpp
System::SharedPtr<IThreeDFormatEffectiveData> Aspose::Slides::ThreeDFormat::GetEffective() override
```

### Returvärde

Ett [IThreeDFormatEffectiveData](../../ithreedformateffectivedata/).

## Anmärkningar

Detta exempel visar hur man får effektiva egenskaper för kamera, ljusrigg och figurens övre avfasning. 
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

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IThreeDFormatEffectiveData](../../ithreedformateffectivedata/)
* Klass [ThreeDFormat](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)