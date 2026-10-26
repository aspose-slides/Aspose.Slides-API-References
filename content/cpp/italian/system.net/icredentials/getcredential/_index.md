---
title: GetCredential()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce le credenziali per l'URI specificato e il tipo di autenticazione.
type: docs
weight: 1
url: /it/system.net/icredentials/getcredential/
---
## ICredentials::GetCredential(System::SharedPtr\<Uri\>, String) method


Restituisce le credenziali per l'URI specificato e il tipo di autenticazione.

```cpp
virtual System::SharedPtr<NetworkCredential> System::Net::ICredentials::GetCredential(System::SharedPtr<Uri> uri, String authType)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | L'URI per il quale il client fornisce il tipo di autenticazione. |
| authType | [String](../../../system/string/) | Il tipo di autenticazione. |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [NetworkCredential](../../networkcredential/)
* Classe [Uri](../../../system/uri/)
* Classe [String](../../../system/string/)
* Classe [ICredentials](../)
* Spazio dei nomi [System::Net](../../)
* Library [Aspose.Slides](../../../)