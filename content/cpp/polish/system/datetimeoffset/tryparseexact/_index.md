---
title: TryParseExact()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Próbuje skonwertować podany ciąg do obiektu DateTimeOffset przy użyciu określonych formatów, dostawcy formatu i stylu formatowania.
type: docs
weight: 742
url: /pl/system/datetimeoffset/tryparseexact/
---
## DateTimeOffset::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) metoda


Próbuje skonwertować podany ciąg do obiektu [DateTimeOffset](../) przy użyciu określonych formatów, dostawcy formatu i stylu formatowania.

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) do konwersji. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | Tablice ciągów formatów. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dostawca formatu. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Style formatowania daty i czasu. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) który jest równoważny **input**. |

### Wartość zwracana

true jeśli **input** zostało pomyślnie skonwertowane, w przeciwnym razie - false.

## DateTimeOffset::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) metoda


Próbuje skonwertować podany ciąg do obiektu [DateTimeOffset](../) przy użyciu określonego formatu, dostawcy formatu i stylu formatowania.

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) do konwersji. |
| format | const [String](../../string/)\& | Ciąg formatu. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dostawca formatu. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Style formatowania daty i czasu. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) który jest równoważny **input**. |

### Wartość zwracana

true jeśli **input** zostało pomyślnie skonwertowane, w przeciwnym razie - false.

## Zobacz także

* Wyliczenie [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Definicja typu [ArrayPtr](../../arrayptr/)
* Definicja typu [SharedPtr](../../sharedptr/)
* Klasa [String](../../string/)
* Klasa [IFormatProvider](../../iformatprovider/)
* Klasa [DateTimeOffset](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)