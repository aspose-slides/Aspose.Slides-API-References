---
title: operator==()
second_title: Aspose.Slides pro C++ API Reference
description: Operátor porovnání rovnosti.
type: docs
weight: 300
url: /cs/system/string/operator_equal_equal/
---
## String::operator==(const String\&) const metoda

Operátor porovnání rovnosti.

```cpp
bool System::String::operator==(const String &str) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) k porovnání aktuálního s. |

### Návratová hodnota

true, pokud jsou oba řetězce null, nebo pokud žádný není null a shodují se; false jinak.

## String::operator==(std::nullptr_t) const metoda

Kontroluje, zda je řetězec null. Používá stejnou logiku jako volání [IsNull()](../isnull/).

```cpp
bool System::String::operator==(std::nullptr_t) const
```

### Návratová hodnota

true, pokud je řetězec null, false jinak.

## Viz také

* Třída [String](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)