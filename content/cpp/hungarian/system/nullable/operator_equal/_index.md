---
title: operator=()
second_title: Aspose.Slides C++ API referencia
description: Null értéket rendel az aktuális objektumhoz.
type: docs
weight: 14
url: /hu/system/nullable/operator_equal/
---
## Nullable::operator=(std::nullptr_t) metódus

Null értéket rendel az aktuális objektumhoz.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator=(std::nullptr_t)
```

### Visszatérési érték

Egy [Nullable](../) objektum, amely null-értéket képvisel.

## Nullable::operator=(const T1\&) metódus

Lecseréli az objektum jelenleg reprezentált értékét a megadott értékre.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value &&!std::is_null_pointer<T1>::value, Nullable<T> &>::type System::Nullable<T>::operator=(const T1 &x)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Az | az új érték típusa, amelyet a jelenlegi objektum képvisel |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | const T1\& | az új érték, amelyet a jelenlegi objektum képvisel |

### Visszatérési érték

Az önmagára mutató referencia

## Nullable::operator=(const Nullable\<T1\>\&) metódus

Lecseréli az objektum jelenleg reprezentált értékét a megadott értékre.

```cpp
template<typename T1> Nullable<T> & System::Nullable<T>::operator=(const Nullable<T1> &x)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Az | az új érték típusa, amelyet a jelenlegi objektum képvisel |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | const [Nullable](../)\<T1\>\& | az új érték, amelyet a jelenlegi objektum képvisel |

### Visszatérési érték

Az önmagára mutató referencia

## Lásd még

* Osztály [Nullable](../)
* Struktúra [IsNullable](../../isnullable/)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)