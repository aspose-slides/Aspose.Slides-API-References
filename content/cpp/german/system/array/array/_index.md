---
title: Array()
second_title: Aspose.Slides für C++ API Referenz
description: Konstruiert ein leeres Array.
type: docs
weight: 1
url: /de/system/array/array/
---
## Array::Array() Konstruktor


Konstruiert ein leeres Array.

```cpp
System::Array<T>::Array()
```

## Array::Array(int, const T\&) Konstruktor


Füllender Konstruktor.

```cpp
System::Array<T>::Array(int count, const T &init=T())
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| count | int | Initiale Größe des Arrays |
| init | const T\& | Der anfängliche Wert, der zum Befüllen des Arrays verwendet wird |

## Array::Array(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<ValueType\>::value\&&std::is_convertible\<ValueType, T\>::value, int\>::type, ValueType) Konstruktor


Füllender Konstruktor.

```cpp
template<typename ValueType> System::Array<T>::Array(typename std::enable_if<std::is_arithmetic<T>::value &&std::is_arithmetic<ValueType>::value &&std::is_convertible<ValueType, T>::value, int>::type count, ValueType init)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| ValueType | Typ des Anfangswerts |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| count | typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<[ValueType](../valuetype/)\>::value\&&std::is_convertible\<[ValueType](../valuetype/), T\>::value, int\>::type | Initiale Größe des Arrays |
| init | [ValueType](../valuetype/) | Der anfängliche Wert, der zum Befüllen des Arrays verwendet wird |

## Array::Array(int, const T) Konstruktor


Füllender Konstruktor.

```cpp
System::Array<T>::Array(int count, const T inits[])
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| count | int | Initiale Größe des Arrays |
| inits | const T | Werte, mit denen das Array befüllt wird |

## Array::Array(vector_t\&&) Konstruktor


Move-Konstruktor.

```cpp
System::Array<T>::Array(vector_t &&value)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | **vector_t**\&& | std::vector, dessen Elemente vom Array übernommen werden |

## Array::Array(const vector_t\&) Konstruktor


Copy-Konstruktor.

```cpp
System::Array<T>::Array(const vector_t &assgn)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| assgn | const **vector_t**\& | std::vector, aus dem die Werte kopiert werden |

## Array::Array(const std::vector\<Q\>\&) Konstruktor


Konstruiert ein [Array](../)-Objekt und füllt es mit Werten, die aus einem std::vector-Objekt kopiert wurden, dessen Werttyp derselbe wie **T** ist, aber von **UnderlyingType** abweicht.

```cpp
template<typename Q,typename> System::Array<T>::Array(const std::vector<Q> &value)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Q | Der Typ der Elemente des std::vector-Objekts, aus dem die Elemente kopiert werden |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const std::vector\<Q\>\& | std::vector, aus dem die Werte kopiert werden |

## Array::Array(std::vector\<Q\>\&&) Konstruktor


Konstruiert ein [Array](../)-Objekt und füllt es mit Werten, die aus einem std::vector-Objekt verschoben wurden, dessen Werttyp derselbe wie **T** ist, aber von **UnderlyingType** abweicht.

```cpp
template<typename Q,typename> System::Array<T>::Array(std::vector<Q> &&value)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Q | Der Typ der Elemente des std::vector-Objekts, aus dem die Elemente verschoben werden |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | std::vector\<Q\>\&& | std::vector, aus dem die Werte verschoben werden |

## Array::Array(std::initializer_list\<UnderlyingType\>) Konstruktor


Konstruiert ein [Array](../)-Objekt und füllt es mit Werten aus der angegebenen Initialisierungsliste, die Elemente des Typs **UnderlyingType** enthält.

```cpp
System::Array<T>::Array(std::initializer_list<UnderlyingType> init)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| init | std::initializer_list\<[UnderlyingType](../underlyingtype/)\> | Initialisierungsliste, die die Elemente zum Befüllen des Arrays enthält |

## Array::Array(const std::array\<UnderlyingType, InitArraySize\>\&) Konstruktor


Konstruiert ein [Array](../)-Objekt und füllt es mit Werten aus dem angegebenen Array, das Elemente des Typs **UnderlyingType** enthält.

```cpp
template<std::size_t> System::Array<T>::Array(const std::array<UnderlyingType, InitArraySize> &init)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| InitArraySize | Anzahl der Elemente des **init**-Arrays. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| init | const std::array\<[UnderlyingType](../underlyingtype/), InitArraySize\>\& | [Array](../) zum Kopieren in das zu konstruierende Array. |

## Array::Array(std::initializer_list\<bool\>, int) Konstruktor


Konstruiert ein [Array](../)-Objekt und füllt es mit Werten aus der angegebenen Initialisierungsliste, die Elemente des Typs bool enthält.

```cpp
System::Array<T>::Array(std::initializer_list<bool> init, int=0)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| init | std::initializer_list\<**bool**\> | Initialisierungsliste, die die Elemente zum Befüllen des Arrays enthält |

## Siehe auch

* Typedef [ValueType](../valuetype/)
* Typedef [UnderlyingType](../underlyingtype/)
* Klasse [Array](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)