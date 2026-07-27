---
title: CheckWriteProtection()
second_title: Referencia de API de Aspose.Slides para C++
description: Determina si una presentación está protegida con contraseña para modificarla.
type: docs
weight: 157
url: /es/aspose.slides/protectionmanager/checkwriteprotection/
---
## ProtectionManager::CheckWriteProtection(System::String) método

Determina si una presentación está protegida con contraseña para modificarla.

```cpp
bool Aspose::Slides::ProtectionManager::CheckWriteProtection(System::String password) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | La contraseña para la verificación. |

### Valor devuelto

True si la contraseña es válida; de lo contrario, false.

## Observaciones

```cpp
auto presentation = System::MakeObject<Presentation>(presentationFilePath);
bool isWriteProtected = presentation->get_ProtectionManager()->CheckWriteProtection(u"my_password");
```

1. Debe comprobar la propiedad [ProtectionManager::get_IsWriteProtected](../get_iswriteprotected/) antes de llamar a este método.
1. Cuando la contraseña es nula o está vacía, este método devuelve false.

## Ver también

* Clase [String](../../../system/string/)
* Clase [ProtectionManager](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)