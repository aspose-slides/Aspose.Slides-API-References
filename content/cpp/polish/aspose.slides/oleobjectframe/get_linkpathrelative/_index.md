---
title: get_LinkPathRelative()
second_title: Aspose.Slides dla C++ – Referencja API
description: "Zwraca względną ścieżkę do powiązanego pliku, jeśli istnieje, w przeciwnym razie zwraca pusty ciąg znaków. Tylko do odczytu System::String."
type: docs
weight: 131
url: /pl/aspose.slides/oleobjectframe/get_linkpathrelative/
---
## OleObjectFrame::get_LinkPathRelative() metoda

Zwraca względną ścieżkę do powiązanego pliku, jeśli istnieje, w przeciwnym razie zwraca pusty ciąg znaków. Tylko do odczytu [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::OleObjectFrame::get_LinkPathRelative() override
```

## Uwagi

W prezentacjach Ppt niektóre łącza obiektów Ole mogą mieć reprezentację względną.

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
* Klasa [OleObjectFrame](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)