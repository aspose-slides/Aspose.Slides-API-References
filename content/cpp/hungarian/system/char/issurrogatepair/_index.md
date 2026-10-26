---
title: IsSurrogatePair()
second_title: Aspose.Slides C++ API referencia
description: Megállapítja, hogy a két megadott karakter egy UTF-16 szurogat párt alkot-e.
type: docs
weight: 27
url: /hu/system/char/issurrogatepair/
---
## Char::IsSurrogatePair(char_t, char_t) metódus


Meghatározza, hogy a két megadott karakter egy UTF-16 szurogat párt alkot-e.

```cpp
static bool System::Char::IsSurrogatePair(char_t highSurrogate, char_t lowSurrogate)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| highSurrogate | char_t | Egy karakter, amelyet magas szurogatként tesztelnek |
| lowSurrogate | char_t | Egy karakter, amelyet alacsony szurogatként tesztelnek |

### Visszatérési érték

Igaz, ha a megadott karakterek szurogat párt alkotnak, egyébként - hamis

## Char::IsSurrogatePair(const String\&, int) metódus


Meghatározza, hogy a megadott karakterpufferben két egymást követő karakter szurogat párt alkot-e.

```cpp
static bool System::Char::IsSurrogatePair(const String &str, int index)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | const [String](../../string/)\& | Egy karakterlánc |
| index | int | Egy nulla alapú index a megadott pufferben, ahol a tesztelendő karaktersorozat kezdődik |

### Visszatérési érték

Igaz, ha a megadott karakterek szurogat párt alkotnak, egyébként - hamis

## Lásd még

* Osztály [Char](../)
* Osztály [String](../../string/)
* Névterület [System](../../)
* Könyvtár [Aspose.Slides](../../../)