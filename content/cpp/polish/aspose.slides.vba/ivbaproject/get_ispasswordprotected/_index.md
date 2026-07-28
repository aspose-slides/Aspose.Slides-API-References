---
title: get_IsPasswordProtected()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Określa, czy VBAProject jest chroniony hasłem w celu podglądu właściwości projektu. Tylko do odczytu bool.
type: docs
weight: 40
url: /pl/aspose.slides.vba/ivbaproject/get_ispasswordprotected/
---
## IVbaProject::get_IsPasswordProtected() metoda


Określa, czy VBAProject jest chroniony hasłem w celu podglądu właściwości projektu. Tylko do odczytu **bool**.

```cpp
virtual bool Aspose::Slides::Vba::IVbaProject::get_IsPasswordProtected()=0
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

* Klasa [IVbaProject](../)
* Przestrzeń nazw [Aspose::Slides::Vba](../../)
* Biblioteka [Aspose.Slides](../../../)