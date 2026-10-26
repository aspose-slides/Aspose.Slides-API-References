---
title: operator-()
second_title: Aspose.Slides för C++ API-referens
description: Subtraherar nullable- och nullpekade värden.
type: docs
weight: 222
url: /sv/system/nullable/operator_minus/
---
## Nullable::operator-(T1) const method

Subtraherar nullable och nullpekade värden.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-(T1) const
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | Högeroperandens typ, bör vara nullptr_t. |

### Returvärde

Tomt [Nullable](../)-objekt.

## Nullable::operator-(const T1\&) const method

Subtraherar nullable och icke-nullbara värden.

```cpp
template<typename T1,typename> auto System::Nullable<T>::operator-(const T1 &other) const -> Nullable<decltype(get_Value() - other)>
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | Högeroperandens typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | const T1\& | värde att subtrahera. |

### Returvärde

Subtraktionsresultat.

## Nullable::operator-(const Nullable\<T1\>\&) const method

Subtraherar nullable-värden.

```cpp
template<typename T1> auto System::Nullable<T>::operator-(const Nullable<T1> &other) const -> System::Nullable<decltype(get_Value() - other.get_Value())>
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | Högeroperandens typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | värde att subtrahera. |

### Returvärde

Subtraktionsresultat.

## Se också

* Klass [Nullable](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)