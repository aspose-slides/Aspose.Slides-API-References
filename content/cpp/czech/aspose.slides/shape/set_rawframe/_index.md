---
title: set_RawFrame()
second_title: Aspose.Slides pro C++ API referenci
description: Nastavuje vlastnosti surového rámce tvaru. Zapište IShapeFrame.
type: docs
weight: 53
url: /cs/aspose.slides/shape/set_rawframe/
---
## Shape::set_RawFrame(System::SharedPtr\<IShapeFrame\>) metoda

Nastavuje vlastnosti surového rámce tvaru. Zapište [IShapeFrame](../../ishapeframe/).

```cpp
void Aspose::Slides::Shape::set_RawFrame(System::SharedPtr<IShapeFrame> value) override
```

## Poznámky

Kód, který se pokouší přiřadit nedefinovaný rámec do [IShape::set_Frame](../../ishape/set_frame/), nedává smysl v obecném případě (zejména v případě, když je nadřazený [GroupShape](../../groupshape/) více vnořen do jiných GroupShape-s). Například: 
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
 Takový kód může vést k nejasným situacím. Proto byla přidána omezení pro používání nedefinovaných hodnot pro [IShape::set_Frame](../../ishape/set_frame/). Hodnoty x, y, width, height, flipH, flipV a rotationAngle musí být definovány (ne std::numeric_limits<float>::quiet_NaN() nebo [NullableBool::NotDefined](../../nullablebool/)). Ukázkový kód výše nyní vyvolá výjimku ArgumentException. Toto se vztahuje na následující případy použití: 
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

Ale rámec pro [IShape::set_RawFrame](../../ishape/set_rawframe/) metodu může být nedefinovaný. To dává smysl, když je tvar propojen s placeholderem. Pak jsou nedefinované hodnoty rámce tvaru přepsány hodnotami z nadřazeného placeholderu. Pokud pro tento tvar neexistuje nadřazený placeholder, tvar použije výchozí hodnoty při výpočtu efektivního rámce na základě jeho [IShape::get_RawFrame](../../ishape/get_rawframe/). Výchozí hodnoty jsou 0 a [NullableBool::False](../../nullablebool/) pro x, y, width, height, flipH, flipV a rotationAngle. Například: 
```cpp
SharedPtr<IShape> shape = ...; // shape je propojen s placeholderem
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // nyní shape dědí hodnoty x, y, height, flipH, flipV z placeholderu a přepisuje width=100 a rotationAngle=0.
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IShapeFrame](../../ishapeframe/)
* Třída [Shape](../)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)