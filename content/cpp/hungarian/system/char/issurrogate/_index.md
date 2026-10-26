---
title: IsSurrogate()
second_title: Aspose.Slides C++ API hivatkozás
description: Megállapítja, hogy a megadott karakter UTF-16 szürregység-kódegység-e.
type: docs
weight: 14
url: /hu/system/char/issurrogate/
---
## Char::IsSurrogate(char_t) metódus

Megállapítja, hogy a megadott karakter UTF-16 szürregység-kódegység-e.

```cpp
static bool System::Char::IsSurrogate(char_t c)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| c | char_t | Egy karakter |

### Visszatérési érték

Igaz, ha a megadott karakter UTF-16 szürregység-kódegység-e, egyébként – hamis

## Char::IsSurrogate(const String\&, int) metódus

Megállapítja, hogy a megadott karakterlánc megadott indexén lévő karakter UTF-16 szürregység-kódegység-e.

```cpp
static bool System::Char::IsSurrogate(const String &s, int index)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| s | const [String](../../string/)\& | Egy karakterlánc |
| index | int | A karakter indexe a megadott karakterláncban |

### Visszatérési érték

Igaz, ha a megadott indexen lévő karakter UTF-16 szürregység-kódegység-e, egyébként – hamis

## Lásd még

* Osztály [Char](../)
* Osztály [String](../../string/)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)