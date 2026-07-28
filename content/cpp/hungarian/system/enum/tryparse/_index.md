---
title: TryParse()
second_title: Aspose.Slides C++ API Referencia
description: Megpróbálja a megadott karakterláncot egyenlő enum állandóvá konvertálni.
type: docs
weight: 79
url: /hu/system/enum/tryparse/
---
## Enum::TryParse(const String\&, E\&) metódus


Megpróbálja a megadott karakterláncot egyenlő enum állandóvá konvertálni.

```cpp
static bool System::Enum<E, Guard>::TryParse(const String &str, E &result)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | const [String](../../string/)\& | [String](../../string/) amelyet úgy értelmeznek, hogy az enum állandó nevét tartalmazza |
| result | E\& | A kimeneti paraméter, amely ha a konverzió sikeres, a függvény konverziójának eredményét tartalmazza |

### Visszatérési érték

True if conversion succeeded, otherwise - false

## Enum::TryParse(const String\&, bool, E\&) metódus


Megpróbálja a megadott karakterláncot egyenlő enum állandóvá konvertálni.

```cpp
static bool System::Enum<E, Guard>::TryParse(const String &str, bool ignoreCase, E &result)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | const [String](../../string/)\& | [String](../../string/) amelyet úgy értelmeznek, hogy az enum állandó nevét tartalmazza |
| ignoreCase | **bool** | Megadja, hogy az esetet figyelmen kívül kell-e hagyni a karakterlánc értelmezésekor |
| result | E\& | A kimeneti paraméter, amely ha a konverzió sikeres, a függvény konverziójának eredményét tartalmazza |

### Visszatérési érték

True if conversion succeeded, otherwise - false

## Lásd még

* Osztály [String](../../string/)
* Struktúra [Enum](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)