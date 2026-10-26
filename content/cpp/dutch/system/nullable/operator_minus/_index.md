---
title: operator-()
second_title: Aspose.Slides voor C++ API-referentie
description: Trekt nullable- en null-pointerwaarden af.
type: docs
weight: 222
url: /nl/system/nullable/operator_minus/
---
## Nullable::operator-(T1) const methode


Trekt nullable- en null-pointerwaarden af.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-(T1) const
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | Type van de rechter operand, moet nullptr_t zijn. |

### Retourwaarde

Leeg [Nullable](../) object.

## Nullable::operator-(const T1&) const methode


Trekt nullable- en niet-nullable waarden af.

```cpp
template<typename T1,typename> auto System::Nullable<T>::operator-(const T1 &other) const -> Nullable<decltype(get_Value() - other)>
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | Type van de rechter operand. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| other | const T1& | waarde om af te trekken. |

### Retourwaarde

Resultaat van de aftrekking.

## Nullable::operator-(const Nullable\<T1\>&) const methode


Trekt nullable-waarden af.

```cpp
template<typename T1> auto System::Nullable<T>::operator-(const Nullable<T1> &other) const -> System::Nullable<decltype(get_Value() - other.get_Value())>
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | Type van de rechter operand. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>& | waarde om af te trekken. |

### Retourwaarde

Resultaat van de aftrekking.

## Zie ook

* Klasse [Nullable](../)
* Namespace [System](../../)
* Bibliotheek [Aspose.Slides](../../../)