---
title: GetCredential()
second_title: Referência da API Aspose.Slides para C++
description: Retorna credenciais para o URI especificado e o tipo de autenticação.
type: docs
weight: 1
url: /pt/system.net/icredentials/getcredential/
---
## ICredentials::GetCredential(System::SharedPtr\<Uri\>, String) method

Retorna credenciais para o URI especificado e tipo de autenticação.

```cpp
virtual System::SharedPtr<NetworkCredential> System::Net::ICredentials::GetCredential(System::SharedPtr<Uri> uri, String authType)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | O URI para o qual o tipo de autenticação é fornecido por um cliente. |
| authType | [String](../../../system/string/) | O tipo de autenticação. |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [NetworkCredential](../../networkcredential/)
* Classe [Uri](../../../system/uri/)
* Classe [String](../../../system/string/)
* Classe [ICredentials](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)