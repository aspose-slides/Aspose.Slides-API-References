---
title: Parse()
second_title: Aspose.Slides pro C++ API Reference
description: Převádí textovou reprezentaci desetinného čísla na ekvivalentní instanci třídy Decimal.
type: docs
weight: 469
url: /cs/system/decimal/parse/
---
## Decimal::Parse(const String\&) metoda

Převádí textovou reprezentaci desetinného čísla na ekvivalentní instanci třídy [Decimal](../).

```cpp
static Decimal System::Decimal::Parse(const String &s)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| s | const [String](../../string/)\& | Textová reprezentace čísla |

### Návratová hodnota

Nová instance třídy [Decimal](../) představující hodnotu ekvivalentní té, která je představována zadaným řetězcem.

## Decimal::Parse(const String\&, Globalization::NumberStyles) metoda

Převádí textovou reprezentaci desetinného čísla na ekvivalentní instanci třídy [Decimal](../) pomocí zadaného stylu.

```cpp
static Decimal System::Decimal::Parse(const String &s, Globalization::NumberStyles styles)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| s | const [String](../../string/)\& | Textová reprezentace desetinné hodnoty, kterou převést |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitová kombinace hodnot výčtu, která poskytuje doplňující informace o **s**, o prvcích stylu, které mohou být v **s** přítomny, nebo o převodu **s** na objekt [Decimal](../) |

### Návratová hodnota

Nová instance třídy [Decimal](../) představující hodnotu ekvivalentní té, která je představována zadaným řetězcem.

## Decimal::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metoda

Převádí textovou reprezentaci desetinného čísla na ekvivalentní instanci třídy [Decimal](../) pomocí zadaného poskytovatele formátu.

```cpp
static Decimal System::Decimal::Parse(const String &s, const SharedPtr<IFormatProvider> &provider)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| s | const [String](../../string/)\& | Textová reprezentace desetinné hodnoty, kterou převést |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Poskytovatel formátu |

### Návratová hodnota

Nová instance třídy [Decimal](../) představující hodnotu ekvivalentní té, která je představována zadaným řetězcem.

## Decimal::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metoda

Převádí textovou reprezentaci desetinného čísla na ekvivalentní instanci třídy [Decimal](../) pomocí zadaného stylu a poskytovatele formátu.

```cpp
static Decimal System::Decimal::Parse(const String &s, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| s | const [String](../../string/)\& | Textová reprezentace desetinné hodnoty, kterou převést |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitová kombinace hodnot výčtu, která poskytuje doplňující informace o **s**, o prvcích stylu, které mohou být v **s** přítomny, nebo o převodu **s** na objekt [Decimal](../) |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Poskytovatel formátu |

### Návratová hodnota

Nová instance třídy [Decimal](../) představující hodnotu ekvivalentní té, která je představována zadaným řetězcem.

## Viz také

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)