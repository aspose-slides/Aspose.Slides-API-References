---
title: CheckPassword()
second_title: Referencia de API de Aspose.Slides para C++
description: Comprueba si una contraseña es correcta para una presentación protegida con contraseña de apertura.
type: docs
weight: 53
url: /es/aspose.slides/ipresentationinfo/checkpassword/
---
## IPresentationInfo::CheckPassword(System::String) método

Comprueba si una contraseña es correcta para una presentación protegida con contraseña de apertura.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::CheckPassword(System::String password)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | La contraseña a comprobar. |

### Valor de retorno

True si la presentación está protegida con contraseña de apertura y la contraseña es correcta y false en caso contrario.

## Observaciones

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
bool isPasswordCorrect = info->CheckPassword(u"my_password");
```

Cuando la contraseña es null o está vacía, este método devuelve false.

## Véase también

* Clase [String](../../../system/string/)
* Clase [IPresentationInfo](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)