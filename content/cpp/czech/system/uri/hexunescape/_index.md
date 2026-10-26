---
title: HexUnescape()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Převádí zadané hexadecimální vyjádření znaku na znak.
type: docs
weight: 443
url: /cs/system/uri/hexunescape/
---
## Uri::HexUnescape(const String\&, int32_t\&) metoda

Převádí zadané hexadecimální vyjádření znaku na znak.

```cpp
static char16_t System::Uri::HexUnescape(const String &pattern, int32_t &index)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| pattern | const [String](../../string/)\& | Řetězec obsahující hexadecimální vyjádření znaku |
| index | **int32_t**\& | Pozice v **pattern**, kde hexadecimální vyjádření znaku začíná |

### Návratová hodnota

Znak reprezentovaný hexadecimálním kódováním na pozici **index**. Pokud znak na **index** není hexadecimálně zakódován, je vrácen znak na **index**. Hodnota **index** je zvýšena tak, aby ukazovala na znak následující po vráceném znaku.

## Viz také

* Třída [String](../../string/)
* Třída [Uri](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)