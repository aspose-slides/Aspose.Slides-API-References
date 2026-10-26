---
title: GetCredential()
second_title: Aspose.Slides C++ API referencia
description: Visszaadja a megadott URI-hez és hitelesítési típushoz tartozó hitelesítő adatokat.
type: docs
weight: 1
url: /hu/system.net/icredentials/getcredential/
---
## ICredentials::GetCredential(System::SharedPtr\<Uri\>, String) metódus

Visszaadja a megadott URI-hez és hitelesítési típushoz tartozó hitelesítő adatokat.

```cpp
virtual System::SharedPtr<NetworkCredential> System::Net::ICredentials::GetCredential(System::SharedPtr<Uri> uri, String authType)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Az a URI, amelyhez a kliens biztosítja a hitelesítési típust. |
| authType | [String](../../../system/string/) | A hitelesítési típus. |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [NetworkCredential](../../networkcredential/)
* Osztály [Uri](../../../system/uri/)
* Osztály [String](../../../system/string/)
* Osztály [ICredentials](../)
* Névterület [System::Net](../../)
* Könyvtár [Aspose.Slides](../../../)