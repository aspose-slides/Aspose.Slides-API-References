---
title: operator+()
second_title: Aspose.Slides for C++ API referenciája
description: Visszaad egy alapértelmezés szerint példányosított Nullable<T> osztálypéldányt.
type: docs
weight: 209
url: /hu/system/nullable/operator_plus/
---
## Nullable::operator+(std::nullptr_t) const metódus


Visszaad egy alapértelmezés szerint példányosított Nullable<T> osztálypéldányt.

```cpp
Nullable<T> System::Nullable<T>::operator+(std::nullptr_t) const
```

## Nullable::operator+(const T1\&) const metódus


Összead a nullable és a non-nullable értékeket.

```cpp
template<typename T1,typename> auto System::Nullable<T>::operator+(const T1 &other) const -> Nullable<decltype(get_Value()+other)>
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | Jobb operandus típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| other | const T1\& | hozzáadandó érték. |

### Visszatérési érték

Összeadási eredmény.

## Nullable::operator+(const Nullable\<T1\>\&) const metódus


Összead nullable értékeket.

```cpp
template<typename T1> auto System::Nullable<T>::operator+(const Nullable<T1> &other) const -> System::Nullable<decltype(get_Value()+other.get_Value())>
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | Jobb operandus típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | hozzáadandó érték. |

### Visszatérési érték

Összeadási eredmény.

## Lásd még

* Osztály [Nullable](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)