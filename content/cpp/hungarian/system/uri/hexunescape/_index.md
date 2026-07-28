---
title: HexUnescape()
second_title: Aspose.Slides C++ API referencia
description: Átalakítja a megadott karakter hexadecimális ábrázolását karakterré.
type: docs
weight: 443
url: /hu/system/uri/hexunescape/
---
## Uri::HexUnescape(const String&, int32_t&) metódus


Átalakítja a megadott karakter hexadecimális ábrázolását karakterré.

```cpp
static char16_t System::Uri::HexUnescape(const String &pattern, int32_t &index)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pattern | const [String](../../string/)\& | Egy karakter hexadecimális ábrázolását tartalmazó karakterlánc |
| index | **int32_t**\& | A **pattern**-ben a karakter hexadecimális ábrázolásának kezdő pozíciója |

### Visszatérési érték

A **index** pozíción található hexadecimális kódolással ábrázolt karakter. Ha a **index** pozícióban lévő karakter nincs hexadecimálisan kódolva, akkor a **index** pozícióban lévő karakter lesz visszaadva. **index** értéke növekszik, hogy az így visszaadott karaktert követő karakterre mutasson.

## Lásd még

* Osztály [String](../../string/)
* Osztály [Uri](../)
* Névterület [System](../../)
* Könyvtár [Aspose.Slides](../../../)