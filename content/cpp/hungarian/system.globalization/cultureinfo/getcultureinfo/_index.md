---
title: GetCultureInfo()
second_title: Aspose.Slides for C++ API referencia
description: Kultúrát kér le a neve alapján. Ugyanaz, mint a CreateSpecificCulture.
type: docs
weight: 586
url: /hu/system.globalization/cultureinfo/getcultureinfo/
---
## CultureInfo::GetCultureInfo(const String\&) metódus


Kultúrát kér le a neve alapján. Ugyanaz, mint a CreateSpecificCulture.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(const String &name)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Előre definiált kultúra neve vagy egy már létező kultúra objektum neve. |

### Visszatérési érték

Újonnan létrehozott kultúra objektum.

## CultureInfo::GetCultureInfo(const String\&, const String\&) metódus


Kultúrát kér le a neve alapján.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(const String &name, const String &text_and_compare_culture_name)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Kultúra neve. |
| text_and_compare_culture_name | const [String](../../../system/string/)\& | Kultúra neve, amely a [TextInfo](../../textinfo/) és [CompareInfo](../../compareinfo/) objektumokhoz használatos. |

### Visszatérési érték

Kultúra objektum.

## CultureInfo::GetCultureInfo(int32_t) metódus


Kultúrát kér le azonosító alapján.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(int32_t culture)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| culture | **int32_t** | Kultúra azonosító. |

### Visszatérési érték

Újonnan létrehozott kultúra objektum.

## Lásd még

* Typedef [CultureInfoPtr](../../cultureinfoptr/)
* Osztály [String](../../../system/string/)
* Osztály [CultureInfo](../)
* Névtér [System::Globalization](../../)
* Library [Aspose.Slides](../../../)