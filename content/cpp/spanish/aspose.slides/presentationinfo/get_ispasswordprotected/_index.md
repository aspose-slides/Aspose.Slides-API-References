---
title: get_IsPasswordProtected()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene un valor que indica si una presentación vinculada está protegida por una contraseña para abrirse.
type: docs
weight: 14
url: /es/aspose.slides/presentationinfo/get_ispasswordprotected/
---
## PresentationInfo::get_IsPasswordProtected() método


Obtiene un valor que indica si una presentación vinculada está protegida por una contraseña para abrirse.

```cpp
bool Aspose::Slides::PresentationInfo::get_IsPasswordProtected() override
```

## Observaciones



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is protected by password to open.");
}
```

## Ver también

* Clase [PresentationInfo](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)