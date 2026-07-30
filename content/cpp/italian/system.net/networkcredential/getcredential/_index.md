---
title: GetCredential()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce le credenziali per l'URI specificato e il tipo di autenticazione.
type: docs
weight: 92
url: /it/system.net/networkcredential/getcredential/
---
## NetworkCredential::GetCredential(System::SharedPtr\<Uri\>, String) metodo

Restituisce le credenziali per l'URI specificato e il tipo di autenticazione.

```cpp
System::SharedPtr<NetworkCredential> System::Net::NetworkCredential::GetCredential(System::SharedPtr<Uri> uri, String authenticationType) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | L'URI. |
| authenticationType | [String](../../../system/string/) | Il tipo di autenticazione. |

## NetworkCredential::GetCredential(String, int32_t, String) metodo

Restituisce le credenziali per il nome host specificato, la porta e il tipo di autenticazione.

```cpp
System::SharedPtr<NetworkCredential> System::Net::NetworkCredential::GetCredential(String host, int32_t port, String authenticationType) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| host | [String](../../../system/string/) | Il nome host. |
| port | **int32_t** | Il numero di porta. |
| authenticationType | [String](../../../system/string/) | Il tipo di autenticazione. |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [NetworkCredential](../)
* Classe [Uri](../../../system/uri/)
* Classe [String](../../../system/string/)
* Namespace [System::Net](../../)
* Libreria [Aspose.Slides](../../../)