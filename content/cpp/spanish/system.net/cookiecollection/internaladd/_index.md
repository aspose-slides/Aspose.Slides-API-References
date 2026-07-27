---
title: InternalAdd()
second_title: Referencia de la API de Aspose.Slides para C++
description: Agrega la cookie especificada a la colección.
type: docs
weight: 118
url: /es/system.net/cookiecollection/internaladd/
---
## CookieCollection::InternalAdd(System::SharedPtr\<Cookie\>, bool) método


Agrega la cookie especificada a la colección.

```cpp
int32_t System::Net::CookieCollection::InternalAdd(System::SharedPtr<Cookie> cookie, bool isStrict)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | La cookie a agregar. |
| isStrict | **bool** | True cuando la cookie especificada debe reemplazar a la anterior, de lo contrario false. |

### Valor devuelto

0 cuando la cookie especificada reemplazó a la anterior, de lo contrario 1.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Cookie](../../cookie/)
* Clase [CookieCollection](../)
* Espacio de nombres [System::Net](../../)
* Biblioteca [Aspose.Slides](../../../)