---
title: GetCredential()
second_title: Aspose.Slides C++ API hivatkozás
description: Visszaadja a megadott URI-hez és hitelesítési típushoz tartozó hitelesítő adatokat.
type: docs
weight: 92
url: /hu/system.net/networkcredential/getcredential/
---
## NetworkCredential::GetCredential(System::SharedPtr\<Uri\>, String) metódus

A megadott URI-hez és hitelesítési típushoz tartozó hitelesítő adatokat adja vissza.

```cpp
System::SharedPtr<NetworkCredential> System::Net::NetworkCredential::GetCredential(System::SharedPtr<Uri> uri, String authenticationType) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Az URI. |
| authenticationType | [String](../../../system/string/) | A hitelesítési típus. |

## NetworkCredential::GetCredential(String, int32_t, String) metódus

A megadott gépnév, port és hitelesítési típus hitelesítő adatait adja vissza.

```cpp
System::SharedPtr<NetworkCredential> System::Net::NetworkCredential::GetCredential(String host, int32_t port, String authenticationType) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| host | [String](../../../system/string/) | A gépnév. |
| port | **int32_t** | A port száma. |
| authenticationType | [String](../../../system/string/) | A hitelesítési típus. |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [NetworkCredential](../)
* Osztály [Uri](../../../system/uri/)
* Osztály [String](../../../system/string/)
* Névtér [System::Net](../../)
* Könyvtár [Aspose.Slides](../../../)