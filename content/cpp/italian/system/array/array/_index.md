---
title: Array()
second_title: Aspose.Slides per C++ API Reference
description: Costruisce un array vuoto.
type: docs
weight: 1
url: /it/system/array/array/
---
## Array::Array() costruttore

Costruisce un array vuoto.

```cpp
System::Array<T>::Array()
```

## Array::Array(int, const T\&) costruttore

Costruttore di riempimento.

```cpp
System::Array<T>::Array(int count, const T &init=T())
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| count | int | Dimensione iniziale dell'array |
| init | const T\& | Il valore iniziale utilizzato per riempire l'array |

## Array::Array(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<ValueType\>::value\&&std::is_convertible\<ValueType, T\>::value, int\>::type, ValueType) costruttore

Costruttore di riempimento.

```cpp
template<typename ValueType> System::Array<T>::Array(typename std::enable_if<std::is_arithmetic<T>::value &&std::is_arithmetic<ValueType>::value &&std::is_convertible<ValueType, T>::value, int>::type count, ValueType init)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| ValueType | Tipo del valore iniziale |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| count | typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<[ValueType](../valuetype/)\>::value\&&std::is_convertible\<[ValueType](../valuetype/), T\>::value, int\>::type | Dimensione iniziale dell'array |
| init | [ValueType](../valuetype/) | Il valore iniziale utilizzato per riempire l'array |

## Array::Array(int, const T) costruttore

Costruttore di riempimento.

```cpp
System::Array<T>::Array(int count, const T inits[])
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| count | int | Dimensione iniziale dell'array |
| inits | const T | Valori con cui riempire l'array |

## Array::Array(vector_t\&&) costruttore

Costruttore di spostamento.

```cpp
System::Array<T>::Array(vector_t &&value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | **vector_t**\&& | std::vector, elementi che vengono acquisiti dall'array |

## Array::Array(const vector_t\&) costruttore

Costruttore di copia.

```cpp
System::Array<T>::Array(const vector_t &assgn)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| assgn | const **vector_t**\& | std::vector da cui copiare i valori |

## Array::Array(const std::vector\<Q\>\&) costruttore

Crea un oggetto [Array](../) e lo riempie con i valori copiati da un oggetto std::vector il cui tipo di valori è lo stesso di **T** ma diverso da **UnderlyingType**.

```cpp
template<typename Q,typename> System::Array<T>::Array(const std::vector<Q> &value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Q | Il tipo degli elementi dell'oggetto std::vector da cui copiare gli elementi |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const std::vector\<Q\>\& | std::vector da cui copiare i valori |

## Array::Array(std::vector\<Q\>\&&) costruttore

Crea un oggetto [Array](../) e lo riempie con i valori spostati da un oggetto std::vector il cui tipo di valori è lo stesso di **T** ma diverso da **UnderlyingType**.

```cpp
template<typename Q,typename> System::Array<T>::Array(std::vector<Q> &&value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Q | Il tipo degli elementi dell'oggetto std::vector da cui spostare gli elementi |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | std::vector\<Q\>\&& | std::vector da cui copiare i valori |

## Array::Array(std::initializer_list\<UnderlyingType\>) costruttore

Crea un oggetto [Array](../) e lo riempie con i valori dalla lista di inizializzazione specificata contenente elementi di tipo **UnderlyingType**.

```cpp
System::Array<T>::Array(std::initializer_list<UnderlyingType> init)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| init | std::initializer_list\<[UnderlyingType](../underlyingtype/)\> | Lista di inizializzazione contenente gli elementi con cui riempire l'array |

## Array::Array(const std::array\<UnderlyingType, InitArraySize\>\&) costruttore

Crea un oggetto [Array](../) e lo riempie con i valori dall'array specificato contenente elementi di tipo **UnderlyingType**.

```cpp
template<std::size_t> System::Array<T>::Array(const std::array<UnderlyingType, InitArraySize> &init)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| InitArraySize | Numero di elementi dell'array **init**. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| init | const std::array\<[UnderlyingType](../underlyingtype/), InitArraySize\>\& | [Array](../) da copiare nell'array in costruzione. |

## Array::Array(std::initializer_list\<bool\>, int) costruttore

Crea un oggetto [Array](../) e lo riempie con i valori dalla lista di inizializzazione specificata contenente elementi di tipo bool.

```cpp
System::Array<T>::Array(std::initializer_list<bool> init, int=0)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| init | std::initializer_list\<**bool**\> | Lista di inizializzazione contenente gli elementi con cui riempire l'array |

## Vedi anche

* Typedef [ValueType](../valuetype/)
* Typedef [UnderlyingType](../underlyingtype/)
* Classe [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)