---
title: Parse()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar den angivna strängrepresentationen av ett datum- och tidsvärde till motsvarande DateTime-objekt.
type: docs
weight: 859
url: /sv/system/datetime/parse/
---
## DateTime::Parse(const String\&) metod


Konverterar den angivna strängrepresentationen av ett datum- och tidsvärde till motsvarande [DateTime](../)-objekt.

```cpp
static DateTime System::DateTime::Parse(const String &s)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | Strängrepresentationen av ett datum- och tidsvärde att konvertera. |

### Returvärde

En ny instans av klassen [DateTime](../) som representerar datum- och tidsvärdet som är motsvarande det som representeras av den angivna strängen.

## DateTime::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) metod


Konverterar den angivna strängrepresentationen av ett datum- och tidsvärde till motsvarande [DateTime](../)-objekt med hjälp av kulturspecifik formatinformation.

```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | Strängrepresentationen av ett datum- och tidsvärde att konvertera. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Objektet [IFormatProvider](../../iformatprovider/) som tillhandahåller kulturspecifik formatinformation. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | En bitvis kombination av uppräkningsvärdena som ger ytterligare information om **s**, om stilelement som kan finnas i **s**, eller om konverteringen från **s** till ett [DateTime](../)-objekt. |

### Returvärde

En ny instans av klassen [DateTime](../) som representerar datum- och tidsvärdet som är motsvarande det som representeras av den angivna strängen.

## DateTime::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) metod




```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::Parse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) metod




```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::Parse(const String\&, std::nullptr_t, Globalization::DateTimeStyles) metod




```cpp
static DateTime System::DateTime::Parse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## Se även

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klass [DateTime](../)
* Klass [String](../../string/)
* Klass [IFormatProvider](../../iformatprovider/)
* Klass [CultureInfo](../../../system.globalization/cultureinfo/)
* Klass [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)