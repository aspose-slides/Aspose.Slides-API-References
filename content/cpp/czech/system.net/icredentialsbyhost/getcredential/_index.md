---
title: GetCredential()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vrací pověření pro zadaný host a typ autentizace.
type: docs
weight: 1
url: /cs/system.net/icredentialsbyhost/getcredential/
---
## ICredentialsByHost::GetCredential(String, int32_t, String) metoda

Vrací přihlašovací údaje pro určený host a typ autentizace.

```cpp
virtual System::SharedPtr<NetworkCredential> System::Net::ICredentialsByHost::GetCredential(String host, int32_t port, String authenticationType)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| host | [String](../../../system/string/) | Host, který ověřuje klienta. |
| port | **int32_t** | Číslo portu hosta. |
| authenticationType | [String](../../../system/string/) | Typ autentizace. |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [NetworkCredential](../../networkcredential/)
* Class [String](../../../system/string/)
* Class [ICredentialsByHost](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)