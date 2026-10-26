---
title: get_RawFrame()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de eigenschappen van het ruwe vormframe. Lees IShapeFrame.
type: docs
weight: 40
url: /nl/aspose.slides/shape/get_rawframe/
---
## Shape::get_RawFrame() methode

Retourneert de eigenschappen van het ruwe vormframe. Lees [IShapeFrame](../../ishapeframe/).

```cpp
System::SharedPtr<IShapeFrame> Aspose::Slides::Shape::get_RawFrame() override
```

## Opmerkingen

Code die probeert een niet-gedefinieerd frame toe te wijzen aan [IShape::set_Frame](../../ishape/set_frame/) is in het algemeen geen zinvolle zaak (bijzonder in het geval wanneer de bovenliggende [GroupShape](../../groupshape/) meerdere keren genest is in andere GroupShape-s). Bijvoorbeeld:
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), NullableBool::NotDefined, 
NullableBool::NotDefined, std::numeric_limits<float>::quiet_NaN()));
```
 of
```cpp
slide->get_Shapes()->AddAutoShape(ShapeType::RoundCornerRectangle,
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN());
```
 Zulke code kan leiden tot onduidelijke situaties. Daarom zijn er beperkingen toegevoegd voor het gebruik van ongedefinieerde waarden voor [IShape::set_Frame](../../ishape/set_frame/). Waarden van x, y, width, height, flipH, flipV en rotationAngle moeten gedefinieerd zijn (niet std::numeric_limits<float>::quiet_NaN() of [NullableBool::NotDefined](../../nullablebool/)). De bovenstaande voorbeeldcode werpt nu een ArgumentException. Dit is van toepassing op deze gebruikssituaties:
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(...); // kan niet ongedefinieerd zijn

SharedPtr<IShapeCollection> shapes = ...;
// x, y, breedte, hoogte parameters mogen niet std::numeric_limits<float>::quiet_NaN() zijn:
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

Maar een frame voor de [IShape::set_RawFrame](../../ishape/set_rawframe/) methode kan ongedefinieerd zijn. Dit is logisch wanneer een vorm gekoppeld is aan een placeholder. Dan worden ongedefinieerde shape-frame-waarden overschreven door de bovenliggende placeholder-vorm. Als er geen bovenliggende placeholder-vorm voor die vorm bestaat, dan gebruikt die vorm standaardwaarden bij het evalueren van het effectieve frame op basis van zijn [IShape::get_RawFrame](../../ishape/get_rawframe/). Standaardwaarden zijn 0 en [NullableBool::False](../../nullablebool/) voor x, y, width, height, flipH, flipV en rotationAngle. Bijvoorbeeld:
```cpp
SharedPtr<IShape> shape = ...; // shape is gekoppeld aan placeholder
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // nu shape erft x, y, height, flipH, flipV waarden van placeholder en overschrijft width=100 en rotationAngle=0.
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IShapeFrame](../../ishapeframe/)
* Klasse [Shape](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)