---
title: Parse()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Převede zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 32-bitové nezapsané celé číslo.
type: docs
weight: 1
url: /cs/system/uint32/parse/
---
## UInt32::Parse(const String\&) metoda


Převede zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 32-bitové nezapsané celé číslo.

```cpp
static uint32_t System::UInt32::Parse(const String &value)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec, který se má převést. |

### Návratová hodnota

32-bitové nezapsané celé číslo rovnající se číslu reprezentovanému v zadaném řetězci.

## UInt32::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metoda


Převede zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 32-bitové nezapsané celé číslo pomocí poskytnutých informací o formátování.

```cpp
static uint32_t System::UInt32::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec, který se má převést. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ukazatel na objekt, který obsahuje informace o formátování řetězce. |

### Návratová hodnota

32-bitové nezapsané celé číslo rovnající se číslu reprezentovanému v zadaném řetězci.

## UInt32::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metoda




```cpp
static uint32_t System::UInt32::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt32::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda




```cpp
static uint32_t System::UInt32::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt32::Parse(const String\&, std::nullptr_t) metoda




```cpp
static uint32_t System::UInt32::Parse(const String &value, std::nullptr_t)
```

## UInt32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metoda


Převede zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 32-bitové nezapsané celé číslo pomocí poskytnutých informací o formátování a stylu čísla.

```cpp
static uint32_t System::UInt32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec, který se má převést. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitová kombinace hodnot výčtového typu NumberStyles, která určuje povolený styl textové reprezentace čísla. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ukazatel na objekt, který obsahuje informace o formátování řetězce. |

### Návratová hodnota

32-bitové nezapsané celé číslo rovnající se číslu reprezentovanému v zadaném řetězci.

## UInt32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metoda




```cpp
static uint32_t System::UInt32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metoda




```cpp
static uint32_t System::UInt32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt32::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) metoda




```cpp
static uint32_t System::UInt32::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Viz také

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Třída [String](../../string/)
* Třída [IFormatProvider](../../iformatprovider/)
* Třída [CultureInfo](../../../system.globalization/cultureinfo/)
* Třída [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt32](../)
* Jmenný prostor [System](../../)
* Library [Aspose.Slides](../../../)