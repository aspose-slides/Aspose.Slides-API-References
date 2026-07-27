---
title: Remove()
second_title: Referencia de API de Aspose.Slides para C++
description: Elimina las credenciales de red para el prefijo URI especificado y el tipo de autenticación.
type: docs
weight: 53
url: /es/system.net/credentialcache/remove/
---
## CredentialCache::Remove(System::SharedPtr\<Uri\>, String) método


Elimina las credenciales de red para el prefijo URI especificado y el tipo de autenticación.

```cpp
void System::Net::CredentialCache::Remove(System::SharedPtr<Uri> uriPrefix, String authenticationType)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | El prefijo URI. |
| authenticationType | [String](../../../system/string/) | El tipo de autenticación. |

## CredentialCache::Remove(String, int32_t, String) método


Elimina las credenciales de red para el nombre de host, el puerto y el tipo de autenticación especificados.

```cpp
void System::Net::CredentialCache::Remove(String host, int32_t port, String authenticationType)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| host | [String](../../../system/string/) | El nombre de host con el que están asociadas las credenciales. |
| port | **int32_t** | El número de puerto. |
| authenticationType | [String](../../../system/string/) | Un tipo de autenticación. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Uri](../../../system/uri/)
* Clase [String](../../../system/string/)
* Clase [CredentialCache](../)
* Espacio de nombres [System::Net](../../)
* Biblioteca [Aspose.Slides](../../../)