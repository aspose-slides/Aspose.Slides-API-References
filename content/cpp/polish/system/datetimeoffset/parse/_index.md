---
title: Parse()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Konwertuje podany ciąg znaków na równoważny obiekt DateTimeOffset.
type: docs
weight: 703
url: /pl/system/datetimeoffset/parse/
---
## DateTimeOffset::Parse(const String\&) metoda

Konwertuje podany ciąg znaków na odpowiednik [DateTimeOffset](../).

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) do konwersji. |

### Wartość zwracana

[DateTimeOffset](../) który jest równoważny **input**.

## DateTimeOffset::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) metoda

Konwertuje podany ciąg znaków na obiekt [DateTimeOffset](../) przy użyciu podanego dostawcy formatu i stylu formatowania.

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) do konwersji. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dostawca formatu. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Style formatowania daty i czasu. |

### Wartość zwracana

[DateTimeOffset](../) który jest równoważny **input**.

## Zobacz także

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasa [DateTimeOffset](../)
* Klasa [String](../../string/)
* Klasa [IFormatProvider](../../iformatprovider/)
* Przestrzeń nazw [System](../../)
* Library [Aspose.Slides](../../../)