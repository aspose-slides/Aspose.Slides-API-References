---
title: Parse()
second_title: Aspose.Slides pro C++ API Reference
description: Převede zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní jednopřesnostní hodnotu s plovoucí desetinnou čárkou.
type: docs
weight: 1
url: /cs/system/single/parse/
---
## Single::Parse(const String\&) metoda

Převede zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní jednopřesnostní hodnotu s plovoucí desetinnou čárkou.

```cpp
static float System::Single::Parse(const String &value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec, který se má převést. |

### Návratová hodnota

Jednopřesnostní hodnota s plovoucí desetinnou čárkou, která je rovna číslu reprezentovanému zadaným řetězcem.

## Single::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metoda

Převede zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní jednopřesnostní hodnotu s plovoucí desetinnou čárkou pomocí poskytnutých informací o formátování.

```cpp
static float System::Single::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec, který se má převést. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ukazatel na objekt, který obsahuje informace o formátu řetězce. |

### Návratová hodnota

Jednopřesnostní hodnota s plovoucí desetinnou čárkou, která je rovna číslu reprezentovanému zadaným řetězcem.

## Single::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metoda




```cpp
static float System::Single::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Single::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda 




```cpp
static float System::Single::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Single::Parse(const String\&, std::nullptr_t) metoda 




```cpp
static float System::Single::Parse(const String &value, std::nullptr_t)
```

## Single::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metoda

Převede zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní jednopřesnostní hodnotu s plovoucí desetinnou čárkou pomocí poskytnutých informací o formátování a stylu čísla.

```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec, který se má převést. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitová kombinace hodnot výčtu NumberStyles, která určuje povolený styl textové reprezentace čísla. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ukazatel na objekt, který obsahuje informace o formátu řetězce. |

### Návratová hodnota

Jednopřesnostní hodnota s plovoucí desetinnou čárkou, která je rovna číslu reprezentovanému zadaným řetězcem.

## Single::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metoda 




```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Single::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda 




```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Single::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) metoda 




```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Viz také

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [Single](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)