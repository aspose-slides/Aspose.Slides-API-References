---
title: get_IsWriteProtected()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene un valor que indica si una presentación vinculada está protegida contra escritura.
type: docs
weight: 27
url: /es/aspose.slides/ipresentationinfo/get_iswriteprotected/
---
## IPresentationInfo::get_IsWriteProtected() método


Obtiene un valor que indica si una presentación vinculada está protegida contra escritura.

```cpp
virtual NullableBool Aspose::Slides::IPresentationInfo::get_IsWriteProtected()=0
```

## Observaciones



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is write protected by a password.");
}
```


Si la presentación está protegida por una contraseña para abrir, el valor de la propiedad es igual a NotDefined. Ver [NullableBool](../../nullablebool/) enumeración.

## Ver también

* Enumeración [NullableBool](../../nullablebool/)
* Clase [IPresentationInfo](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)