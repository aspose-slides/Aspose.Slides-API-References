---
title: get_RawFrame()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de eigenschappen van het ruwe vormframe. Lees IShapeFrame.
type: docs
weight: 40
url: /nl/aspose.slides/ishape/get_rawframe/
---
## IShape::get_RawFrame() methode


Retourneert de eigenschappen van het ruwe vormframe. Lees [IShapeFrame](../../ishapeframe/).

```cpp
virtual System::SharedPtr<IShapeFrame> Aspose::Slides::IShape::get_RawFrame()=0
```

## Opmerkingen


Code die probeert een niet-gedefinieerd frame toe te wijzen aan [IShape::set_Frame](../set_frame/) heeft geen zin in het algemeen geval (met name in het geval dat de bovenliggende [GroupShape](../../groupshape/) meerdere keren genest is in andere GroupShape-s). Bijvoorbeeld: 
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
 Zulke code kan tot onduidelijke situaties leiden. Daarom zijn er beperkingen toegevoegd voor het gebruik van niet-gedefinieerde waarden voor [IShape::set_Frame](../set_frame/). Waarden van x, y, width, height, flipH, flipV en rotationAngle moeten gedefinieerd zijn (niet std::numeric_limits<float>::quiet_NaN() of [NullableBool::NotDefined](../../nullablebool/)). Voorbeeldcode hierboven werpt nu een ArgumentException. Dit is van toepassing op deze gebruikssituaties: 
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(...); // kan niet ongedefinieerd zijn

SharedPtr<IShapeCollection> shapes = ...;
// x, y, width, height parameters mogen niet std::numeric_limits<float>::quiet_NaN() zijn:
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


Maar een frame voor [IShape::set_RawFrame](../set_rawframe/) methode kan ongedefinieerd zijn. Dit is logisch wanneer een vorm is gekoppeld aan een placeholder. Dan worden de niet-gedefinieerde vormframewaarden overschreven door de bovenliggende placeholder-vorm. Als er geen bovenliggende placeholder-vorm voor die vorm is, dan gebruikt die vorm standaardwaarden bij het evalueren van het effectieve frame op basis van zijn [IShape::get_RawFrame](./). Standaardwaarden zijn 0 en [NullableBool::False](../../nullablebool/) voor x, y, width, height, flipH, flipV en rotationAngle. Bijvoorbeeld: 
```cpp
SharedPtr<IShape> shape = ...; // shape is gekoppeld aan placeholder
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // nu shape erft x, y, height, flipH, flipV waarden van placeholder en overschrijft width=100 en rotationAngle=0.
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IShapeFrame](../../ishapeframe/)
* Klasse [IShape](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)