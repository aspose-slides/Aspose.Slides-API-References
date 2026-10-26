---
title: Array()
second_title: Aspose.Slides for C++ API Referansı
description: Boş bir dizi oluşturur.
type: docs
weight: 1
url: /tr/system/array/array/
---
## Array::Array() yapıcı


Boş bir dizi oluşturur.

```cpp
System::Array<T>::Array()
```

## Array::Array(int, const T\&) yapıcı


Doldurma yapıcı.

```cpp
System::Array<T>::Array(int count, const T &init=T())
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| count | int | Dizinin başlangıç boyutu |
| init | const T\& | Diziyi doldurmak için kullanılan başlangıç değeri |

## Array::Array(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<ValueType\>::value\&&std::is_convertible\<ValueType, T\>::value, int\>::type, ValueType) yapıcı


Doldurma yapıcı.

```cpp
template<typename ValueType> System::Array<T>::Array(typename std::enable_if<std::is_arithmetic<T>::value &&std::is_arithmetic<ValueType>::value &&std::is_convertible<ValueType, T>::value, int>::type count, ValueType init)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| ValueType | Başlangıç değerinin türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| count | typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<[ValueType](../valuetype/)\>::value\&&std::is_convertible\<[ValueType](../valuetype/), T\>::value, int\>::type | Dizinin başlangıç boyutu |
| init | [ValueType](../valuetype/) | Diziyi doldurmak için kullanılan başlangıç değeri |

## Array::Array(int, const T) yapıcı


Doldurma yapıcı.

```cpp
System::Array<T>::Array(int count, const T inits[])
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| count | int | Dizinin başlangıç boyutu |
| inits | const T | Diziyi doldurmak için kullanılan değerler |

## Array::Array(vector_t\&&) yapıcı


Taşıma yapıcı.

```cpp
System::Array<T>::Array(vector_t &&value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | **vector_t**\&& | Dizinin edinildiği std::vector öğeleri |

## Array::Array(const vector_t\&) yapıcı


Kopyalama yapıcı.

```cpp
System::Array<T>::Array(const vector_t &assgn)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| assgn | const **vector_t**\& | Değerleri kopyalanacak std::vector |

## Array::Array(const std::vector\<Q\>\&) yapıcı


Bir [Array](../) nesnesi oluşturur ve **T** ile aynı türde ancak **UnderlyingType**'tan farklı bir std::vector nesnesinden kopyalanan değerlerle doldurur.

```cpp
template<typename Q,typename> System::Array<T>::Array(const std::vector<Q> &value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Q | Kopyalanacak std::vector nesnesinin öğelerinin türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const std::vector\<Q\>\& | Değerlerin kopyalanacağı std::vector |

## Array::Array(std::vector\<Q\>\&&) yapıcı


Bir [Array](../) nesnesi oluşturur ve **T** ile aynı türde ancak **UnderlyingType**'tan farklı bir std::vector nesnesinden taşınan değerlerle doldurur.

```cpp
template<typename Q,typename> System::Array<T>::Array(std::vector<Q> &&value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Q | Taşınacak std::vector nesnesinin öğelerinin türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | std::vector\<Q\>\&& | Değerlerin taşınacağı std::vector |

## Array::Array(std::initializer_list\<UnderlyingType\>) yapıcı


Bir [Array](../) nesnesi oluşturur ve **UnderlyingType** öğeleri içeren belirtilen başlatıcı listedeki değerlerle doldurur.

```cpp
System::Array<T>::Array(std::initializer_list<UnderlyingType> init)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| init | std::initializer_list\<[UnderlyingType](../underlyingtype/)\> | Diziyi doldurmak için kullanılan öğeleri içeren başlatıcı liste |

## Array::Array(const std::array\<UnderlyingType, InitArraySize\>\&) yapıcı


Bir [Array](../) nesnesi oluşturur ve **UnderlyingType** öğeleri içeren belirtilen dizi içindeki değerlerle doldurur.

```cpp
template<std::size_t> System::Array<T>::Array(const std::array<UnderlyingType, InitArraySize> &init)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| InitArraySize | **init** dizisinin öğe sayısı. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| init | const std::array\<[UnderlyingType](../underlyingtype/), InitArraySize\>\& | [Array](../) oluşturulan diziye kopyalanır. |

## Array::Array(std::initializer_list\<bool\>, int) yapıcı


Bir [Array](../) nesnesi oluşturur ve bool türündeki öğeleri içeren belirtilen başlatıcı listedeki değerlerle doldurur.

```cpp
System::Array<T>::Array(std::initializer_list<bool> init, int=0)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| init | std::initializer_list\<**bool**\> | Diziyi doldurmak için kullanılan öğeleri içeren başlatıcı liste |

## Bakınız

* Typedef [ValueType](../valuetype/)
* Typedef [UnderlyingType](../underlyingtype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)