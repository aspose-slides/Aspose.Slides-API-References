---
title: GetEffective()
second_title: Referência da API Aspose.Slides para C++
description: Obtém os dados efetivos de formatação 3-D com a herança aplicada.
type: docs
weight: 183
url: /pt/aspose.slides/threedformat/geteffective/
---
## ThreeDFormat::GetEffective() método

Obtém os dados efetivos de formatação 3-D com a herança aplicada.

```cpp
System::SharedPtr<IThreeDFormatEffectiveData> Aspose::Slides::ThreeDFormat::GetEffective() override
```

### Valor de Retorno

Um [IThreeDFormatEffectiveData](../../ithreedformateffectivedata/).

## Observações

Este exemplo demonstra como obter propriedades efetivas para câmera, rig de iluminação e bisel superior da forma. 
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

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IThreeDFormatEffectiveData](../../ithreedformateffectivedata/)
* Classe [ThreeDFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)