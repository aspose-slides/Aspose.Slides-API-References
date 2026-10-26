---
title: GetCredential()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve credenciales para el URI especificado y el tipo de autenticación.
type: docs
weight: 92
url: /es/system.net/networkcredential/getcredential/
---
## NetworkCredential::GetCredential(System::SharedPtr\<Uri\>, String) método


Devuelve credenciales para el URI especificado y el tipo de autenticación.

```cpp
System::SharedPtr<NetworkCredential> System::Net::NetworkCredential::GetCredential(System::SharedPtr<Uri> uri, String authenticationType) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | El URI. |
| authenticationType | [String](../../../system/string/) | El tipo de autenticación. |

## NetworkCredential::GetCredential(String, int32_t, String) método


Devuelve credenciales para el nombre de host, puerto y tipo de autenticación especificados.

```cpp
System::SharedPtr<NetworkCredential> System::Net::NetworkCredential::GetCredential(String host, int32_t port, String authenticationType) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| host | [String](../../../system/string/) | El nombre de host. |
| port | **int32_t** | El número de puerto. |
| authenticationType | [String](../../../system/string/) | El tipo de autenticación. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [NetworkCredential](../)
* Clase [Uri](../../../system/uri/)
* Clase [String](../../../system/string/)
* Espacio de nombres [System::Net](../../)
* Biblioteca [Aspose.Slides](../../../)