---
title: GetEffective()
second_title: Aspose.Slides voor C++ API Referentie
description: Haalt effectieve 3-D-opmaakgegevens op met de overerving toegepast.
type: docs
weight: 183
url: /nl/aspose.slides/threedformat/geteffective/
---
## ThreeDFormat::GetEffective() methode

Haalt effectieve 3-D-opmaakgegevens op met de overerving toegepast.

```cpp
System::SharedPtr<IThreeDFormatEffectiveData> Aspose::Slides::ThreeDFormat::GetEffective() override
```

### Retourwaarde

Een [IThreeDFormatEffectiveData](../../ithreedformateffectivedata/).

## Opmerkingen

Dit voorbeeld demonstreert hoe u effectieve eigenschappen kunt ophalen voor de camera, het lichtrig en de bovenste afschuining van de vorm. 
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

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IThreeDFormatEffectiveData](../../ithreedformateffectivedata/)
* Klasse [ThreeDFormat](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)