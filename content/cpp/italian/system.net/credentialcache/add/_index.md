---
title: Add()
second_title: Riferimento API Aspose.Slides per C++
description: Aggiunge le credenziali di rete specificate alla cache.
type: docs
weight: 40
url: /it/system.net/credentialcache/add/
---
## CredentialCache::Add(System::SharedPtr\<Uri\>, String, System::SharedPtr\<NetworkCredential\>) metodo

Aggiunge le credenziali di rete specificate alla cache.

```cpp
void System::Net::CredentialCache::Add(System::SharedPtr<Uri> uriPrefix, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Il prefisso URI della risorsa a cui sono associate le credenziali. |
| authenticationType | [String](../../../system/string/) | Lo schema di autenticazione. |
| credential | [System::SharedPtr](../../../system/sharedptr/)\<[NetworkCredential](../../networkcredential/)\> | Le credenziali da aggiungere. |

## CredentialCache::Add(String, int32_t, String, System::SharedPtr\<NetworkCredential\>) metodo

Aggiunge le credenziali di rete specificate alla cache.

```cpp
void System::Net::CredentialCache::Add(String host, int32_t port, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| host | [String](../../../system/string/) | Il nome host a cui sono associate le credenziali. |
| port | **int32_t** | Il numero di porta. |
| authenticationType | [String](../../../system/string/) | Lo schema di autenticazione. |
| credential | [System::SharedPtr](../../../system/sharedptr/)\<[NetworkCredential](../../networkcredential/)\> | Le credenziali da aggiungere. |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Uri](../../../system/uri/)
* Classe [String](../../../system/string/)
* Classe [NetworkCredential](../../networkcredential/)
* Classe [CredentialCache](../)
* Spazio dei nomi [System::Net](../../)
* Libreria [Aspose.Slides](../../../)