---
title: GetCultureInfo()
second_title: Aspose.Slides dla odniesienia API C++
description: Pobiera kulturę na podstawie jej nazwy. To samo co CreateSpecificCulture.
type: docs
weight: 586
url: /pl/system.globalization/cultureinfo/getcultureinfo/
---
## CultureInfo::GetCultureInfo(const String\&) metoda

Pobiera kulturę na podstawie jej nazwy. To samo co CreateSpecificCulture.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(const String &name)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Predefiniowana nazwa kultury lub nazwa istniejącego obiektu kultury. |

### Wartość zwracana

Nowo utworzony obiekt kultury.

## CultureInfo::GetCultureInfo(const String\&, const String\&) metoda

Pobiera kulturę na podstawie jej nazwy.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(const String &name, const String &text_and_compare_culture_name)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Nazwa kultury. |
| text_and_compare_culture_name | const [String](../../../system/string/)\& | Nazwa kultury używana dla obiektów [TextInfo](../../textinfo/) i [CompareInfo](../../compareinfo/). |

### Wartość zwracana

Obiekt kultury.

## CultureInfo::GetCultureInfo(int32_t) metoda

Pobiera kulturę na podstawie identyfikatora.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(int32_t culture)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| culture | **int32_t** | Identyfikator kultury. |

### Wartość zwracana

Nowo utworzony obiekt kultury.

## Zobacz także

* Typedef [CultureInfoPtr](../../cultureinfoptr/)
* Klasa [String](../../../system/string/)
* Klasa [CultureInfo](../)
* Przestrzeń nazw [System::Globalization](../../)
* Library [Aspose.Slides](../../../)