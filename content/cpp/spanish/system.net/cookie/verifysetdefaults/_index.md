---
title: VerifySetDefaults()
second_title: Referencia de API de Aspose.Slides para C++
description: Verifica y establece los valores por defecto del atributo.
type: docs
weight: 482
url: /es/system.net/cookie/verifysetdefaults/
---
## Cookie::VerifySetDefaults(CookieVariant, System::SharedPtr\<Uri\>, bool, String, bool, bool) método

Verifica y establece los valores por defecto del atributo.

```cpp
bool System::Net::Cookie::VerifySetDefaults(CookieVariant variant, System::SharedPtr<Uri> uri, bool isLocalDomain, String localDomain, bool setDefault, bool shouldThrow)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| variant | [CookieVariant](../../cookievariant/) | La especificación de la cookie. |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | La instancia de la clase Uri que se usa para inicializar los campos internos. |
| isLocalDomain | **bool** | Un valor que indica si la cookie se inserta en el dominio local. |
| localDomain | [String](../../../system/string/) | Un nombre de dominio local. |
| setDefault | **bool** | Un valor que indica si los atributos de la cookie deben inicializarse usando sus valores por defecto. |
| shouldThrow | **bool** | Un valor que indica si se debe lanzar una excepción cuando los valores especificados son inválidos. |

### Valor devuelto

True cuando todos los valores son válidos, de lo contrario false.

## Véase también

* Enumeración [CookieVariant](../../cookievariant/)
* Definición de tipo [SharedPtr](../../../system/sharedptr/)
* Clase [Uri](../../../system/uri/)
* Clase [String](../../../system/string/)
* Clase [Cookie](../)
* Espacio de nombres [System::Net](../../)
* Biblioteca [Aspose.Slides](../../../)