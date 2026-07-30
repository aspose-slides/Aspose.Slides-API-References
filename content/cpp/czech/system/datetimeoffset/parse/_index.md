---
title: Parse()
second_title: Aspose.Slides pro C++ – reference API
description: Převede zadaný řetězec na ekvivalent DateTimeOffset.
type: docs
weight: 703
url: /cs/system/datetimeoffset/parse/
---
## DateTimeOffset::Parse(const String\&) metoda

Převede zadaný řetězec na ekvivalent [DateTimeOffset](../).

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) k převodu. |

### Vrácená hodnota

[DateTimeOffset](../) který je ekvivalentní **input**.

## DateTimeOffset::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) metoda

Převede zadaný řetězec na objekt [DateTimeOffset](../) pomocí zadaného poskytovatele formátu a stylu formátování.

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) k převodu. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Poskytovatel formátu. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Styly formátování data a času. |

### Vrácená hodnota

[DateTimeOffset](../) který je ekvivalentní **input**.

## Viz také

* Výčet [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Třída [DateTimeOffset](../)
* Třída [String](../../string/)
* Třída [IFormatProvider](../../iformatprovider/)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)