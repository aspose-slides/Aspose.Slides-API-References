---
title: get_IsPasswordProtected()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene un valor que indica si una presentación vinculada está protegida por una contraseña para abrirla.
type: docs
weight: 14
url: /es/aspose.slides/ipresentationinfo/get_ispasswordprotected/
---
## IPresentationInfo::get_IsPasswordProtected() método


Obtiene un valor que indica si una presentación vinculada está protegida por una contraseña para abrirla.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::get_IsPasswordProtected()=0
```

## Observaciones


```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is protected by a password to open.");
}
```

## Ver también

* Clase [IPresentationInfo](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)