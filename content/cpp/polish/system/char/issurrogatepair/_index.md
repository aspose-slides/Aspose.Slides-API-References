---
title: IsSurrogatePair()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Określa, czy dwa określone znaki tworzą parę zastępczą UTF-16.
type: docs
weight: 27
url: /pl/system/char/issurrogatepair/
---
## Char::IsSurrogatePair(char_t, char_t) metoda

Określa, czy dwa określone znaki tworzą parę zastępczą UTF-16.

```cpp
static bool System::Char::IsSurrogatePair(char_t highSurrogate, char_t lowSurrogate)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| highSurrogate | char_t | Znak, który jest testowany pod kątem bycia wysokim surrogatem |
| lowSurrogate | char_t | Znak, który jest testowany pod kątem bycia niskim surrogatem |

### Wartość zwracana

True jeśli podane znaki tworzą parę zastępczą, w przeciwnym razie - false

## Char::IsSurrogatePair(const String\&, int) metoda

Określa, czy dwa kolejne znaki w podanym buforze znaków tworzą parę zastępczą.

```cpp
static bool System::Char::IsSurrogatePair(const String &str, int index)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str | const [String](../../string/)\& | Łańcuch znaków |
| index | int | Indeks zero-bazowy w podanym buforze, od którego zaczyna się sekwencja znaków do przetestowania |

### Wartość zwracana

True jeśli podane znaki tworzą parę zastępczą, w przeciwnym razie - false

## Zobacz także

* Klasa [Char](../)
* Klasa [String](../../string/)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)