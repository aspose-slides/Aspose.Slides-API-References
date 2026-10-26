---
title: EnumParseHelper
second_title: Aspose.Slides C++ API hivatkozás
description: Segédosztály, amely a string ábrázolását egy enum konstanszá alakítja át a megfelelő enum értékké.
type: docs
weight: 1613
url: /hu/system/enumparsehelper/
---
## EnumParseHelper struct

Segédosztály, amely a string reprezentációját az enum konstans átalakításához biztosítja, így a megfelelő enum értéket kapjuk.

```cpp
template<class E,class G,class Guard>class EnumParseHelper
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| E | Az enum típusa, amellyel az osztály metódusai dolgoznak |
| G | A [System::Enum](../enum/) második formális argumentuma, amelyet használni kell. |
| Guard | Formális sablonargumentum a rendelkezésre álló elemzési algoritmus kiválasztásához. |

## Módszerek

| Metódus | Leírás |
| --- | --- |
| static E [Parse](./parse/)(const [String](../string/)\&, **bool**) | Átalakítja a megadott string-et a megfelelő enum konstans értékre. |

## Lásd még

* Névterület [System](../)
* Könyvtár [Aspose.Slides](../../)