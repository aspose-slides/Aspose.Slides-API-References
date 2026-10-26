---
title: GetCredential()
second_title: Aspose.Slides C++ API referenciája
description: Visszaadja a megadott kiszolgálóhoz és hitelesítési típushoz tartozó hitelesítő adatokat.
type: docs
weight: 1
url: /hu/system.net/icredentialsbyhost/getcredential/
---
## ICredentialsByHost::GetCredential(String, int32_t, String) metódus

Visszaadja a megadott kiszolgálóhoz és hitelesítési típushoz tartozó hitelesítő adatokat.

```cpp
virtual System::SharedPtr<NetworkCredential> System::Net::ICredentialsByHost::GetCredential(String host, int32_t port, String authenticationType)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| host | [String](../../../system/string/) | A kiszolgáló, amely hitelesíti az ügyfelet. |
| port | **int32_t** | A kiszolgáló portszáma. |
| authenticationType | [String](../../../system/string/) | A hitelesítési típus. |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [NetworkCredential](../../networkcredential/)
* Osztály [String](../../../system/string/)
* Osztály [ICredentialsByHost](../)
* Névtér [System::Net](../../)
* Könyvtár [Aspose.Slides](../../../)