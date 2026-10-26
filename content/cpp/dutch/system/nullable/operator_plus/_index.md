---
title: operator+()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een standaard geconstrueerde instantie van de Nullable<T> klasse.
type: docs
weight: 209
url: /nl/system/nullable/operator_plus/
---
## Nullable::operator+(std::nullptr_t) const methode


Retourneert een standaard geconstrueerde instantie van Nullable<T> klasse.

```cpp
Nullable<T> System::Nullable<T>::operator+(std::nullptr_t) const
```

## Nullable::operator+(const T1\&) const methode


Somt nullable en non-nullable waarden op.

```cpp
template<typename T1,typename> auto System::Nullable<T>::operator+(const T1 &other) const -> Nullable<decltype(get_Value()+other)>
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | Right operand type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| other | const T1\& | waarde om toe te voegen. |

### Retourwaarde

Somresultaat.

## Nullable::operator+(const Nullable\<T1\>\&) const methode


Somt nullable waarden op.

```cpp
template<typename T1> auto System::Nullable<T>::operator+(const Nullable<T1> &other) const -> System::Nullable<decltype(get_Value()+other.get_Value())>
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | Right operand type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | waarde om toe te voegen. |

### Retourwaarde

Somresultaat.

## Zie ook

* Klasse [Nullable](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)