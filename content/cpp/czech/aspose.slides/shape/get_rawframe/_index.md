---
title: get_RawFrame()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vrací vlastnosti surového rámce tvaru. Přečtěte si IShapeFrame.
type: docs
weight: 40
url: /cs/aspose.slides/shape/get_rawframe/
---
## Shape::get_RawFrame() method

Vrací vlastnosti rámce surového tvaru. Přečtěte si [IShapeFrame](../../ishapeframe/).

```cpp
System::SharedPtr<IShapeFrame> Aspose::Slides::Shape::get_RawFrame() override
```

## Poznámky

Kód, který se pokouší přiřadit nedefinovaný rámec k [IShape::set_Frame](../../ishape/set_frame/), nedává smysl v obecné situaci (zejména v případě, kdy je nadřízený [GroupShape](../../groupshape/) vnořený do více dalších GroupShape). Například:
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
Takový kód může vést k nejasným situacím. Proto byla zavedena omezení pro použití nedefinovaných hodnot pro [IShape::set_Frame](../../ishape/set_frame/). Hodnoty x, y, width, height, flipH, flipV a rotationAngle musí být definovány (nejsou std::numeric_limits<float>::quiet_NaN() ani [NullableBool::NotDefined](../../nullablebool/)). Ukázkový kód výše nyní vyhodí výjimku ArgumentException. Toto platí pro následující případy použití:
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

Avšak rámec pro metodu [IShape::set_RawFrame](../../ishape/set_rawframe/) může být nedefinován. To má smysl, když je tvar propojen s placeholderem. Pak jsou nedefinované hodnoty rámce tvaru přepsány z nadřazeného placeholderu. Pokud pro tento tvar neexistuje nadřazený placeholder, tvar použije výchozí hodnoty při výpočtu efektivního rámce na základě jeho [IShape::get_RawFrame](../../ishape/get_rawframe/). Výchozí hodnoty jsou 0 a [NullableBool::False](../../nullablebool/) pro x, y, width, height, flipH, flipV a rotationAngle. Například:
```cpp
SharedPtr<IShape> shape = ...; // tvar je propojen s placeholderem
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // tvar nyní dědí hodnoty x, y, height, flipH, flipV z placeholderu a přepisuje width=100 a rotationAngle=0.
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IShapeFrame](../../ishapeframe/)
* Třída [Shape](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)