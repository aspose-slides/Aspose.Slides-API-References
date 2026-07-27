---
title: CheckWriteProtection()
second_title: Referencia de API de Aspose.Slides para C++
description: Comprueba si la contraseña para modificar es correcta para una presentación protegida contra escritura.
type: docs
weight: 66
url: /es/aspose.slides/presentationinfo/checkwriteprotection/
---
## PresentationInfo::CheckWriteProtection(System::String) método


Comprueba si la contraseña para modificar es correcta para una presentación protegida contra escritura.

```cpp
bool Aspose::Slides::PresentationInfo::CheckWriteProtection(System::String password) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | La contraseña a comprobar. |

### Valor devuelto

True si la presentación está protegida contra escritura y la contraseña es correcta. False en caso contrario.

## Observaciones



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    bool isWriteProtectedByPassword = info->CheckWriteProtection(u"my_password");
}
```



1. Debe comprobar la propiedad [PresentationInfo::get_IsWriteProtected](../get_iswriteprotected/) antes de llamar a este método.
1. Cuando la contraseña es nula o está vacía, este método devuelve False.



## Ver también

* Clase [String](../../../system/string/)
* Clase [PresentationInfo](../)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)