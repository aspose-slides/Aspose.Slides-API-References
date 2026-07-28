---
title: IsHighSurrogate()
second_title: Aspose.Slides C++ API referencia
description: Megállapítja, hogy a megadott indexen a megadott karakterláncban lévő karakter UTF-16 magas helyettesítő kódegység-e.
type: docs
weight: 40
url: /hu/system/char/ishighsurrogate/
---
## Char::IsHighSurrogate(const String\&, int) metódus


Megállapítja, hogy a megadott indexen a megadott karakterláncban lévő karakter UTF-16 magas helyettesítő kódegység-e.

```cpp
static bool System::Char::IsHighSurrogate(const String &s, int index)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| s | const [String](../../string/)\& | Egy karakterlánc |
| index | int | A tesztelendő karakter indexe a megadott karakterláncban |

### Visszatérési érték

True if the character at the specified index is a UTF-16 high surrogate code unit, otherwise - false

## Char::IsHighSurrogate(const char_t *, int) metódus


Megállapítja, hogy a megadott indexen a megadott karakterpufferben lévő karakter magas helyettesítő-e.

```cpp
static bool System::Char::IsHighSurrogate(const char_t *str, int idx)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | const char_t * | Mutató a karakterpuffer elejére |
| idx | int | Nullával kezdődő index a megadott pufferben a tesztelendő karakterhez |

### Visszatérési érték

True if the character at the specified index is a high surrogate, otherwise - false

## Char::IsHighSurrogate(char_t) metódus


Megállapítja, hogy a megadott karakter magas helyettesítő-e.

```cpp
static bool System::Char::IsHighSurrogate(char_t c)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| c | char_t | A tesztelendő karakter |

### Visszatérési érték

True if the specified character is a high surrogate, otherwise - false

## Lásd még

* Osztály [String](../../string/)
* Osztály [Char](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)