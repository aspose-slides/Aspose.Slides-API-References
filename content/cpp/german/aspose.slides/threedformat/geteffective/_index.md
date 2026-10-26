---
title: GetEffective()
second_title: Aspose.Slides für C++ API-Referenz
description: Ermittelt wirksame 3-D-Formatierungsdaten mit angewandter Vererbung.
type: docs
weight: 183
url: /de/aspose.slides/threedformat/geteffective/
---
## ThreeDFormat::GetEffective() Methode

Ermittelt die wirksamen 3-D-Formatierungsdaten mit angewandter Vererbung.

```cpp
System::SharedPtr<IThreeDFormatEffectiveData> Aspose::Slides::ThreeDFormat::GetEffective() override
```

### Rückgabewert

Ein [IThreeDFormatEffectiveData](../../ithreedformateffectivedata/).

## Bemerkungen

Dieses Beispiel zeigt, wie man wirksame Eigenschaften für die Kamera, das Licht-Rig und die obere Abschrägung der Form erhält. 
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

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IThreeDFormatEffectiveData](../../ithreedformateffectivedata/)
* Klasse [ThreeDFormat](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)