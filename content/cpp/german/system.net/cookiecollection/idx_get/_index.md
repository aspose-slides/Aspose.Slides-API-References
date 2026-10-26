---
title: idx_get()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt ein Cookie aus der Cookie-Sammlung am angegebenen Index zurück.
type: docs
weight: 40
url: /de/system.net/cookiecollection/idx_get/
---
## CookieCollection::idx_get(int32_t) Methode

Gibt ein Cookie aus der Cookie-Sammlung am angegebenen Index zurück.

```cpp
System::SharedPtr<Cookie> System::Net::CookieCollection::idx_get(int32_t index)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Der Index eines Cookies, das zurückgegeben werden muss. |

### Rückgabewert

Ein Cookie am angegebenen Index.

## CookieCollection::idx_get(String) Methode

Gibt ein Cookie aus der Cookie-Sammlung mit angegebenem Namen zurück.

```cpp
System::SharedPtr<Cookie> System::Net::CookieCollection::idx_get(String name)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | [String](../../../system/string/) | Der Name eines Cookies, das zurückgegeben werden muss. |

### Rückgabewert

Ein Cookie aus der Cookie-Sammlung mit angegebenem Namen, wenn es gefunden wird, sonst nullptr.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Cookie](../../cookie/)
* Klasse [CookieCollection](../)
* Klasse [String](../../../system/string/)
* Namensraum [System::Net](../../)
* Library [Aspose.Slides](../../../)