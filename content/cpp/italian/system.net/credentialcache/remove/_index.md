---
title: Remove()
second_title: Riferimento API di Aspose.Slides per C++
description: Rimuove le credenziali di rete per il prefisso URI e il tipo di autenticazione specificati.
type: docs
weight: 53
url: /it/system.net/credentialcache/remove/
---
## CredentialCache::Remove(System::SharedPtr\<Uri\>, String) metodo

Rimuove le credenziali di rete per il prefisso URI e il tipo di autenticazione specificati.

```cpp
void System::Net::CredentialCache::Remove(System::SharedPtr<Uri> uriPrefix, String authenticationType)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Il prefisso URI. |
| authenticationType | [String](../../../system/string/) | Il tipo di autenticazione. |

## CredentialCache::Remove(String, int32_t, String) metodo

Rimuove le credenziali di rete per il nome host, la porta e il tipo di autenticazione specificati.

```cpp
void System::Net::CredentialCache::Remove(String host, int32_t port, String authenticationType)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| host | [String](../../../system/string/) | Il nome host a cui sono associate le credenziali. |
| port | **int32_t** | Il numero di porta. |
| authenticationType | [String](../../../system/string/) | Un tipo di autenticazione. |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Uri](../../../system/uri/)
* Classe [String](../../../system/string/)
* Classe [CredentialCache](../)
* Spazio dei nomi [System::Net](../../)
* Libreria [Aspose.Slides](../../../)