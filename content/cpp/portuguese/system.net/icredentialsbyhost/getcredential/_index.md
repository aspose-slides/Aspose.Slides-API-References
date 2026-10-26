---
title: GetCredential()
second_title: Referência da API Aspose.Slides para C++
description: Retorna credenciais para o host especificado e o tipo de autenticação.
type: docs
weight: 1
url: /pt/system.net/icredentialsbyhost/getcredential/
---
## ICredentialsByHost::GetCredential(String, int32_t, String) método

Retorna credenciais para o host especificado e o tipo de autenticação.

```cpp
virtual System::SharedPtr<NetworkCredential> System::Net::ICredentialsByHost::GetCredential(String host, int32_t port, String authenticationType)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| host | [String](../../../system/string/) | O host que autentica o cliente. |
| port | **int32_t** | O número da porta do host. |
| authenticationType | [String](../../../system/string/) | O tipo de autenticação. |

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [NetworkCredential](../../networkcredential/)
* Classe [String](../../../system/string/)
* Classe [ICredentialsByHost](../)
* Espaço de nomes [System::Net](../../)
* Biblioteca [Aspose.Slides](../../../)