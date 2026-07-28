---
title: operator==()
second_title: Aspose.Slides for C++ API referencia
description: Egyenlőség összehasonlító operátor.
type: docs
weight: 300
url: /hu/system/string/operator_equal_equal/
---
## String::operator==(const String\&) const method

Egyenlőség összehasonlító operátor.

```cpp
bool System::String::operator==(const String &str) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) a jelenlegihez való összehasonlításhoz. |

### Visszatérési érték

true, ha mindkét karakterlánc null, vagy mindkettő nem null és egyezik, false egyébként.

## String::operator==(std::nullptr_t) const method

Ellenőrzi, hogy a karakterlánc null-e. Ugyanazt a logikát alkalmazza, mint a [IsNull()](../isnull/) hívás.

```cpp
bool System::String::operator==(std::nullptr_t) const
```

### Visszatérési érték

true, ha a karakterlánc null, false egyébként.

## Lásd még

* Osztály [String](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)