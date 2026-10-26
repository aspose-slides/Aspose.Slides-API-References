---
title: Parse()
second_title: Aspose.Slides C++ API-referencia
description: Átalakítja a tizedes szám karakterlánc ábrázolását egy ekvivalens Decimal osztálypéldányra.
type: docs
weight: 469
url: /hu/system/decimal/parse/
---
## Decimal::Parse(const String\&) metódus


Converts the string representation of a decimal number into an equivalent instance of [Decimal](../) class.

```cpp
static Decimal System::Decimal::Parse(const String &s)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| s | const [String](../../string/)\& | A szám karakterlánc ábrázolása |

### Visszatérési érték

A new instance of [Decimal](../) class representing a value equivalent to that represented by the specified string.

## Decimal::Parse(const String\&, Globalization::NumberStyles) metódus


Converts the string representation of a decimal number into an equivalent instance of [Decimal](../) class using the specified style.

```cpp
static Decimal System::Decimal::Parse(const String &s, Globalization::NumberStyles styles)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| s | const [String](../../string/)\& | A konvertálandó tizedes érték karakterlánc ábrázolása |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Az enumerációs értékek bitenkénti kombinációja, amely további információt nyújt a **s**-ról, a **s**-ben előforduló stíluselemekről, vagy a **s**-ből egy [Decimal](../) objektummá való konvertálásról |

### Visszatérési érték

A new instance of [Decimal](../) class representing a value equivalent to that represented by the specified string

## Decimal::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metódus


Converts the string representation of a decimal number into an equivalent instance of [Decimal](../) class using the specified format provider.

```cpp
static Decimal System::Decimal::Parse(const String &s, const SharedPtr<IFormatProvider> &provider)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| s | const [String](../../string/)\& | A konvertálandó tizedes érték karakterlánc ábrázolása |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formátumszolgáltató |

### Visszatérési érték

A new instance of [Decimal](../) class representing a value equivalent to that represented by the specified string

## Decimal::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metódus


Converts the string representation of a decimal number into an equivalent instance of [Decimal](../) class using the specified style and format provider.

```cpp
static Decimal System::Decimal::Parse(const String &s, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| s | const [String](../../string/)\& | A konvertálandó tizedes érték karakterlánc ábrázolása |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Az enumerációs értékek bitenkénti kombinációja, amely további információt nyújt a **s**-ról, a **s**-ben előforduló stíluselemekről, vagy a **s**-ből egy [Decimal](../) objektummá való konvertálásról |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formátumszolgáltató |

### Visszatérési érték

A new instance of [Decimal](../) class representing a value equivalent to that represented by the specified string

## Lásd még

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)