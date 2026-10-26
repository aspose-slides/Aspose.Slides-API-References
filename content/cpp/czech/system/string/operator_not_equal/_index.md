---
title: operator!=()
second_title: Aspose.Slides pro C++ – reference API
description: Operátor porovnání nerovnosti.
type: docs
weight: 313
url: /cs/system/string/operator_not_equal/
---
## String::operator!=(const String\&) const metoda

Operátor porovnání nerovnosti.

```cpp
bool System::String::operator!=(const String &str) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) k porovnání s aktuálním. |

### Návratová hodnota

false, pokud jsou oba řetězce null, nebo pokud nejsou null a shodují se, jinak true.

## String::operator!=(std::nullptr_t) const metoda

Kontroluje, zda řetězec není null. Používá stejnou logiku jako volání [IsNull()](../isnull/).

```cpp
bool System::String::operator!=(std::nullptr_t) const
```

### Návratová hodnota

false, pokud je řetězec null, jinak true.

## Viz také

* Třída [String](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)