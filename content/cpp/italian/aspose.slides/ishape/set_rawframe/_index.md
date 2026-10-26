---
title: set_RawFrame()
second_title: Aspose.Slides per C++ API Reference
description: Imposta le proprietà del frame grezzo della forma. Scrivi IShapeFrame.
type: docs
weight: 53
url: /it/aspose.slides/ishape/set_rawframe/
---
## IShape::set_RawFrame(System::SharedPtr\<IShapeFrame\>) metodo

Imposta le proprietà del frame grezzo della forma. Scrivi [IShapeFrame](../../ishapeframe/).

```cpp
virtual void Aspose::Slides::IShape::set_RawFrame(System::SharedPtr<IShapeFrame> value)=0
```

## Note

Il codice che tenta di assegnare un frame non definito a [IShape::set_Frame](../set_frame/) non ha senso nel caso generale (in particolare nel caso in cui il genitore [GroupShape](../../groupshape/) sia annidato più volte in altri GroupShape). Per esempio:
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), NullableBool::NotDefined, 
NullableBool::NotDefined, std::numeric_limits<float>::quiet_NaN()));
```
oppure
```cpp
slide->get_Shapes()->AddAutoShape(ShapeType::RoundCornerRectangle,
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN());
```
Un tale codice può portare a situazioni poco chiare. Pertanto sono state aggiunte restrizioni per l'uso di valori non definiti per [IShape::set_Frame](../set_frame/). I valori di x, y, width, height, flipH, flipV e rotationAngle devono essere definiti (non std::numeric_limits<float>::quiet_NaN() o [NullableBool::NotDefined](../../nullablebool/)). Il codice di esempio sopra ora genera un'eccezione ArgumentException. Questo vale per i seguenti casi d'uso:
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(...); // non può essere indefinito

SharedPtr<IShapeCollection> shapes = ...;
// i parametri x, y, width, height non possono essere std::numeric_limits<float>::quiet_NaN():
{
    shapes->AddAudioFrameCD(...);
    shapes->AddAudioFrameEmbedded(...);
    shapes->AddAudioFrameLinked(...);
    shapes->AddAutoShape(...);
    shapes->AddChart(...);
    shapes->AddConnector(...);
    shapes->AddOleObjectFrame(...);
    shapes->AddPictureFrame(...);
    shapes->AddSmartArt(...);
    shapes->AddTable(...);
    shapes->AddVideoFrame(...);
    shapes->InsertAudioFrameEmbedded(...);
    shapes->InsertAudioFrameLinked(...);
    shapes->InsertAutoShape(...);
    shapes->InsertChart(...);
    shapes->InsertConnector(...);
    shapes->InsertOleObjectFrame(...);
    shapes->InsertPictureFrame(...);
    shapes->InsertTable(...);
    shapes->InsertVideoFrame(...);
}
```

Tuttavia un frame per il metodo [IShape::set_RawFrame](./) può essere non definito. Questo ha senso quando la forma è collegata a un segnaposto. In tal caso i valori del frame non definiti della forma vengono sovrascritti dal segnaposto padre. Se non esiste un segnaposto padre per quella forma, la forma utilizza i valori predefiniti quando valuta il frame effettivo in base al suo [IShape::get_RawFrame](../get_rawframe/). I valori predefiniti sono 0 e [NullableBool::False](../../nullablebool/) per x, y, width, height, flipH, flipV e rotationAngle. Per esempio:
```cpp
SharedPtr<IShape> shape = ...; // shape è collegata al segnaposto
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // ora shape eredita i valori x, y, height, flipH, flipV dal segnaposto e sovrascrive width=100 e rotationAngle=0.
```

## Vedi anche

* typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IShapeFrame](../../ishapeframe/)
* Classe [IShape](../)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)