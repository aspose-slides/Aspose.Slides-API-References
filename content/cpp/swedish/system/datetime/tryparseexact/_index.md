---
title: TryParseExact()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar den angivna strängrepresentationen av ett datum- och tidsvärde till motsvarande DateTime-objekt med hjälp av det angivna formatet, kultur-specifik formatinformation och stil. Formatet för strängrepresentationen måste exakt matcha det angivna formatet.
type: docs
weight: 898
url: /sv/system/datetime/tryparseexact/
---
## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) metod


Konverterar den angivna strängrepresentationen av ett datum- och tidsvärde till motsvarande [DateTime](../)-objekt med hjälp av det angivna formatet, kultur-specifik formatinformation och stil. Formatet för strängrepresentationen måste exakt matcha det angivna formatet.

```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | const [String](../../string/)\& | Strängrepresentationen av ett datum- och tidsvärde som ska konverteras. |
| format | const [String](../../string/)\& | Strängformatet. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | [IFormatProvider](../../iformatprovider/)-objektet som tillhandahåller kultur-specifik formatinformation. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | En bitvis kombination av uppräkningens värden som ger ytterligare information om **s**, om stilelement som kan finnas i **s**, eller om konverteringen från **s** till ett [DateTime](../)-objekt. |
| result | [DateTime](../)\& | Utdataargumentet som, om konverteringen lyckas, innehåller konverteringsresultatet. |

### Returvärde

True om konverteringen lyckas, annars - false.

## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) metod




```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) metod




```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) metod




```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) metod


Konverterar den angivna strängrepresentationen av ett datum- och tidsvärde till motsvarande [DateTime](../)-objekt med hjälp av de angivna formaten, kultur-specifik formatinformation och stil. Formatet för strängrepresentationen måste exakt matcha ett eller flera av de angivna formaten.

```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | const [String](../../string/)\& | Strängrepresentationen av ett datum- och tidsvärde som ska konverteras. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | Arrayen av strängformat. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | [IFormatProvider](../../iformatprovider/)-objektet som tillhandahåller kultur-specifik formatinformation. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | En bitvis kombination av uppräkningens värden som ger ytterligare information om **s**, om stilelement som kan finnas i **s**, eller om konverteringen från **s** till ett [DateTime](../)-objekt. |
| result | [DateTime](../)\& | Utdataargumentet som, om konverteringen lyckas, innehåller konverteringsresultatet. |

### Returvärde

True om konverteringen lyckas, annars - false.

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) metod




```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) metod




```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) metod




```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## Se också

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [DateTime](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)