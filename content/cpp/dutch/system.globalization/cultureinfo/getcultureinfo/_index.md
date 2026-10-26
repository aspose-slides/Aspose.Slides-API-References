---
title: GetCultureInfo()
second_title: Aspose.Slides voor C++ API Referentie
description: Haalt de cultuur op op basis van de naam. Hetzelfde als CreateSpecificCulture.
type: docs
weight: 586
url: /nl/system.globalization/cultureinfo/getcultureinfo/
---
## CultureInfo::GetCultureInfo(const String\&) methode


Haalt de cultuur op op basis van de naam. Hetzelfde als CreateSpecificCulture.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(const String &name)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Vooraf gedefinieerde cultuurnaam of de naam van een bestaand cultuurobject. |

### Retourwaarde

Nieuw aangemaakt cultuurobject.

## CultureInfo::GetCultureInfo(const String\&, const String\&) methode


Haalt de cultuur op op basis van de naam.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(const String &name, const String &text_and_compare_culture_name)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Cultuurnaam. |
| text_and_compare_culture_name | const [String](../../../system/string/)\& | Cultuurnaam die wordt gebruikt voor [TextInfo](../../textinfo/) en [CompareInfo](../../compareinfo/) objecten. |

### Retourwaarde

Cultuurobject.

## CultureInfo::GetCultureInfo(int32_t) methode


Haalt de cultuur op op basis van id.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(int32_t culture)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| culture | **int32_t** | Cultuuridentifier. |

### Retourwaarde

Nieuw aangemaakt cultuurobject.

## Zie ook

* Typedef [CultureInfoPtr](../../cultureinfoptr/)
* Klasse [String](../../../system/string/)
* Klasse [CultureInfo](../)
* Naamruimte [System::Globalization](../../)
* Library [Aspose.Slides](../../../)