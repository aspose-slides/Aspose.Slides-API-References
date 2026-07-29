---
title: GetCredential()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar autentiseringsuppgifter för den angivna URI:n och autentiseringstypen.
type: docs
weight: 92
url: /sv/system.net/networkcredential/getcredential/
---
## NetworkCredential::GetCredential(System::SharedPtr\<Uri\>, String) method

Returnerar autentiseringsuppgifter för den angivna URI:n och autentiseringstypen.

```cpp
System::SharedPtr<NetworkCredential> System::Net::NetworkCredential::GetCredential(System::SharedPtr<Uri> uri, String authenticationType) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI:n. |
| authenticationType | [String](../../../system/string/) | Autentiseringstypen. |

## NetworkCredential::GetCredential(String, int32_t, String) method

Returnerar autentiseringsuppgifter för det angivna värdnamnet, porten och autentiseringstypen.

```cpp
System::SharedPtr<NetworkCredential> System::Net::NetworkCredential::GetCredential(String host, int32_t port, String authenticationType) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| host | [String](../../../system/string/) | Värdnamnet. |
| port | **int32_t** | Portnumret. |
| authenticationType | [String](../../../system/string/) | Autentiseringstypen. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [NetworkCredential](../)
* Klass [Uri](../../../system/uri/)
* Klass [String](../../../system/string/)
* Namnrymd [System::Net](../../)
* Bibliotek [Aspose.Slides](../../../)