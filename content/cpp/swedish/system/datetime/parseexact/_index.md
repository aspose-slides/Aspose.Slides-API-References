---
title: ParseExact()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar den angivna strängrepresentationen av ett datum- och tidsvärde till motsvarande DateTime objekt med hjälp av det angivna formatet och kultur-specifik formatinformation. Strängrepresentationens format måste exakt matcha det angivna formatet. Kastar ett undantag om konverteringen misslyckas.
type: docs
weight: 872
url: /sv/system/datetime/parseexact/
---
## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) metod


Konverterar den angivna strängrepresentationen av ett datum- och tidsvärde till motsvarande [DateTime](../) objekt med hjälp av det angivna formatet och kultur-specifik formatinformation. Strängrepresentationens format måste exakt matcha det angivna formatet. Kastar ett undantag om konverteringen misslyckas.

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | const [String](../../string/)\& | Strängrepresentationen av ett datum- och tidsvärde som ska konverteras. |
| format | const [String](../../string/)\& | Strängformatet. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Det [IFormatProvider](../../iformatprovider/) objektet som tillhandahåller kultur-specifik formatinformation. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | En bitvis kombination av uppräkningens värden som ger ytterligare information om **s**, om stilelement som kan finnas i **s**, eller om konverteringen från **s** till ett [DateTime](../) objekt. |

### Returvärde

En ny instans av [DateTime](../) klass som representerar datum- och tidsvärdet som motsvarar det som representeras av den angivna strängen.

## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) metod




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) metod




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles) metod




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) metod


Konverterar den angivna strängrepresentationen av ett datum- och tidsvärde till motsvarande [DateTime](../) objekt med hjälp av de angivna formaten, kultur-specifik formatinformation och stil. Strängrepresentationens format måste exakt matcha ett eller flera av de angivna formaten. Kastar ett undantag om konverteringen misslyckas.

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | const [String](../../string/)\& | Strängrepresentationen av ett datum- och tidsvärde som ska konverteras. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | Arrayen av strängformat. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Det [IFormatProvider](../../iformatprovider/) objektet som tillhandahåller kultur-specifik formatinformation. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | En bitvis kombination av uppräkningens värden som ger ytterligare information om **s**, om stilelement som kan finnas i **s**, eller om konverteringen från **s** till ett [DateTime](../) objekt. |

### Returvärde

En ny instans av [DateTime](../) klass som representerar datum- och tidsvärdet som motsvarar det som representeras av den angivna strängen.

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) metod




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) metod




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles) metod




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::DateTimeStyles styles)
```

## Se även

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Klass [DateTime](../)
* Klass [String](../../string/)
* Klass [IFormatProvider](../../iformatprovider/)
* Klass [CultureInfo](../../../system.globalization/cultureinfo/)
* Klass [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)