---
title: Add()
second_title: Referencia de API de Aspose.Slides para C++
description: Agrega las credenciales de red especificadas a la caché.
type: docs
weight: 40
url: /es/system.net/credentialcache/add/
---
## CredentialCache::Add(System::SharedPtr\<Uri\>, String, System::SharedPtr\<NetworkCredential\>) método

Agrega las credenciales de red especificadas a la caché.

```cpp
void System::Net::CredentialCache::Add(System::SharedPtr<Uri> uriPrefix, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | El prefijo URI del recurso con el que se asocian las credenciales. |
| authenticationType | [String](../../../system/string/) | El esquema de autenticación. |
| credential | [System::SharedPtr](../../../system/sharedptr/)\<[NetworkCredential](../../networkcredential/)\> | Las credenciales a agregar. |

## CredentialCache::Add(String, int32_t, String, System::SharedPtr\<NetworkCredential\>) método

Agrega las credenciales de red especificadas a la caché.

```cpp
void System::Net::CredentialCache::Add(String host, int32_t port, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| host | [String](../../../system/string/) | El nombre de host con el que se asocian las credenciales. |
| port | **int32_t** | El número de puerto. |
| authenticationType | [String](../../../system/string/) | El esquema de autenticación. |
| credential | [System::SharedPtr](../../../system/sharedptr/)\<[NetworkCredential](../../networkcredential/)\> | Las credenciales a agregar. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Uri](../../../system/uri/)
* Clase [String](../../../system/string/)
* Clase [NetworkCredential](../../networkcredential/)
* Clase [CredentialCache](../)
* Espacio de nombres [System::Net](../../)
* Library [Aspose.Slides](../../../)