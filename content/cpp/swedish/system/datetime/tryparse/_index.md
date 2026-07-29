---
title: TryParse()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar den angivna strängrepresentationen av ett datum- och tidsvärde till motsvarande DateTime-objekt.
type: docs
weight: 885
url: /sv/system/datetime/tryparse/
---
## DateTime::TryParse(const String\&, DateTime\&) metod


Konverterar den angivna strängrepresentationen av ett datum och tidsvärde till motsvarande [DateTime](../)-objekt.

```cpp
static bool System::DateTime::TryParse(const String &s, DateTime &result)
```


### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| s | const [String](../../string/)\& | Strängrepresentationen av ett datum- och tidsvärde att konvertera. |
| result | [DateTime](../)\& | Utdataargumentet som, om konverteringen lyckas, innehåller konverteringsresultatet. |

### Returvärde

Sant om konverteringen lyckas, annars - falskt.

## DateTime::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) metod


Konverterar den angivna strängrepresentationen av ett datum och tidsvärde till motsvarande [DateTime](../)-objekt med den angivna kulturspecifika formatinformationen och stil.

```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```


### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| s | const [String](../../string/)\& | Strängrepresentationen av ett datum- och tidsvärde att konvertera. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | [IFormatProvider](../../iformatprovider/)-objektet som tillhandahåller kulturspecifik formatinformation. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | En bitvis kombination av uppräkningsvärdena som ger ytterligare information om **s**, om stilelement som kan finnas i **s**, eller om konverteringen från **s** till ett [DateTime](../)-objekt. |
| result | [DateTime](../)\& | Utdataargumentet som, om konverteringen lyckas, innehåller konverteringsresultatet. |

### Returvärde

Sant om konverteringen lyckas, annars - falskt.

## DateTime::TryParse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) metod




```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) metod




```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParse(const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) metod




```cpp
static bool System::DateTime::TryParse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## Se även

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klass [String](../../string/)
* Klass [DateTime](../)
* Klass [IFormatProvider](../../iformatprovider/)
* Klass [CultureInfo](../../../system.globalization/cultureinfo/)
* Klass [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)