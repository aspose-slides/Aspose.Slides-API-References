---
title: HexUnescape()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar den angivna hexadecimala representationen av ett tecken till ett tecken.
type: docs
weight: 443
url: /sv/system/uri/hexunescape/
---
## Uri::HexUnescape(const String\&, int32_t\&) metod


Konverterar den angivna hexadecimala representationen av ett tecken till ett tecken.

```cpp
static char16_t System::Uri::HexUnescape(const String &pattern, int32_t &index)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pattern | const [String](../../string/)\& | En sträng som innehåller den hexadecimala representationen av ett tecken |
| index | **int32_t**\& | Positionen i **pattern** där den hexadecimala representationen av ett tecken börjar |

### Returvärde

Tecknet som representeras av den hexadecimala kodningen på position **index**. Om tecknet på **index** inte är hexadecimalt kodad, returneras tecknet på **index**. Värdet på **index** ökas så att det pekar på tecknet som följer det returnerade.

## Se också

* Klass [String](../../string/)
* Klass [Uri](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)