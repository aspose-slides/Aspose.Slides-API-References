---
title: idx_get()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve una cookie de la colección de cookies en el índice especificado.
type: docs
weight: 40
url: /es/system.net/cookiecollection/idx_get/
---
## CookieCollection::idx_get(int32_t) método

Devuelve una cookie de la colección de cookies en el índice especificado.

```cpp
System::SharedPtr<Cookie> System::Net::CookieCollection::idx_get(int32_t index)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | El índice de una cookie que debe devolverse. |

### Valor de retorno

Una cookie en el índice especificado.

## CookieCollection::idx_get(String) método

Devuelve una cookie de la colección de cookies por el nombre especificado.

```cpp
System::SharedPtr<Cookie> System::Net::CookieCollection::idx_get(String name)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | El nombre de una cookie que debe devolverse. |

### Valor de retorno

Una cookie de la colección de cookies por el nombre especificado cuando se encuentra, de lo contrario nullptr.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Cookie](../../cookie/)
* Clase [CookieCollection](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [System::Net](../../)
* Library [Aspose.Slides](../../../)