---
title: GetCultureInfo()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Získá kulturu podle jejího názvu. Stejné jako CreateSpecificCulture.
type: docs
weight: 586
url: /cs/system.globalization/cultureinfo/getcultureinfo/
---
## CultureInfo::GetCultureInfo(const String\&) metoda

Získá kulturu podle jejího názvu. Stejné jako CreateSpecificCulture.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(const String &name)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Predefined culture name or existing culture object's name. |

### Návratová hodnota

Nově vytvořený objekt kultury.

## CultureInfo::GetCultureInfo(const String\&, const String\&) metoda

Získá kulturu podle jejího názvu.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(const String &name, const String &text_and_compare_culture_name)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Culture name. |
| text_and_compare_culture_name | const [String](../../../system/string/)\& | Název kultury používaný pro objekty [TextInfo](../../textinfo/) a [CompareInfo](../../compareinfo/). |

### Návratová hodnota

Objekt kultury.

## CultureInfo::GetCultureInfo(int32_t) metoda

Získá kulturu podle ID.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(int32_t culture)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| culture | **int32_t** | Identifikátor kultury. |

### Návratová hodnota

Nově vytvořený objekt kultury.

## Viz také

* Typedef [CultureInfoPtr](../../cultureinfoptr/)
* Třída [String](../../../system/string/)
* Třída [CultureInfo](../)
* Jmenný prostor [System::Globalization](../../)
* Knihovna [Aspose.Slides](../../../)