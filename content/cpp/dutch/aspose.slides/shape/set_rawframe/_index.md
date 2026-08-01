---
title: set_RawFrame()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt de eigenschappen van het ruwe vormframe in. Schrijf IShapeFrame.
type: docs
weight: 53
url: /nl/aspose.slides/shape/set_rawframe/
---
## Shape::set_RawFrame(System::SharedPtr\<IShapeFrame\>) methode


Stelt de eigenschappen van het ruwe vormframe in. Schrijf [IShapeFrame](../../ishapeframe/).

```cpp
void Aspose::Slides::Shape::set_RawFrame(System::SharedPtr<IShapeFrame> value) override
```

## Opmerkingen


Code die probeert een ongedefinieerd frame toe te wijzen aan [IShape::set_Frame](../../ishape/set_frame/) heeft geen zin in het algemene geval (met name wanneer de ouder [GroupShape](../../groupshape/) meerdere keren genesteld is in andere GroupShape-s). Bijvoorbeeld: 
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
 Dergelijke code kan leiden tot onduidelijke situaties. Er zijn dus beperkingen toegevoegd voor het gebruik van ongedefinieerde waarden voor [IShape::set_Frame](../../ishape/set_frame/). Waarden van x, y, width, height, flipH, flipV en rotationAngle moeten gedefinieerd zijn (niet std::numeric_limits<float>::quiet_NaN() of [NullableBool::NotDefined](../../nullablebool/)). Voorbeeldcode hierboven werpt nu een ArgumentException-uitzondering. Dit is van toepassing op deze gebruikssituaties: 
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(...); // mag niet ongedefinieerd zijn

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


Maar een frame voor [IShape::set_RawFrame](../../ishape/set_rawframe/) methode kan ongedefinieerd zijn. Dit is logisch wanneer een vorm gekoppeld is aan een plaatshouder. Daarna worden ongedefinieerde vormframewaarden overschreven door de bovenliggende plaatshoudervorm. Als er geen bovenliggende plaatshoudervorm is voor die vorm, dan gebruikt die vorm standaardwaarden bij het evalueren van het effectieve frame op basis van zijn [IShape::get_RawFrame](../../ishape/get_rawframe/). Standaardwaarden zijn 0 en [NullableBool::False](../../nullablebool/) voor x, y, width, height, flipH, flipV en rotationAngle. Bijvoorbeeld: 
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
* Bibliotheek [Aspose.Slides](../../../)