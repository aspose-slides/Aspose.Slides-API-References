---
title: Parse()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar den angivna strängen som innehåller talets strängrepresentation till motsvarande enkelflytande flyttal.
type: docs
weight: 1
url: /sv/system/single/parse/
---
## Single::Parse(const String\&) metod


Konverterar den angivna strängen som innehåller talets strängrepresentation till motsvarande enkelflytande flyttal.

```cpp
static float System::Single::Parse(const String &value)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera. |

### Returvärde

Det enkelflytande flyttal som är lika med talet som representeras av den angivna strängen.

## Single::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metod


Konverterar den angivna strängen som innehåller talets strängrepresentation till motsvarande enkelflytande flyttal med hjälp av den angivna formateringsinformationen.

```cpp
static float System::Single::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | En pekare till ett objekt som innehåller strängformateringsinformationen. |

### Returvärde

Det enkelflytande flyttal som är lika med talet som representeras av den angivna strängen.

## Single::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metod




```cpp
static float System::Single::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Single::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metod




```cpp
static float System::Single::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Single::Parse(const String\&, std::nullptr_t) metod




```cpp
static float System::Single::Parse(const String &value, std::nullptr_t)
```

## Single::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metod


Konverterar den angivna strängen som innehåller talets strängrepresentation till motsvarande enkelflytande flyttal med hjälp av den angivna formateringsinformationen och talstil.

```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | En bitvis kombination av värden i NumberStyles-enum som specificerar det tillåtna formatet för strängrepresentationen av ett tal. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | En pekare till ett objekt som innehåller strängformateringsinformationen. |

### Returvärde

Det enkelflytande flyttal som är lika med talet som representeras av den angivna strängen.

## Single::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metod




```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Single::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metod




```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Single::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) metod




```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Se även

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [Single](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)