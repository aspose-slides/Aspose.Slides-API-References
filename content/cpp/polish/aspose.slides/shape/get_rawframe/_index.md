---
title: get_RawFrame()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Zwraca właściwości surowej ramki kształtu. Przeczytaj IShapeFrame.
type: docs
weight: 40
url: /pl/aspose.slides/shape/get_rawframe/
---
## Shape::get_RawFrame() method


Zwraca właściwości surowej ramki kształtu. Przeczytaj [IShapeFrame](../../ishapeframe/).

```cpp
System::SharedPtr<IShapeFrame> Aspose::Slides::Shape::get_RawFrame() override
```

## Uwagi


Kod, który próbuje przypisać niezdefiniowaną ramkę do [IShape::set_Frame](../../ishape/set_frame/), nie ma sensu w ogólnym przypadku (szczególnie w sytuacji, gdy rodzic [GroupShape](../../groupshape/) jest wielokrotnie zagnieżdżony w innych GroupShape-s). Na przykład: 
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), NullableBool::NotDefined, 
NullableBool::NotDefined, std::numeric_limits<float>::quiet_NaN()));
```
 lub 
```cpp
slide->get_Shapes()->AddAutoShape(ShapeType::RoundCornerRectangle,
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN());
```
 Taki kod może prowadzić do niejasnych sytuacji. Dlatego dodano ograniczenia dotyczące używania niezdefiniowanych wartości dla [IShape::set_Frame](../../ishape/set_frame/). Wartości x, y, width, height, flipH, flipV i rotationAngle muszą być zdefiniowane (nie std::numeric_limits<float>::quiet_NaN() lub [NullableBool::NotDefined](../../nullablebool/)). Powyższy przykładowy kod teraz zgłasza wyjątek ArgumentException. Obejmuje to następujące przypadki użycia: 
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(...); // nie może być niezdefiniowane

SharedPtr<IShapeCollection> shapes = ...;
// parametry x, y, width, height nie mogą być std::numeric_limits<float>::quiet_NaN():
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


Jednak ramka dla metody [IShape::set_RawFrame](../../ishape/set_rawframe/) może być niezdefiniowana. Ma to sens, gdy kształt jest powiązany z placeholderem. Wtedy niezdefiniowane wartości ramki kształtu są nadpisywane przez ramkę rodzica placeholdera. Jeśli nie ma rodzica placeholdera dla tego kształtu, wtedy kształt używa wartości domyślnych przy obliczaniu efektywnej ramki na podstawie jego [IShape::get_RawFrame](../../ishape/get_rawframe/). Domyślne wartości to 0 oraz [NullableBool::False](../../nullablebool/) dla x, y, width, height, flipH, flipV i rotationAngle. Na przykład: 
```cpp
SharedPtr<IShape> shape = ...; // shape jest powiązany z placeholderem
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // teraz shape dziedziczy wartości x, y, height, flipH, flipV z placeholdera i nadpisuje width=100 oraz rotationAngle=0.
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IShapeFrame](../../ishapeframe/)
* Klasa [Shape](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)