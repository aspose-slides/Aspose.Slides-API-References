---
title: GetCredential()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací přihlašovací údaje pro zadané URI a typ autentizace.
type: docs
weight: 92
url: /cs/system.net/networkcredential/getcredential/
---
## NetworkCredential::GetCredential(System::SharedPtr\<Uri\>, String) method

Vrací přihlašovací údaje pro zadané URI a typ autentizace.

```cpp
System::SharedPtr<NetworkCredential> System::Net::NetworkCredential::GetCredential(System::SharedPtr<Uri> uri, String authenticationType) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI. |
| authenticationType | [String](../../../system/string/) | Typ autentizace. |

## NetworkCredential::GetCredential(String, int32_t, String) method

Vrací přihlašovací údaje pro zadaný název hostitele, port a typ autentizace.

```cpp
System::SharedPtr<NetworkCredential> System::Net::NetworkCredential::GetCredential(String host, int32_t port, String authenticationType) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| host | [String](../../../system/string/) | Název hostitele. |
| port | **int32_t** | Číslo portu. |
| authenticationType | [String](../../../system/string/) | Typ autentizace. |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [NetworkCredential](../)
* Třída [Uri](../../../system/uri/)
* Třída [String](../../../system/string/)
* Jmenný prostor [System::Net](../../)
* Library [Aspose.Slides](../../../)