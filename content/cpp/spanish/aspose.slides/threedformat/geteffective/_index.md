---
title: GetEffective()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene los datos de formato 3-D efectivos con la herencia aplicada.
type: docs
weight: 183
url: /es/aspose.slides/threedformat/geteffective/
---
## ThreeDFormat::GetEffective() método

Obtiene los datos de formato 3-D efectivos con la herencia aplicada.

```cpp
System::SharedPtr<IThreeDFormatEffectiveData> Aspose::Slides::ThreeDFormat::GetEffective() override
```

### Valor de retorno

Un [IThreeDFormatEffectiveData](../../ithreedformateffectivedata/).

## Observaciones

Este ejemplo muestra cómo obtener las propiedades efectivas para la cámara, el rig de luz y el bisel superior de la forma.

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

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IThreeDFormatEffectiveData](../../ithreedformateffectivedata/)
* Class [ThreeDFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)