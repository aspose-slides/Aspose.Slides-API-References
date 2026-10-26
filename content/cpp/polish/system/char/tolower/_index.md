---
title: ToLower()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Konwertuje podany znak na małe litery.
type: docs
weight: 235
url: /pl/system/char/tolower/
---
## Char::ToLower(char_t) metoda

Konwertuje podany znak na małe litery.

```cpp
static char_t System::Char::ToLower(char_t c)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| c | char_t | Znak do konwersji |

### Wartość zwracana

Podany znak w małej literze, jeśli podany znak jest wielką literą, w przeciwnym razie – podany znak

## Char::ToLower(char_t, const SharedPtr\<Globalization::CultureInfo\>\&) metoda

Konwertuje podany znak na małe litery.

```cpp
static char_t System::Char::ToLower(char_t c, const SharedPtr<Globalization::CultureInfo> &culture)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| c | char_t | Znak do konwersji |
| culture | const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Obiekt dostarczający reguły wielkości znaków zależne od kultury. |

### Wartość zwracana

Podany znak w małej literze, jeśli podany znak jest wielką literą, w przeciwnym razie – podany znak

## Zobacz także

* Typedef [SharedPtr](../../sharedptr/)
* Klasa [Char](../)
* Klasa [CultureInfo](../../../system.globalization/cultureinfo/)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)