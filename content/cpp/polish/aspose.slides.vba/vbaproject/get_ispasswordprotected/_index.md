---
title: get_IsPasswordProtected()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Wskazuje, czy VBAProject jest chroniony hasłem w celu wyświetlenia właściwości projektu. Tylko do odczytu bool.
type: docs
weight: 40
url: /pl/aspose.slides.vba/vbaproject/get_ispasswordprotected/
---
## VbaProject::get_IsPasswordProtected() metoda


Wskazuje, czy VBAProject jest chroniony hasłem w celu wyświetlenia właściwości projektu. Tylko do odczytu **bool**.

```cpp
bool Aspose::Slides::Vba::VbaProject::get_IsPasswordProtected() override
```

## Uwagi



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptm");

if (presentation->get_VbaProject()->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The VBAProject '") + presentation->get_VbaProject()->get_Name() + u"' is protected by password to view project properties.");
}
```

## Zobacz także

* Klasa [VbaProject](../)
* Przestrzeń nazw [Aspose::Slides::Vba](../../)
* Biblioteka [Aspose.Slides](../../../)