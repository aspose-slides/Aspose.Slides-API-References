---
title: GetCredential()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve credenciales para el prefijo URI especificado y el tipo de autenticación.
type: docs
weight: 66
url: /es/system.net/credentialcache/getcredential/
---
## CredentialCache::GetCredential(System::SharedPtr\<Uri\>, String) método


Devuelve credenciales para el prefijo URI especificado y el tipo de autenticación.

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(System::SharedPtr<Uri> uriPrefix, String authenticationType) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | El prefijo URI. |
| authenticationType | [String](../../../system/string/) | Un tipo de autenticación. |

## CredentialCache::GetCredential(String, int32_t, String) método


Devuelve credenciales para el nombre de host, el puerto y el tipo de autenticación especificados.

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(String host, int32_t port, String authenticationType) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| host | [String](../../../system/string/) | El nombre de host con el que están asociadas las credenciales. |
| port | **int32_t** | El número de puerto. |
| authenticationType | [String](../../../system/string/) | El tipo de autenticación. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [NetworkCredential](../../networkcredential/)
* Clase [Uri](../../../system/uri/)
* Clase [String](../../../system/string/)
* Clase [CredentialCache](../)
* Espacio de nombres [System::Net](../../)
* Biblioteca [Aspose.Slides](../../../)