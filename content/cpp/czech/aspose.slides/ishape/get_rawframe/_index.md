---
title: get_RawFrame()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vrací vlastnosti surového rámce tvaru. Přečtěte si IShapeFrame.
type: docs
weight: 40
url: /cs/aspose.slides/ishape/get_rawframe/
---
## IShape::get_RawFrame() metoda


Vrací vlastnosti surového rámce tvaru. Přečtěte si [IShapeFrame](../../ishapeframe/).

```cpp
virtual System::SharedPtr<IShapeFrame> Aspose::Slides::IShape::get_RawFrame()=0
```

## Poznámky


Kód, který se pokouší přiřadit nedefinovaný rámec k [IShape::set_Frame](../set_frame/), nedává v obecné situaci smysl (zejména v případě, kdy je nadřízený [GroupShape](../../groupshape/) víceúrovňově vnořen do dalších GroupShape-s). Například: 
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), NullableBool::NotDefined, 
NullableBool::NotDefined, std::numeric_limits<float>::quiet_NaN()));
```
 nebo 
```cpp
slide->get_Shapes()->AddAutoShape(ShapeType::RoundCornerRectangle,
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN());
```
 Takový kód může vést k nejasným situacím. Proto byla přidána omezení pro používání nedefinovaných hodnot pro [IShape::set_Frame](../set_frame/). Hodnoty x, y, width, height, flipH, flipV a rotationAngle musí být definovány (ne std::numeric_limits<float>::quiet_NaN() nebo [NullableBool::NotDefined](../../nullablebool/)). Ukázkový kód výše nyní vyhazuje výjimku ArgumentException. Toto se vztahuje na následující případy použití: 
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(...); // nemůže být nedefinováno

SharedPtr<IShapeCollection> shapes = ...;
// parametry x, y, width, height nemohou být std::numeric_limits<float>::quiet_NaN():
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


Ale rámec pro [IShape::set_RawFrame](../set_rawframe/) metodu může být nedefinovaný. To má smysl, když je tvar propojen s placeholderem. Pak jsou nedefinované hodnoty rámce tvaru přepsány z nadřazeného placeholder tvaru. Pokud pro tento tvar neexistuje nadřazený placeholder, pak tento tvar použije výchozí hodnoty při výpočtu efektivního rámce na základě jeho [IShape::get_RawFrame](./). Výchozí hodnoty jsou 0 a [NullableBool::False](../../nullablebool/) pro x, y, width, height, flipH, flipV a rotationAngle. Například: 
```cpp
SharedPtr<IShape> shape = ...; // shape je propojen s placeholderem
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // nyní shape dědí hodnoty x, y, height, flipH, flipV z placeholderu a přepíše width=100 a rotationAngle=0.
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IShapeFrame](../../ishapeframe/)
* Třída [IShape](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)