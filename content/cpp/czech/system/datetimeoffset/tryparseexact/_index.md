---
title: TryParseExact()
second_title: Aspose.Slides pro C++ API Reference
description: Zkouší převést zadaný řetězec na objekt DateTimeOffset pomocí zadaných formátů, poskytovatele formátu a stylu formátování.
type: docs
weight: 742
url: /cs/system/datetimeoffset/tryparseexact/
---
## DateTimeOffset::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset&) metoda

Zkouší převést zadaný řetězec na objekt [DateTimeOffset](../) pomocí zadaných formátů, poskytovatele formátu a stylu formátování.

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) k převodu. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | Pole formátovacích řetězců. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Poskytovatel formátu. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Styly formátování data a času. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) která je ekvivalentní **input**. |

### Návratová hodnota

true, pokud byl **input** úspěšně převeden, jinak - false.

## DateTimeOffset::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset&) metoda

Zkouší převést zadaný řetězec na objekt [DateTimeOffset](../) pomocí zadaného formátu, poskytovatele formátu a stylu formátování.

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) k převodu. |
| format | const [String](../../string/)\& | Formátovací řetězec. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Poskytovatel formátu. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Styly formátování data a času. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) která je ekvivalentní **input**. |

### Návratová hodnota

true, pokud byl **input** úspěšně převeden, jinak - false.

## Viz také

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Třída [String](../../string/)
* Třída [IFormatProvider](../../iformatprovider/)
* Třída [DateTimeOffset](../)
* Jmenný prostor [System](../../)
* Library [Aspose.Slides](../../../)