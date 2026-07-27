---
title: Array()
second_title: Referência da API Aspose.Slides para C++
description: Constrói um array vazio.
type: docs
weight: 1
url: /pt/system/array/array/
---
## Array::Array() construtor


Constrói um array vazio.

```cpp
System::Array<T>::Array()
```

## Array::Array(int, const T\&) construtor


Construtor de preenchimento.

```cpp
System::Array<T>::Array(int count, const T &init=T())
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| count | int | Tamanho inicial do array |
| init | const T\& | O valor inicial usado para preencher o array |

## Array::Array(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<ValueType\>::value\&&std::is_convertible\<ValueType, T\>::value, int\>::type, ValueType) construtor


Construtor de preenchimento.

```cpp
template<typename ValueType> System::Array<T>::Array(typename std::enable_if<std::is_arithmetic<T>::value &&std::is_arithmetic<ValueType>::value &&std::is_convertible<ValueType, T>::value, int>::type count, ValueType init)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| ValueType | Tipo do valor inicial |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| count | typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<[ValueType](../valuetype/)\>::value\&&std::is_convertible\<[ValueType](../valuetype/), T\>::value, int\>::type | Tamanho inicial do array |
| init | [ValueType](../valuetype/) | O valor inicial usado para preencher o array |

## Array::Array(int, const T) construtor


Construtor de preenchimento.

```cpp
System::Array<T>::Array(int count, const T inits[])
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| count | int | Tamanho inicial do array |
| inits | const T | Valores para preencher o array |

## Array::Array(vector_t\&&) construtor


Construtor de movimentação.

```cpp
System::Array<T>::Array(vector_t &&value)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | **vector_t**\&& | std::vector, cujos elementos são adquiridos pelo array |

## Array::Array(const vector_t\&) construtor


Construtor de cópia.

```cpp
System::Array<T>::Array(const vector_t &assgn)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| assgn | const **vector_t**\& | std::vector de onde copiar os valores |

## Array::Array(const std::vector\<Q\>\&) construtor


Constrói um objeto [Array](../) e preenche-o com valores copiados de um objeto std::vector cujo tipo de valores é o mesmo que **T**, mas diferente de **UnderlyingType**.

```cpp
template<typename Q,typename> System::Array<T>::Array(const std::vector<Q> &value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Q | O tipo dos elementos do objeto std::vector de onde copiar os elementos |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const std::vector\<Q\>\& | std::vector de onde copiar os valores |

## Array::Array(std::vector\<Q\>\&&) construtor


Constrói um objeto [Array](../) e preenche-o com valores movidos de um objeto std::vector cujo tipo de valores é o mesmo que **T**, mas diferente de **UnderlyingType**.

```cpp
template<typename Q,typename> System::Array<T>::Array(std::vector<Q> &&value)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Q | O tipo dos elementos do objeto std::vector de onde mover os elementos |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | std::vector\<Q\>\&& | std::vector de onde copiar os valores |

## Array::Array(std::initializer_list\<UnderlyingType\>) construtor


Constrói um objeto [Array](../) e preenche-o com valores da lista de inicialização especificada contendo elementos do tipo **UnderlyingType**.

```cpp
System::Array<T>::Array(std::initializer_list<UnderlyingType> init)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| init | std::initializer_list\<[UnderlyingType](../underlyingtype/)\> | Lista de inicialização contendo elementos para preencher o array |

## Array::Array(const std::array\<UnderlyingType, InitArraySize\>\&) construtor


Constrói um objeto [Array](../) e preenche-o com valores do array especificado contendo elementos do tipo **UnderlyingType**.

```cpp
template<std::size_t> System::Array<T>::Array(const std::array<UnderlyingType, InitArraySize> &init)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| InitArraySize | Número de elementos do array **init**. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| init | const std::array\<[UnderlyingType](../underlyingtype/), InitArraySize\>\& | [Array](../) para copiar no array que está sendo construído. |

## Array::Array(std::initializer_list\<bool\>, int) construtor


Constrói um objeto [Array](../) e preenche-o com valores da lista de inicialização especificada contendo elementos do tipo bool.

```cpp
System::Array<T>::Array(std::initializer_list<bool> init, int=0)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| init | std::initializer_list\<**bool**\> | Lista de inicialização contendo elementos para preencher o array |

## Veja Também

* Typedef [ValueType](../valuetype/)
* Typedef [UnderlyingType](../underlyingtype/)
* Classe [Array](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)