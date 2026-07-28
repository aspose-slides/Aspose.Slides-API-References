---
title: get_IsPasswordProtected()
second_title: Aspose.Slides for C++ API referencia
description: Azt jelzi, hogy a VBAProject jelszóval védett-e a projekt tulajdonságainak megtekintéséhez. Csak olvasható bool.
type: docs
weight: 40
url: /hu/aspose.slides.vba/vbaproject/get_ispasswordprotected/
---
## VbaProject::get_IsPasswordProtected() metódus

Jelzi, hogy a VBAProject jelszóval védett-e a projekt tulajdonságainak megtekintéséhez. Csak olvasható **bool**.

```cpp
bool Aspose::Slides::Vba::VbaProject::get_IsPasswordProtected() override
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

* Osztály [VbaProject](../)
* Névterület [Aspose::Slides::Vba](../../)
* Könyvtár [Aspose.Slides](../../../)