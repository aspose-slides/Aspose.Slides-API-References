---
title: TryParse()
second_title: Aspose.Slides dla C++ dokumentacja API
description: Próbuje przekonwertować podany ciąg znaków na obiekt DateTimeOffset.
type: docs
weight: 729
url: /pl/system/datetimeoffset/tryparse/
---
## DateTimeOffset::TryParse(const String\&, DateTimeOffset\&) method


Próbuje przekształcić podany ciąg znaków w obiekt [DateTimeOffset](../).

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, DateTimeOffset &result)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) do konwersji. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) równoważny **input**. |

### Wartość zwracana

true, jeśli **input** został pomyślnie skonwertowany, w przeciwnym razie - false.

## DateTimeOffset::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) method


Próbuje przekształcić podany ciąg znaków w obiekt [DateTimeOffset](../) przy użyciu określonego dostawcy formatu i stylu formatowania.

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) do konwersji. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dostawca formatu. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Style formatowania daty i czasu. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) równoważny **input**. |

### Wartość zwracana

true, jeśli **input** został pomyślnie skonwertowany, w przeciwnym razie - false.

## Zobacz także

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasa [String](../../string/)
* Klasa [DateTimeOffset](../)
* Klasa [IFormatProvider](../../iformatprovider/)
* Przestrzeń nazw [System](../../)
* Library [Aspose.Slides](../../../)