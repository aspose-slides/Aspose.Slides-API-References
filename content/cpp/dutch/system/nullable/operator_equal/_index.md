---
title: operator=()
second_title: Aspose.Slides voor C++ API-referentie
description: Wijs een null toe aan het huidige object.
type: docs
weight: 14
url: /nl/system/nullable/operator_equal/
---
## Nullable::operator=(std::nullptr_t) methode


Wijs een null toe aan het huidige object.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator=(std::nullptr_t)
```


### Retourwaarde

Een [Nullable](../) object dat null-waarde vertegenwoordigt.

## Nullable::operator=(const T1\&) methode


Vervangt de momenteel door het object gerepresenteerde waarde door de opgegeven waarde.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value &&!std::is_null_pointer<T1>::value, Nullable<T> &>::type System::Nullable<T>::operator=(const T1 &x)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| The | Het type van de nieuwe waarde die door het huidige object moet worden gerepresenteerd |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | const T1\& | De nieuwe waarde die door het huidige object moet worden gerepresenteerd |

### Retourwaarde

Een referentie naar zichzelf

## Nullable::operator=(const Nullable\<T1\>\&) methode


Vervangt de momenteel door het object gerepresenteerde waarde door de opgegeven waarde.

```cpp
template<typename T1> Nullable<T> & System::Nullable<T>::operator=(const Nullable<T1> &x)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| The | Het type van de nieuwe waarde die door het huidige object moet worden gerepresenteerd |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | const [Nullable](../)\<T1\>\& | De nieuwe waarde die door het huidige object moet worden gerepresenteerd |

### Retourwaarde

Een referentie naar zichzelf

## Zie ook

* Class [Nullable](../)
* Struct [IsNullable](../../isnullable/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)