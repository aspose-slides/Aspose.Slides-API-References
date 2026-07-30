---
title: TryParse()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Převede řetězec na ekvivalentní objekt TimeSpan a vrátí výsledek převodu.
type: docs
weight: 560
url: /cs/system/timespan/tryparse/
---
## TimeSpan::TryParse(const String\&, TimeSpan\&) metoda


Převede řetězec na ekvivalentní [TimeSpan](../) objekt a vrátí výsledek převodu.

```cpp
static bool System::TimeSpan::TryParse(const String &input, TimeSpan &result)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [String](../../string/)\& | Vstupní řetězec. |
| result | [TimeSpan](../)\& | Časový interval, který odpovídá řetězci. |

### Návratová hodnota

True pokud byl řetězec úspěšně převeden; jinak false.

## TimeSpan::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) metoda


Převede řetězec na ekvivalentní [TimeSpan](../) objekt pomocí zadaného poskytovatele formátu a vrátí výsledek převodu.

```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [String](../../string/)\& | Vstupní řetězec. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Poskytovatel formátu, který poskytuje informace o kulturně specifickém formátování. |
| result | [TimeSpan](../)\& | Časový interval, který odpovídá řetězci. |

### Návratová hodnota

True pokud byl řetězec úspěšně převeden; jinak false.

## TimeSpan::TryParse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) metoda




```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## TimeSpan::TryParse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) metoda




```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## TimeSpan::TryParse(const String\&, std::nullptr_t, TimeSpan\&) metoda




```cpp
static bool System::TimeSpan::TryParse(const String &input, std::nullptr_t, TimeSpan &result)
```

## Viz také

* Typedef [SharedPtr](../../sharedptr/)
* Třída [String](../../string/)
* Třída [TimeSpan](../)
* Třída [IFormatProvider](../../iformatprovider/)
* Třída [CultureInfo](../../../system.globalization/cultureinfo/)
* Třída [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)