---
title: NullableBoolHelper()
second_title: Aspose.Slides C++ API hivatkozás
description: Segédfüggvény, amely ellenőrzi, hogy ez és other mindkettő nem null, és ha igen, meghív egy lambdát. Implementációkban használják.
type: docs
weight: 105
url: /hu/system/nullable/nullableboolhelper/
---
## Nullable::NullableBoolHelper(const T1\&, const std::function\<bool()>\&, bool) const method

Segédfüggvény, amely ellenőrzi, hogy ez és **other** mindkettő nem null, és ha igen, meghív egy lambdát. Implementációkban használják.

```cpp
template<typename T1> bool System::Nullable<T>::NullableBoolHelper(const T1 &other, const std::function<bool()> &f, bool default_if_both_are_null=false) const
```

### Sablon paraméterek

| Parameter | Description |
| --- | --- |
| T1 | Más nullable típus. |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| other | const T1\& | Másik nullable érték, amivel összehasonlít. |
| f | const std::function\<**bool**()>\& | Lambda, amelyet akkor hív meg, ha **this** és **other** egyaránt nem null. |
| default_if_both_are_null | **bool** | Visszatérési érték, ha mindkét érték null. |

### Visszatérési érték

false, ha **this** vagy **other** null; **default_if_both_are_null**, ha mindkettő null; **f** hívás eredménye, ha mindkettő nem null.

## Lásd még

* Osztály [Nullable](../)
* Névtere [System](../../)
* Könyvtár [Aspose.Slides](../../../)