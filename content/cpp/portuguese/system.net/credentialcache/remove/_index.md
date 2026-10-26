---
title: Remove()
second_title: Referência da API Aspose.Slides para C++
description: Remove credenciais de rede para o prefixo de URI especificado e o tipo de autenticação.
type: docs
weight: 53
url: /pt/system.net/credentialcache/remove/
---
## CredentialCache::Remove(System::SharedPtr\<Uri\>, String) método


Remove credenciais de rede para o prefixo de URI especificado e o tipo de autenticação.

```cpp
void System::Net::CredentialCache::Remove(System::SharedPtr<Uri> uriPrefix, String authenticationType)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | O prefixo de URI. |
| authenticationType | [String](../../../system/string/) | O tipo de autenticação. |

## CredentialCache::Remove(String, int32_t, String) método


Remove credenciais de rede para o nome de host, porta e tipo de autenticação especificados.

```cpp
void System::Net::CredentialCache::Remove(String host, int32_t port, String authenticationType)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| host | [String](../../../system/string/) | O nome de host ao qual as credenciais estão associadas. |
| port | **int32_t** | O número da porta. |
| authenticationType | [String](../../../system/string/) | Um tipo de autenticação. |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Uri](../../../system/uri/)
* Classe [String](../../../system/string/)
* Classe [CredentialCache](../)
* Namespace [System::Net](../../)
* Biblioteca [Aspose.Slides](../../../)