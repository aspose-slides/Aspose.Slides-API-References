---
title: GetCredential()
second_title: Referência da API Aspose.Slides para C++
description: Retorna credenciais para o prefixo URI especificado e o tipo de autenticação.
type: docs
weight: 66
url: /pt/system.net/credentialcache/getcredential/
---
## CredentialCache::GetCredential(System::SharedPtr\<Uri\>, String) método

Retorna credenciais para o prefixo URI especificado e o tipo de autenticação.

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(System::SharedPtr<Uri> uriPrefix, String authenticationType) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | O prefixo URI. |
| authenticationType | [String](../../../system/string/) | Um tipo de autenticação. |

## CredentialCache::GetCredential(String, int32_t, String) método

Retorna credenciais para o nome do host, porta e tipo de autenticação especificados.

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(String host, int32_t port, String authenticationType) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| host | [String](../../../system/string/) | O nome do host ao qual as credenciais estão associadas. |
| port | **int32_t** | O número da porta. |
| authenticationType | [String](../../../system/string/) | O tipo de autenticação. |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [NetworkCredential](../../networkcredential/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [CredentialCache](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)