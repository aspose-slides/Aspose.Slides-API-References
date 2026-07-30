---
title: get_IsPasswordProtected()
second_title: Aspose.Slides pro C++ - referenční dokumentace API
description: Určuje, zda je VBAProject chráněn heslem pro zobrazení vlastností projektu. Pouze pro čtení bool.
type: docs
weight: 40
url: /cs/aspose.slides.vba/ivbaproject/get_ispasswordprotected/
---
## IVbaProject::get_IsPasswordProtected() metoda


Určuje, zda je VBAProject chráněn heslem pro zobrazení vlastností projektu. Pouze pro čtení **bool**.

```cpp
virtual bool Aspose::Slides::Vba::IVbaProject::get_IsPasswordProtected()=0
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

* Třída [IVbaProject](../)
* Jmenný prostor [Aspose::Slides::Vba](../../)
* Knihovna [Aspose.Slides](../../../)