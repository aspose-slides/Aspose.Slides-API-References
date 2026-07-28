---
title: ParseExact()
second_title: Aspose.Slides dla C++ – odniesienie do API
description: Konwertuje podany ciąg znaków na obiekt DateTimeOffset przy użyciu określonego formatu, dostawcy formatu i stylu formatowania.
type: docs
weight: 716
url: /pl/system/datetimeoffset/parseexact/
---
## DateTimeOffset::ParseExact(const String&, const String&, const SharedPtr<IFormatProvider>&, Globalization::DateTimeStyles) metoda


Converts the specified string to [DateTimeOffset](../) object using the specified format, format provider and formatting style.

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [String](../../string/)& | [String](../../string/) do konwersji. |
| format | const [String](../../string/)& | Łańcuch formatu. |
| provider | const [SharedPtr](../../sharedptr/)<[IFormatProvider](../../iformatprovider/)>& | Dostawca formatu. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Style formatowania daty i czasu. |

### Wartość zwracana

[DateTimeOffset](../) który jest równoważny **input**.

## DateTimeOffset::ParseExact(const String&, const ArrayPtr<String>&, const SharedPtr<IFormatProvider>&, Globalization::DateTimeStyles) metoda


Converts the specified string to [DateTimeOffset](../) object using the specified formats, format provider and formatting style.

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [String](../../string/)& | [String](../../string/) do konwersji. |
| formats | const [ArrayPtr](../../arrayptr/)<[String](../../string/)>& | [Array](../../array/) łańcuchów formatu. |
| provider | const [SharedPtr](../../sharedptr/)<[IFormatProvider](../../iformatprovider/)>& | Dostawca formatu. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Style formatowania daty i czasu. |

### Wartość zwracana

[DateTimeOffset](../) który jest równoważny **input**.

## Zobacz również

* Wyliczenie [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Definicja typu [SharedPtr](../../sharedptr/)
* Definicja typu [ArrayPtr](../../arrayptr/)
* Klasa [DateTimeOffset](../)
* Klasa [String](../../string/)
* Klasa [IFormatProvider](../../iformatprovider/)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)