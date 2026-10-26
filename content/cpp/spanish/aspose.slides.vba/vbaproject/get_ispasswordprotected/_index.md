---
title: get_IsPasswordProtected()
second_title: Referencia de API de Aspose.Slides para C++
description: Indica si el VBAProject está protegido por una contraseña para ver las propiedades del proyecto. Solo lectura bool.
type: docs
weight: 40
url: /es/aspose.slides.vba/vbaproject/get_ispasswordprotected/
---
## VbaProject::get_IsPasswordProtected() método


Indica si el VBAProject está protegido por una contraseña para ver las propiedades del proyecto. Solo lectura **bool**.

```cpp
bool Aspose::Slides::Vba::VbaProject::get_IsPasswordProtected() override
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

* Clase [VbaProject](../)
* Espacio de nombres [Aspose::Slides::Vba](../../)
* Biblioteca [Aspose.Slides](../../../)