---
title: GetCredential()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve credenciales para la URI especificada y el tipo de autenticación.
type: docs
weight: 1
url: /es/system.net/icredentials/getcredential/
---
## ICredentials::GetCredential(System::SharedPtr\<Uri\>, String) método


Devuelve credenciales para la URI especificada y el tipo de autenticación.

```cpp
virtual System::SharedPtr<NetworkCredential> System::Net::ICredentials::GetCredential(System::SharedPtr<Uri> uri, String authType)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | La URI para la que el cliente proporciona el tipo de autenticación. |
| authType | [String](../../../system/string/) | El tipo de autenticación. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [NetworkCredential](../../networkcredential/)
* Clase [Uri](../../../system/uri/)
* Clase [String](../../../system/string/)
* Clase [ICredentials](../)
* Espacio de nombres [System::Net](../../)
* Biblioteca [Aspose.Slides](../../../)