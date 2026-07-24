---
title: GetCultureInfo()
second_title: Aspose.Slides für C++ API-Referenz
description: Ruft die Kultur anhand ihres Namens ab. Entspricht CreateSpecificCulture.
type: docs
weight: 586
url: /de/system.globalization/cultureinfo/getcultureinfo/
---
## CultureInfo::GetCultureInfo(const String\&) method

Ruft die Kultur anhand ihres Namens ab. Gleich wie CreateSpecificCulture.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(const String &name)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Vordefinierter Kulturname oder Name eines bestehenden Kulturobjekts. |

### Rückgabewert

Neu erstelltes Kulturobjekt.

## CultureInfo::GetCultureInfo(const String\&, const String\&) method

Ruft die Kultur anhand ihres Namens ab.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(const String &name, const String &text_and_compare_culture_name)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Kulturname. |
| text_and_compare_culture_name | const [String](../../../system/string/)\& | Kulturname, der für [TextInfo](../../textinfo/)- und [CompareInfo](../../compareinfo/)-Objekte verwendet wird. |

### Rückgabewert

Kulturobjekt.

## CultureInfo::GetCultureInfo(int32_t) method

Ruft die Kultur anhand ihrer ID ab.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(int32_t culture)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| culture | **int32_t** | Kulturkennzeichen. |

### Rückgabewert

Neu erstelltes Kulturobjekt.

## Siehe auch

* Typedef [CultureInfoPtr](../../cultureinfoptr/)
* Klasse [String](../../../system/string/)
* Klasse [CultureInfo](../)
* Namensraum [System::Globalization](../../)
* Library [Aspose.Slides](../../../)