---
title: Parse()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar strängrepresentationen av ett decimaltal till en motsvarande instans av Decimal-klassen.
type: docs
weight: 469
url: /sv/system/decimal/parse/
---
## Decimal::Parse(const String\&) metod

Konverterar strängrepresentationen av ett decimaltal till en motsvarande instans av [Decimal](../) klass.

```cpp
static Decimal System::Decimal::Parse(const String &s)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | const [String](../../string/)\& | Strängrepresentationen av ett tal |

### Returvärde

En ny instans av [Decimal](../) klass som representerar ett värde som är motsvarande det som representeras av den specificerade strängen.

## Decimal::Parse(const String\&, Globalization::NumberStyles) metod

Konverterar strängrepresentationen av ett decimaltal till en motsvarande instans av [Decimal](../) klass med den angivna stilen.

```cpp
static Decimal System::Decimal::Parse(const String &s, Globalization::NumberStyles styles)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | const [String](../../string/)\& | Strängrepresentationen av ett decimalvärde att konvertera |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | En bitvis kombination av uppräkningsvärdena som ger ytterligare information om **s**, om stilelement som kan finnas i **s**, eller om konverteringen från **s** till ett [Decimal](../) objekt |

### Returvärde

En ny instans av [Decimal](../) klass som representerar ett värde som är motsvarande det som representeras av den specificerade strängen

## Decimal::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metod

Konverterar strängrepresentationen av ett decimaltal till en motsvarande instans av [Decimal](../) klass med den angivna formatleverantören.

```cpp
static Decimal System::Decimal::Parse(const String &s, const SharedPtr<IFormatProvider> &provider)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | const [String](../../string/)\& | Strängrepresentationen av ett decimalvärde att konvertera |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formatleverantör |

### Returvärde

En ny instans av [Decimal](../) klass som representerar ett värde som är motsvarande det som representeras av den specificerade strängen

## Decimal::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metod

Konverterar strängrepresentationen av ett decimaltal till en motsvarande instans av [Decimal](../) klass med den angivna stilen och formatleverantören.

```cpp
static Decimal System::Decimal::Parse(const String &s, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | const [String](../../string/)\& | Strängrepresentationen av ett decimalvärde att konvertera |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | En bitvis kombination av uppräkningsvärdena som ger ytterligare information om **s**, om stilelement som kan finnas i **s**, eller om konverteringen från **s** till ett [Decimal](../) objekt |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formatleverantör |

### Returvärde

En ny instans av [Decimal](../) klass som representerar ett värde som är motsvarande det som representeras av den specificerade strängen

## Se även

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klass [Decimal](../)
* Klass [String](../../string/)
* Klass [IFormatProvider](../../iformatprovider/)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)