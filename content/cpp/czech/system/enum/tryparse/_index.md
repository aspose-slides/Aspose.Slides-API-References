---
title: TryParse()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Pokusí se převést zadaný řetězec na odpovídající konstantu výčtu.
type: docs
weight: 79
url: /cs/system/enum/tryparse/
---
## Enum::TryParse(const String\&, E\&) metoda

Pokusí se převést zadaný řetězec na odpovídající konstantu výčtu.

```cpp
static bool System::Enum<E, Guard>::TryParse(const String &str, E &result)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | const [String](../../string/)\& | [String](../../string/) která je interpretována jako obsahující název konstanty výčtu |
| result | E\& | Výstupní parametr, který při úspěšné konverzi obsahuje výsledek konverze funkce |

### Návratová hodnota

True pokud se konverze podařila, jinak - false

## Enum::TryParse(const String\&, bool, E\&) metoda

Pokusí se převést zadaný řetězec na odpovídající konstantu výčtu.

```cpp
static bool System::Enum<E, Guard>::TryParse(const String &str, bool ignoreCase, E &result)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | const [String](../../string/)\& | [String](../../string/) která je interpretována jako obsahující název konstanty výčtu |
| ignoreCase | **bool** | Určuje, zda má být při interpretaci řetězce ignorována velikost písmen |
| result | E\& | Výstupní parametr, který při úspěšné konverzi obsahuje výsledek konverze při návratu funkce |

### Návratová hodnota

True pokud se konverze podařila, jinak - false

## See Also

* Třída [String](../../string/)
* Struktura [Enum](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)