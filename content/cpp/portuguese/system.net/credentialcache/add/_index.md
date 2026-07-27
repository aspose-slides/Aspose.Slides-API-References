---
title: Add()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona as credenciais de rede especificadas ao cache.
type: docs
weight: 40
url: /pt/system.net/credentialcache/add/
---
## CredentialCache::Add(System::SharedPtr\<Uri\>, String, System::SharedPtr\<NetworkCredential\>) método


Adiciona as credenciais de rede especificadas ao cache.

```cpp
void System::Net::CredentialCache::Add(System::SharedPtr<Uri> uriPrefix, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | O prefixo URI do recurso ao qual as credenciais estão associadas. |
| authenticationType | [String](../../../system/string/) | O esquema de autenticação. |
| credential | [System::SharedPtr](../../../system/sharedptr/)\<[NetworkCredential](../../networkcredential/)\> | As credenciais a serem adicionadas. |

## CredentialCache::Add(String, int32_t, String, System::SharedPtr\<NetworkCredential\>) método


Adiciona as credenciais de rede especificadas ao cache.

```cpp
void System::Net::CredentialCache::Add(String host, int32_t port, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| host | [String](../../../system/string/) | O nome do host ao qual as credenciais estão associadas. |
| port | **int32_t** | O número da porta. |
| authenticationType | [String](../../../system/string/) | O esquema de autenticação. |
| credential | [System::SharedPtr](../../../system/sharedptr/)\<[NetworkCredential](../../networkcredential/)\> | As credenciais a serem adicionadas. |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Uri](../../../system/uri/)
* Classe [String](../../../system/string/)
* Classe [NetworkCredential](../../networkcredential/)
* Classe [CredentialCache](../)
* Espaço de nomes [System::Net](../../)
* Library [Aspose.Slides](../../../)