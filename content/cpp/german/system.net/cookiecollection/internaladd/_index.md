---
title: InternalAdd()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt das angegebene Cookie zur Sammlung hinzu.
type: docs
weight: 118
url: /de/system.net/cookiecollection/internaladd/
---
## CookieCollection::InternalAdd(System::SharedPtr\<Cookie\>, bool) method

Fügt das angegebene Cookie zur Sammlung hinzu.

```cpp
int32_t System::Net::CookieCollection::InternalAdd(System::SharedPtr<Cookie> cookie, bool isStrict)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | Das hinzuzufügende Cookie. |
| isStrict | **bool** | True, wenn das angegebene Cookie das alte ersetzen muss, sonst false. |

### Rückgabewert

0, wenn das angegebene Cookie das alte ersetzt hat, sonst 1.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Cookie](../../cookie/)
* Klasse [CookieCollection](../)
* Namensraum [System::Net](../../)
* Bibliothek [Aspose.Slides](../../../)