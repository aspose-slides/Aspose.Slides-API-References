---
title: CheckPassword()
second_title: Referencia de la API de Aspose.Slides para C++
description: Verifica si una contraseña es correcta para una presentación protegida con contraseña abierta.
type: docs
weight: 53
url: /es/aspose.slides/presentationinfo/checkpassword/
---
## PresentationInfo::CheckPassword(System::String) método

Verifica si una contraseña es correcta para una presentación protegida con contraseña abierta.

```cpp
bool Aspose::Slides::PresentationInfo::CheckPassword(System::String password) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | La contraseña a verificar. |

### Valor de retorno

True si la presentación está protegida con contraseña abierta y la contraseña es correcta y false en caso contrario.

## Observaciones

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
bool isPasswordCorrect = info->CheckPassword(u"my_password");
```

Cuando la contraseña es null o está vacía, este método devuelve false.

## Ver también

* Clase [String](../../../system/string/)
* Clase [PresentationInfo](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)