---
title: GetEffective()
second_title: Référence de l'API Aspose.Slides for C++
description: Obtient les données de mise en forme 3-D effectives avec l'héritage appliqué.
type: docs
weight: 183
url: /fr/aspose.slides/threedformat/geteffective/
---
## ThreeDFormat::GetEffective() méthode


Obtient les données de mise en forme 3-D effectives avec l'héritage appliqué.

```cpp
System::SharedPtr<IThreeDFormatEffectiveData> Aspose::Slides::ThreeDFormat::GetEffective() override
```


### Valeur de retour

Un [IThreeDFormatEffectiveData](../../ithreedformateffectivedata/).
## Remarques



Cet exemple montre comment obtenir les propriétés effectives pour la caméra, le dispositif d'éclairage et le biseau supérieur de la forme. 
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

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IThreeDFormatEffectiveData](../../ithreedformateffectivedata/)
* Classe [ThreeDFormat](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)