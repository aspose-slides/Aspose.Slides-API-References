---
title: GetCredential()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce le credenziali per il prefisso URI specificato e il tipo di autenticazione.
type: docs
weight: 66
url: /it/system.net/credentialcache/getcredential/
---
## CredentialCache::GetCredential(System::SharedPtr\<Uri\>, String) method

Restituisce le credenziali per il prefisso URI specificato e il tipo di autenticazione.

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(System::SharedPtr<Uri> uriPrefix, String authenticationType) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Il prefisso URI. |
| authenticationType | [String](../../../system/string/) | Un tipo di autenticazione. |

## CredentialCache::GetCredential(String, int32_t, String) method

Restituisce le credenziali per il nome host, la porta e il tipo di autenticazione specificati.

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(String host, int32_t port, String authenticationType) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| host | [String](../../../system/string/) | Il nome host associato alle credenziali. |
| port | **int32_t** | Il numero di porta. |
| authenticationType | [String](../../../system/string/) | Il tipo di autenticazione. |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [NetworkCredential](../../networkcredential/)
* Classe [Uri](../../../system/uri/)
* Classe [String](../../../system/string/)
* Classe [CredentialCache](../)
* Spazio dei nomi [System::Net](../../)
* Library [Aspose.Slides](../../../)