---
title: operator!=()
second_title: Aspose.Slides C++ API referenciája
description: Nem egyenlő összehasonlító operátor.
type: docs
weight: 313
url: /hu/system/string/operator_not_equal/
---
## String::operator!=(const String\&) const metódus

Nem egyenlő összehasonlító operátor.

```cpp
bool System::String::operator!=(const String &str) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) az aktuálishoz való összehasonlításhoz. |

### Visszatérési érték

false, ha mindkét karakterlánc null vagy mindkettő nem null és megegyezik, egyébként true.

## String::operator!=(std::nullptr_t) const metódus

Ellenőrzi, hogy a karakterlánc nem null. Ugyanazt a logikát alkalmazza, mint a [IsNull()](../isnull/) hívás.

```cpp
bool System::String::operator!=(std::nullptr_t) const
```

### Visszatérési érték

false, ha a karakterlánc null, egyébként true.

## Lásd még

* Osztály [String](../)
* Névtere [System](../../)
* Könyvtár [Aspose.Slides](../../../)