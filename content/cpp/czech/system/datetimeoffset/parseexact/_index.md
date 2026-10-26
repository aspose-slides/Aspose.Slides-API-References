---
title: ParseExact()
second_title: Aspose.Slides pro C++ API Reference
description: Převádí zadaný řetězec na objekt DateTimeOffset pomocí zadaného formátu, poskytovatele formátu a stylu formátování.
type: docs
weight: 716
url: /cs/system/datetimeoffset/parseexact/
---
## DateTimeOffset::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) metoda


Převádí zadaný řetězec na objekt [DateTimeOffset](../) pomocí zadaného formátu, poskytovatele formátu a stylu formátování.

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) k převodu. |
| format | const [String](../../string/)\& | Formátovací řetězec. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Poskytovatel formátu. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Styly formátování data a času. |

### Návratová hodnota

[DateTimeOffset](../) který je ekvivalentní **input**.

## DateTimeOffset::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) metoda


Převádí zadaný řetězec na objekt [DateTimeOffset](../) pomocí zadaných formátů, poskytovatele formátu a stylu formátování.

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) k převodu. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | [Array](../../array/) formátovacích řetězců. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Poskytovatel formátu. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Styly formátování data a času. |

### Návratová hodnota

[DateTimeOffset](../) který je ekvivalentní **input**.

## Viz také

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [DateTimeOffset](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)