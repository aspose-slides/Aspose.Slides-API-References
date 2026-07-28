---
title: GetEffective()
second_title: Aspose.Slides dla C++ - odniesienie do API
description: Pobiera efektywne dane formatowania 3-D z zastosowanym dziedziczeniem.
type: docs
weight: 183
url: /pl/aspose.slides/threedformat/geteffective/
---
## ThreeDFormat::GetEffective() metoda

Pobiera efektywne dane formatowania 3-D z zastosowanym dziedziczeniem.

```cpp
System::SharedPtr<IThreeDFormatEffectiveData> Aspose::Slides::ThreeDFormat::GetEffective() override
```

### Wartość zwracana

Obiekt [IThreeDFormatEffectiveData](../../ithreedformateffectivedata/).
## Uwagi

Ten przykład pokazuje, jak uzyskać efektywne właściwości kamery, zestawu oświetlenia i górnego fazetu kształtu.
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

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IThreeDFormatEffectiveData](../../ithreedformateffectivedata/)
* Klasa [ThreeDFormat](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)