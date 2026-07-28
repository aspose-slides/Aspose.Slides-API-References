---
title: get_RawFrame()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Zwraca właściwości surowej ramki kształtu. Przeczytaj IShapeFrame.
type: docs
weight: 40
url: /pl/aspose.slides/ishape/get_rawframe/
---
## IShape::get_RawFrame() metoda


Zwraca właściwości surowej ramki kształtu. Przeczytaj [IShapeFrame](../../ishapeframe/).

```cpp
virtual System::SharedPtr<IShapeFrame> Aspose::Slides::IShape::get_RawFrame()=0
```

## Uwagi


Kod, który próbuje przypisać nieokreśloną ramkę do [IShape::set_Frame](../set_frame/), nie ma sensu w ogólnym przypadku (szczególnie w sytuacji, gdy rodzic [GroupShape](../../groupshape/) jest wielokrotnie zagnieżdżony w innych GroupShape-ach). Na przykład: 
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
Taki kod może prowadzić do niejasnych sytuacji. Dlatego wprowadzono ograniczenia dotyczące używania nieokreślonych wartości dla [IShape::set_Frame](../set_frame/). Wartości x, y, width, height, flipH, flipV i rotationAngle muszą być zdefiniowane (nie std::numeric_limits<float>::quiet_NaN() ani [NullableBool::NotDefined](../../nullablebool/)). Powyższy przykładowy kod teraz zgłasza wyjątek ArgumentException. Dotyczy to następujących przypadków użycia: 
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(...); // nie może być nieokreślone

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


Jednak ramka dla metody [IShape::set_RawFrame](../set_rawframe/) może być nieokreślona. Ma to sens, gdy kształt jest powiązany z placeholderem. Następnie nieokreślone wartości ramki kształtu są nadpisywane z rodzicielskiego placeholdera. Jeśli dla tego kształtu nie istnieje rodzicielski placeholder, kształt używa wartości domyślnych przy obliczaniu efektywnej ramki na podstawie swojego [IShape::get_RawFrame](./). Domyślne wartości to 0 oraz [NullableBool::False](../../nullablebool/) dla x, y, width, height, flipH, flipV i rotationAngle. Na przykład: 
```cpp
SharedPtr<IShape> shape = ...; // kształt jest powiązany z placeholderem
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // teraz kształt dziedziczy wartości x, y, height, flipH, flipV z placeholdera i nadpisuje width=100 oraz rotationAngle=0.
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IShapeFrame](../../ishapeframe/)
* Klasa [IShape](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)