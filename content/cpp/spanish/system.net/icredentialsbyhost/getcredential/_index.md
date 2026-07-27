---
title: GetCredential()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve credenciales para el host especificado y el tipo de autenticación.
type: docs
weight: 1
url: /es/system.net/icredentialsbyhost/getcredential/
---
## ICredentialsByHost::GetCredential(String, int32_t, String) método

Devuelve credenciales para el host especificado y el tipo de autenticación.

```cpp
virtual System::SharedPtr<NetworkCredential> System::Net::ICredentialsByHost::GetCredential(String host, int32_t port, String authenticationType)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| host | [String](../../../system/string/) | El host que autentica al cliente. |
| port | **int32_t** | El número de puerto del host. |
| authenticationType | [String](../../../system/string/) | El tipo de autenticación. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [NetworkCredential](../../networkcredential/)
* Class [String](../../../system/string/)
* Class [ICredentialsByHost](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)