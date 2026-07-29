---
title: GetCultureInfo()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar kultur efter dess namn. Samma som CreateSpecificCulture.
type: docs
weight: 586
url: /sv/system.globalization/cultureinfo/getcultureinfo/
---
## CultureInfo::GetCultureInfo(const String\&) metod

Hämtar kultur efter dess namn. Samma som CreateSpecificCulture.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(const String &name)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Fördefinierat kulturnamn eller befintligt kulturobjekts namn. |

### Returvärde

Nyskapat kulturobjekt.

## CultureInfo::GetCultureInfo(const String\&, const String\&) metod

Hämtar kultur efter dess namn.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(const String &name, const String &text_and_compare_culture_name)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Kulturnamn. |
| text_and_compare_culture_name | const [String](../../../system/string/)\& | Kulturnamn som används för [TextInfo](../../textinfo/) och [CompareInfo](../../compareinfo/) objekt. |

### Returvärde

Kulturobjekt.

## CultureInfo::GetCultureInfo(int32_t) metod

Hämtar kultur efter ID.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(int32_t culture)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| culture | **int32_t** | Kulturidentifierare. |

### Returvärde

Nyskapat kulturobjekt.

## Se också

* Typedef [CultureInfoPtr](../../cultureinfoptr/)
* Klass [String](../../../system/string/)
* Klass [CultureInfo](../)
* Namnrymd [System::Globalization](../../)
* Bibliotek [Aspose.Slides](../../../)