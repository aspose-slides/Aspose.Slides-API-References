---
title: idx_get()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een cookie uit de cookie-collectie op de opgegeven index.
type: docs
weight: 40
url: /nl/system.net/cookiecollection/idx_get/
---
## CookieCollection::idx_get(int32_t) methode

Retourneert een cookie uit de cookie-collectie op de opgegeven index.

```cpp
System::SharedPtr<Cookie> System::Net::CookieCollection::idx_get(int32_t index)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | De index van een cookie die moet worden geretourneerd. |

### Retourwaarde

Een cookie op de opgegeven index.

## CookieCollection::idx_get(String) methode

Retourneert een cookie uit de cookie-collectie op basis van de opgegeven naam.

```cpp
System::SharedPtr<Cookie> System::Net::CookieCollection::idx_get(String name)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | [String](../../../system/string/) | De naam van een cookie die moet worden geretourneerd. |

### Retourwaarde

Een cookie uit de cookie-collectie op basis van de opgegeven naam als deze wordt gevonden, anders nullptr.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Cookie](../../cookie/)
* Klasse [CookieCollection](../)
* Klasse [String](../../../system/string/)
* Naamruimte [System::Net](../../)
* Bibliotheek [Aspose.Slides](../../../)