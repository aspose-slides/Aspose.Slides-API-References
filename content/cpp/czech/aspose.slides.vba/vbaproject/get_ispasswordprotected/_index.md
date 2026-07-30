---
title: get_IsPasswordProtected()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Určuje, zda je VBAProject chráněn heslem pro zobrazení vlastností projektu. Pouze ke čtení bool.
type: docs
weight: 40
url: /cs/aspose.slides.vba/vbaproject/get_ispasswordprotected/
---
## VbaProject::get_IsPasswordProtected() metoda

Určuje, zda je VBAProject chráněn heslem pro zobrazení vlastností projektu. Pouze ke čtení **bool**.

```cpp
bool Aspose::Slides::Vba::VbaProject::get_IsPasswordProtected() override
```

## Poznámky



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptm");

if (presentation->get_VbaProject()->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The VBAProject '") + presentation->get_VbaProject()->get_Name() + u"' is protected by password to view project properties.");
}
```

## Viz také

* Třída [VbaProject](../)
* Jmenný prostor [Aspose::Slides::Vba](../../)
* Knihovna [Aspose.Slides](../../../)