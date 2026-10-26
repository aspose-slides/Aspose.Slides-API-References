---
title: get_RawFrame()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce le proprietà del frame grezzo della forma. Leggi IShapeFrame.
type: docs
weight: 40
url: /it/aspose.slides/ishape/get_rawframe/
---
## IShape::get_RawFrame() metodo

Restituisce le proprietà del frame grezzo della forma. Leggi [IShapeFrame](../../ishapeframe/).

```cpp
virtual System::SharedPtr<IShapeFrame> Aspose::Slides::IShape::get_RawFrame()=0
```

## Note

Il codice che tenta di assegnare un frame non definito a [IShape::set_Frame](../set_frame/) non ha senso nel caso generale (in particolare quando il genitore [GroupShape](../../groupshape/) è annidato più volte in altri GroupShape). Ad esempio:
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), NullableBool::NotDefined, 
NullableBool::NotDefined, std::numeric_limits<float>::quiet_NaN()));
```
 o 
```cpp
slide->get_Shapes()->AddAutoShape(ShapeType::RoundCornerRectangle,
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN());
```
Tale codice può portare a situazioni poco chiare. Pertanto sono state aggiunte delle restrizioni per l'uso di valori non definiti per [IShape::set_Frame](../set_frame/). I valori di x, y, width, height, flipH, flipV e rotationAngle devono essere definiti (non std::numeric_limits<float>::quiet_NaN() o [NullableBool::NotDefined](../../nullablebool/)). Il codice di esempio sopra ora genera un'eccezione ArgumentException. Questo si applica a questi casi d'uso:
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(...); // non può essere indefinito

SharedPtr<IShapeCollection> shapes = ...;
// I parametri x, y, width, height non possono essere std::numeric_limits<float>::quiet_NaN():
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

Ma un frame per il metodo [IShape::set_RawFrame](../set_rawframe/) può essere non definito. Questo ha senso quando la forma è collegata a un segnaposto. In tal caso i valori del frame della forma non definiti vengono sovrascritti dal segnaposto forma genitore. Se non esiste un segnaposto forma genitore per quella forma, allora quella forma utilizza i valori predefiniti quando calcola il frame efficace basandosi sul suo [IShape::get_RawFrame](./). I valori predefiniti sono 0 e [NullableBool::False](../../nullablebool/) per x, y, width, height, flipH, flipV e rotationAngle. Ad esempio:
```cpp
SharedPtr<IShape> shape = ...; // shape è collegata al segnaposto
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // ora shape eredita i valori x, y, height, flipH, flipV dal segnaposto e sovrascrive width=100 e rotationAngle=0.
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShapeFrame](../../ishapeframe/)
* Class [IShape](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)