---
title: set_RawFrame()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Nastaví vlastnosti raw shape frame. Zapište IShapeFrame.
type: docs
weight: 53
url: /cs/aspose.slides/ishape/set_rawframe/
---
## IShape::set_RawFrame(System::SharedPtr\<IShapeFrame\>) metoda

Nastaví vlastnosti raw shape frame. Zapište [IShapeFrame](../../ishapeframe/).

```cpp
virtual void Aspose::Slides::IShape::set_RawFrame(System::SharedPtr<IShapeFrame> value)=0
```

## Poznámky

Kód, který se snaží přiřadit nedefinovaný rámec k [IShape::set_Frame](../set_frame/), nedává v obecném případě smysl (zejména v případě, kdy je nadřazený [GroupShape](../../groupshape/) více vnořen do dalších GroupShape-s). Například:
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
 Takový kód může vést k nejasným situacím. Proto byly přidány omezení pro používání nedefinovaných hodnot pro [IShape::set_Frame](../set_frame/). Hodnoty x, y, width, height, flipH, flipV a rotationAngle musí být definovány (nejsou std::numeric_limits<float>::quiet_NaN() nebo [NullableBool::NotDefined](../../nullablebool/)). Výše uvedený příklad kódu nyní vyvolává výjimku ArgumentException. Toto se vztahuje na následující případy použití:
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

Ale rámec pro metodu [IShape::set_RawFrame](./) může být nedefinovaný. To má smysl, když je tvar propojen s placeholderem. Pak jsou nedefinované hodnoty rámce tvaru přepsány ze nadřazeného placeholderu. Pokud pro daný tvar neexistuje nadřazený placeholder, tvar použije výchozí hodnoty při výpočtu efektivního rámce na základě jeho [IShape::get_RawFrame](../get_rawframe/). Výchozí hodnoty jsou 0 a [NullableBool::False](../../nullablebool/) pro x, y, width, height, flipH, flipV a rotationAngle. Například:
```cpp
SharedPtr<IShape> shape = ...; // shape je propojen s placeholderem
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // nyní shape dědí hodnoty x, y, height, flipH, flipV z placeholderu a přepisuje width=100 a rotationAngle=0.
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IShapeFrame](../../ishapeframe/)
* Třída [IShape](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)