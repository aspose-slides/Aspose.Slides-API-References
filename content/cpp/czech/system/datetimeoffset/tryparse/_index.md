---
title: TryParse()
second_title: Aspose.Slides pro C++ API Reference
description: Pokouší se převést zadaný řetězec na objekt DateTimeOffset.
type: docs
weight: 729
url: /cs/system/datetimeoffset/tryparse/
---
## DateTimeOffset::TryParse(const String\&, DateTimeOffset\&) method


Pokouší se převést zadaný řetězec na objekt [DateTimeOffset](../).

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, DateTimeOffset &result)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) k převodu. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) který je ekvivalentní **input**. |

### Return Value

true pokud byl **input** úspěšně převeden, jinak - false.

## DateTimeOffset::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) method


Pokouší se převést zadaný řetězec na objekt [DateTimeOffset](../) pomocí zadaného poskytovatele formátu a formátovacího stylu.

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) k převodu. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Poskytovatel formátu. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Styly formátování data a času. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) který je ekvivalentní **input**. |

### Return Value

true pokud byl **input** úspěšně převeden, jinak - false.

## See Also

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [DateTimeOffset](../)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)