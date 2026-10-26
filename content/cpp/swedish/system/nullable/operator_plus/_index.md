---
title: operator+()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar en standardkonstruktad instans av Nullable<T>-klassen.
type: docs
weight: 209
url: /sv/system/nullable/operator_plus/
---
## Nullable::operator+(std::nullptr_t) const metod

Returnerar en standardkonstruktad instans av Nullable<T>-klass.

```cpp
Nullable<T> System::Nullable<T>::operator+(std::nullptr_t) const
```

## Nullable::operator+(const T1\&) const metod

Summerar nullbara och icke-nullbara värden.

```cpp
template<typename T1,typename> auto System::Nullable<T>::operator+(const T1 &other) const -> Nullable<decltype(get_Value()+other)>
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | Typ för höger operand. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | const T1\& | värde att lägga till. |

### Returvärde

Resultat av summeringen.

## Nullable::operator+(const Nullable\<T1\>\&) const metod

Summerar nullbara värden.

```cpp
template<typename T1> auto System::Nullable<T>::operator+(const Nullable<T1> &other) const -> System::Nullable<decltype(get_Value()+other.get_Value())>
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | Typ för höger operand. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | värde att lägga till. |

### Returvärde

Resultat av summeringen.

## Se också

* Klass [Nullable](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)