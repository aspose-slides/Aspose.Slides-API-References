---
title: GetEffective()
second_title: Riferimento API Aspose.Slides per C++
description: Ottiene i dati di formattazione 3-D effettivi con l'ereditarietà applicata.
type: docs
weight: 183
url: /it/aspose.slides/threedformat/geteffective/
---
## ThreeDFormat::GetEffective() metodo


Ottiene i dati di formattazione 3-D effettivi con l'ereditarietà applicata.

```cpp
System::SharedPtr<IThreeDFormatEffectiveData> Aspose::Slides::ThreeDFormat::GetEffective() override
```


### Valore di ritorno

Un [IThreeDFormatEffectiveData](../../ithreedformateffectivedata/).
## Osservazioni



Questo esempio dimostra come ottenere le proprietà effettive per la telecamera, il set di luci e il bordo superiore della forma. 
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

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IThreeDFormatEffectiveData](../../ithreedformateffectivedata/)
* Classe [ThreeDFormat](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)