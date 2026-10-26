---
title: get_IsPasswordProtected()
second_title: Aspose.Slides C++ API referencia
description: Jelzi, hogy a VBAProject jelszóval védett-e a projekt tulajdonságainak megtekintéséhez. Csak olvasható bool.
type: docs
weight: 40
url: /hu/aspose.slides.vba/ivbaproject/get_ispasswordprotected/
---
## IVbaProject::get_IsPasswordProtected() metódus


Jelzi, hogy a VBAProject jelszóval védett-e a projekt tulajdonságainak megtekintéséhez. Csak olvasható **bool**.

```cpp
virtual bool Aspose::Slides::Vba::IVbaProject::get_IsPasswordProtected()=0
```

## Megjegyzések



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptm");

if (presentation->get_VbaProject()->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The VBAProject '") + presentation->get_VbaProject()->get_Name() + u"' is protected by password to view project properties.");
}
```

## Lásd még

* Osztály [IVbaProject](../)
* Névtér [Aspose::Slides::Vba](../../)
* Könyvtár [Aspose.Slides](../../../)