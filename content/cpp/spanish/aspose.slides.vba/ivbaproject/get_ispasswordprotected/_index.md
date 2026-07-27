---
title: get_IsPasswordProtected()
second_title: Aspose.Slides para C++ Referencia de API
description: Indica si el VBAProject está protegido por una contraseña para ver las propiedades del proyecto. Solo lectura bool.
type: docs
weight: 40
url: /es/aspose.slides.vba/ivbaproject/get_ispasswordprotected/
---
## IVbaProject::get_IsPasswordProtected() método

Indica si el VBAProject está protegido por una contraseña para ver las propiedades del proyecto. Solo lectura **bool**.

```cpp
virtual bool Aspose::Slides::Vba::IVbaProject::get_IsPasswordProtected()=0
```

## Observaciones

```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptm");

if (presentation->get_VbaProject()->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The VBAProject '") + presentation->get_VbaProject()->get_Name() + u"' is protected by password to view project properties.");
}
```

## Ver también

* Clase [IVbaProject](../)
* Espacio de nombres [Aspose::Slides::Vba](../../)
* Biblioteca [Aspose.Slides](../../../)