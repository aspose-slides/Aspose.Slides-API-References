---
title: Remove()
second_title: Aspose.Slides för C++ API-referens
description: Tar bort nätverksuppgifter för den angivna URI-prefixen och autentiseringstypen.
type: docs
weight: 53
url: /sv/system.net/credentialcache/remove/
---
## CredentialCache::Remove(System::SharedPtr\<Uri\>, String) metod

Tar bort nätverksuppgifter för den angivna URI-prefixen och autentiseringstypen.

```cpp
void System::Net::CredentialCache::Remove(System::SharedPtr<Uri> uriPrefix, String authenticationType)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI-prefixen. |
| authenticationType | [String](../../../system/string/) | autentiseringstypen. |

## CredentialCache::Remove(String, int32_t, String) metod

Tar bort nätverksuppgifter för det angivna värdnamnet, porten och autentiseringstypen.

```cpp
void System::Net::CredentialCache::Remove(String host, int32_t port, String authenticationType)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| host | [String](../../../system/string/) | värdnamnet som uppgifterna är kopplade till. |
| port | **int32_t** | portnumret. |
| authenticationType | [String](../../../system/string/) | en autentiseringstyp. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* klass [Uri](../../../system/uri/)
* klass [String](../../../system/string/)
* klass [CredentialCache](../)
* namnrymd [System::Net](../../)
* Library [Aspose.Slides](../../../)