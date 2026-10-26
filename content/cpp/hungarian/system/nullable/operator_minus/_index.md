---
title: operator-()
second_title: Aspose.Slides for C++ API referencia
description: Kivonja a nullable és a nullra mutató értékeket.
type: docs
weight: 222
url: /hu/system/nullable/operator_minus/
---
## Nullable::operator-(T1) const metódus


Kivonja a nullable és a nullra mutató értékeket.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-(T1) const
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | Jobb operandus típusa, legyen nullptr_t. |

### Visszatérési érték

Üres [Nullable](../) objektum.

## Nullable::operator-(const T1\&) const metódus


Kivonja a nullable és a nem nullable értékeket.

```cpp
template<typename T1,typename> auto System::Nullable<T>::operator-(const T1 &other) const -> Nullable<decltype(get_Value() - other)>
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | Jobb operandus típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| other | const T1\& | kivonandó érték. |

### Visszatérési érték

Kivonás eredménye.

## Nullable::operator-(const Nullable\<T1\>\&) const metódus


Kivonja a nullable értékeket.

```cpp
template<typename T1> auto System::Nullable<T>::operator-(const Nullable<T1> &other) const -> System::Nullable<decltype(get_Value() - other.get_Value())>
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | Jobb operandus típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | kivonandó érték. |

### Visszatérési érték

Kivonás eredménye.

## Lásd még

* Osztály [Nullable](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)