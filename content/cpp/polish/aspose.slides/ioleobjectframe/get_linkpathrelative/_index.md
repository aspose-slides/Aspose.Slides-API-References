---
title: get_LinkPathRelative()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: "Zwraca względną ścieżkę do pliku powiązanego, jeśli istnieje, w przeciwnym razie zwraca pusty ciąg znaków. Tylko do odczytu System::String."
type: docs
weight: 118
url: /pl/aspose.slides/ioleobjectframe/get_linkpathrelative/
---
## IOleObjectFrame::get_LinkPathRelative() metoda


Zwraca względną ścieżkę do pliku powiązanego, jeśli istnieje, w przeciwnym razie zwraca pusty ciąg znaków. Tylko do odczytu [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::IOleObjectFrame::get_LinkPathRelative()=0
```

## Uwagi


W prezentacjach Ppt niektóre łącza obiektów Ole mogą mieć względną reprezentację. 


```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.ppt");

auto oleFrame = System::AsCast<Aspose::Slides::IOleObjectFrame>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));

if (oleFrame != nullptr)
{
    System::Console::WriteLine(System::String(u"The relative path: ") + oleFrame->get_LinkPathRelative());
}
```

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [IOleObjectFrame](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)