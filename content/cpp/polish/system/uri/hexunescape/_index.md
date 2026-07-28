---
title: HexUnescape()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Konwertuje podaną szesnastkową reprezentację znaku na znak.
type: docs
weight: 443
url: /pl/system/uri/hexunescape/
---
## Uri::HexUnescape(const String&, int32_t&) metoda

Konwertuje podaną szesnastkową reprezentację znaku na znak.

```cpp
static char16_t System::Uri::HexUnescape(const String &pattern, int32_t &index)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| pattern | const [String](../../string/)\& | Ciąg znaków zawierający szesnastkową reprezentację znaku |
| index | **int32_t**\& | Pozycja w **pattern**, od której rozpoczyna się szesnastkowa reprezentacja znaku |

### Wartość zwracana

Znak reprezentowany przez szesnastkowe kodowanie na pozycji **index**. Jeśli znak na **index** nie jest szesnastkowo zakodowany, zwracany jest znak znajdujący się na **index**. Wartość **index** jest zwiększana, aby wskazywać znak następujący po zwróconym.

## Zobacz także

* Klasa [String](../../string/)
* Klasa [Uri](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)