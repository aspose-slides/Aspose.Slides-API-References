---
title: IsHighSurrogate()
second_title: Aspose.Slides pro C++ API Reference
description: Určuje, zda znak na zadaném indexu v zadaném řetězci je jednotka kódu UTF-16 high surrogate.
type: docs
weight: 40
url: /cs/system/char/ishighsurrogate/
---
## Char::IsHighSurrogate(const String\&, int) metoda

Určuje, zda znak na zadaném indexu v zadaném řetězci je jednotka kódu UTF-16 high surrogate.

```cpp
static bool System::Char::IsHighSurrogate(const String &s, int index)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| s | const [String](../../string/)\& | Řetězec |
| index | int | Index v zadaném řetězci znaku, který se testuje |

### Návratová hodnota

True pokud je znak na zadaném indexu jednotka kódu UTF-16 high surrogate, jinak – false

## Char::IsHighSurrogate(const char_t *, int) metoda

Určuje, zda znak na zadaném indexu v zadaném bufferu znaků je high surrogate.

```cpp
static bool System::Char::IsHighSurrogate(const char_t *str, int idx)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | const char_t * | Ukazatel na začátek bufferu znaků |
| idx | int | Nulový index v zadaném bufferu znaku, který se testuje |

### Návratová hodnota

True pokud je znak na zadaném indexu high surrogate, jinak – false

## Char::IsHighSurrogate(char_t) metoda

Určuje, zda je zadaný znak high surrogate.

```cpp
static bool System::Char::IsHighSurrogate(char_t c)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| c | char_t | Testovaný znak |

### Návratová hodnota

True pokud je zadaný znak high surrogate, jinak – false

## Viz také

* Class [String](../../string/)
* Class [Char](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)