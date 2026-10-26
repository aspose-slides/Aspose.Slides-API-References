---
title: Array()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří prázdné pole.
type: docs
weight: 1
url: /cs/system/array/array/
---
## Array::Array() konstruktor

Vytvoří prázdné pole.

```cpp
System::Array<T>::Array()
```

## Array::Array(int, const T\&) konstruktor

Konstruktor naplňující.

```cpp
System::Array<T>::Array(int count, const T &init=T())
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| count | int | Počáteční velikost pole |
| init | const T\& | Počáteční hodnota použitá k naplnění pole |

## Array::Array(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<ValueType\>::value\&&std::is_convertible\<ValueType, T\>::value, int\>::type, ValueType) konstruktor

Konstruktor naplňující.

```cpp
template<typename ValueType> System::Array<T>::Array(typename std::enable_if<std::is_arithmetic<T>::value &&std::is_arithmetic<ValueType>::value &&std::is_convertible<ValueType, T>::value, int>::type count, ValueType init)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| ValueType | Typ počáteční hodnoty |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| count | typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<[ValueType](../valuetype/)\>::value\&&std::is_convertible\<[ValueType](../valuetype/), T\>::value, int\>::type | Počáteční velikost pole |
| init | [ValueType](../valuetype/) | Počáteční hodnota použitá k naplnění pole |

## Array::Array(int, const T) konstruktor

Konstruktor naplňující.

```cpp
System::Array<T>::Array(int count, const T inits[])
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| count | int | Počáteční velikost pole |
| inits | const T | Hodnoty k naplnění pole |

## Array::Array(vector_t\&&) konstruktor

Konstruktor přesunu.

```cpp
System::Array<T>::Array(vector_t &&value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | **vector_t**\&& | std::vector, jehož prvky jsou získány polem |

## Array::Array(const vector_t\&) konstruktor

Kopírovací konstruktor.

```cpp
System::Array<T>::Array(const vector_t &assgn)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| assgn | const **vector_t**\& | std::vector, ze kterého se kopírují hodnoty |

## Array::Array(const std::vector\<Q\>\&) konstruktor

Vytvoří objekt [Array](../) a naplní jej hodnotami zkopírovanými z objektu std::vector, jehož typ hodnot je stejný jako **T**, ale odlišný od **UnderlyingType**.

```cpp
template<typename Q,typename> System::Array<T>::Array(const std::vector<Q> &value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Q | Typ prvků objektu std::vector, ze kterého se prvky kopírují |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const std::vector\<Q\>\& | std::vector, ze kterého se kopírují hodnoty |

## Array::Array(std::vector\<Q\>\&&) konstruktor

Vytvoří objekt [Array](../) a naplní jej hodnotami přesunutými z objektu std::vector, jehož typ hodnot je stejný jako **T**, ale odlišný od **UnderlyingType**.

```cpp
template<typename Q,typename> System::Array<T>::Array(std::vector<Q> &&value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Q | Typ prvků objektu std::vector, ze kterého se prvky přesouvají |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | std::vector\<Q\>\&& | std::vector, ze kterého se kopírují hodnoty |

## Array::Array(std::initializer_list\<UnderlyingType\>) konstruktor

Vytvoří objekt [Array](../) a naplní jej hodnotami ze specifikovaného inicializačního seznamu obsahujícího prvky typu **UnderlyingType**.

```cpp
System::Array<T>::Array(std::initializer_list<UnderlyingType> init)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| init | std::initializer_list\<[UnderlyingType](../underlyingtype/)\> | Inicializační seznam obsahující prvky k naplnění pole |

## Array::Array(const std::array\<UnderlyingType, InitArraySize\>\&) konstruktor

Vytvoří objekt [Array](../) a naplní jej hodnotami ze specifikovaného pole obsahujícího prvky typu **UnderlyingType**.

```cpp
template<std::size_t> System::Array<T>::Array(const std::array<UnderlyingType, InitArraySize> &init)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| InitArraySize | Počet prvků pole **init**. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| init | const std::array\<[UnderlyingType](../underlyingtype/), InitArraySize\>\& | [Array](../) k zkopírování do vytvářeného pole. |

## Array::Array(std::initializer_list\<bool\>, int) konstruktor

Vytvoří objekt [Array](../) a naplní jej hodnotami ze specifikovaného inicializačního seznamu obsahujícího prvky typu bool.

```cpp
System::Array<T>::Array(std::initializer_list<bool> init, int=0)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| init | std::initializer_list\<**bool**\> | Inicializační seznam obsahující prvky k naplnění pole |

## Viz také

* Typedef [ValueType](../valuetype/)
* Typedef [UnderlyingType](../underlyingtype/)
* Třída [Array](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)