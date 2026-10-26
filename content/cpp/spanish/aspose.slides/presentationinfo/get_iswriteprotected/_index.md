---
title: get_IsWriteProtected()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene un valor que indica si una presentación vinculada está protegida contra escritura.
type: docs
weight: 27
url: /es/aspose.slides/presentationinfo/get_iswriteprotected/
---
## PresentationInfo::get_IsWriteProtected() método


Obtiene un valor que indica si una presentación vinculada está protegida contra escritura.

```cpp
NullableBool Aspose::Slides::PresentationInfo::get_IsWriteProtected() override
```

## Observaciones



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is write protected by a password.");
}
```


Si la presentación está protegida por una contraseña para abrir, el valor de la propiedad es NotDefined. 
## Ver también

* Enumeración [NullableBool](../../nullablebool/)
* Clase [PresentationInfo](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)