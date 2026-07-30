---
title: IsSurrogatePair()
second_title: Aspose.Slides pro C++ API referenci
description: Určuje, zda dva zadané znaky tvoří UTF-16 surrogate pár.
type: docs
weight: 27
url: /cs/system/char/issurrogatepair/
---
## Char::IsSurrogatePair(char_t, char_t) metoda

Určuje, zda dva zadané znaky tvoří UTF-16 surrogate pár.

```cpp
static bool System::Char::IsSurrogatePair(char_t highSurrogate, char_t lowSurrogate)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| highSurrogate | char_t | Znak, který se testuje na to, zda je vysoký náhradní znak |
| lowSurrogate | char_t | Znak, který se testuje na to, zda je nízký náhradní znak |

### Návratová hodnota

True pokud zadané znaky tvoří surrogate pár, jinak - false

## Char::IsSurrogatePair(const String\&, int) metoda

Určuje, zda dva po sobě jdoucí znaky ve zadaném bufferu znaků tvoří surrogate pár.

```cpp
static bool System::Char::IsSurrogatePair(const String &str, int index)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | const [String](../../string/)\& | Řetězec |
| index | int | Nulový index ve zadaném bufferu, kde začíná testovaná posloupnost znaků |

### Návratová hodnota

True pokud zadané znaky tvoří surrogate pár, jinak - false

## Viz také

* Třída [Char](../)
* Třída [String](../../string/)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)