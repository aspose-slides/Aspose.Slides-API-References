---
title: CheckWriteProtection()
second_title: Referencia de API de Aspose.Slides para C++
description: Comprueba si una contraseña de modificación es correcta para una presentación protegida contra escritura.
type: docs
weight: 66
url: /es/aspose.slides/ipresentationinfo/checkwriteprotection/
---
## IPresentationInfo::CheckWriteProtection(System::String) método


Comprueba si una contraseña de modificación es correcta para una presentación protegida contra escritura.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::CheckWriteProtection(System::String password)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | La contraseña a comprobar. |

### Valor de retorno

True si la presentación está protegida contra escritura y la contraseña es correcta. False de lo contrario.
## Observaciones



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    bool isWriteProtectedByPassword = info->CheckWriteProtection(u"my_password");
}
```



1. Debe comprobar la propiedad [IPresentationInfo::get_IsWriteProtected](../get_iswriteprotected/) antes de llamar a este método.
1. Cuando password es null o está vacío, este método devuelve false.



## Ver también

* Clase [String](../../../system/string/)
* Clase [IPresentationInfo](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)