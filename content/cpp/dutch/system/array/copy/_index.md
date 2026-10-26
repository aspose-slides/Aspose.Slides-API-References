---
title: Copy()
second_title: Aspose.Slides voor C++ API-referentie
description: Kopieert het opgegeven aantal elementen van de bronarray naar de doelarray.
type: docs
weight: 729
url: /nl/system/array/copy/
---
## Array::Copy(const ArrayPtr\<SrcType\>\&, const ArrayPtr\<DstType\>\&, int64_t) methode

Kopieert het opgegeven aantal elementen van de bronarray naar de doelarray.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Bronarray |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Doelarray |
| count | **int64_t** | Het aantal elementen om te kopiëren |

## Array::Copy(System::Details::ArrayView\<SrcType\>, const ArrayPtr\<DstType\>\&, int64_t) methode

Kopieert het opgegeven aantal elementen van de bron-array-view naar de doelarray.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Bronarray-view |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Doelarray |
| count | **int64_t** | Het aantal elementen om te kopiëren |

## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::ArrayView\<DstType\>, int64_t) methode

Kopieert het opgegeven aantal elementen van de bronarray naar de doel-array-view.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Bronarray |
| dstArray | System::Details::ArrayView\<DstType\> | Doelarray-view |
| count | **int64_t** | Het aantal elementen om te kopiëren |

## Array::Copy(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, int64_t) methode

Kopieert het opgegeven aantal elementen van de bron-array-view naar de doel-array-view.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Bronarray-view |
| dstArray | System::Details::ArrayView\<DstType\> | Doelarray-view |
| count | **int64_t** | Het aantal elementen om te kopiëren |

## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, const ArrayPtr\<DstType\>\&, int64_t) methode

Kopieert het opgegeven aantal elementen van de bronarray op de stack naar de doelarray.

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | Bronarray op de stack |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Doelarray |
| count | **int64_t** | Het aantal elementen om te kopiëren |

## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, int64_t) methode

Kopieert het opgegeven aantal elementen van de bronarray naar de doelarray op de stack.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::StackArray<DstType, N> &dstArray, int64_t count)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Bronarray |
| dstArray | System::Details::StackArray\<DstType, N\>\& | Doelarray op de stack |
| count | **int64_t** | Het aantal elementen om te kopiëren |

## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, int64_t) methode

Kopieert het opgegeven aantal elementen van de bronarray op de stack naar de doelarray op de stack.

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, System::Details::StackArray<DstType, ND> &dstArray, int64_t count)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | Bronarray op de stack |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Doelarray op de stack |
| count | **int64_t** | Het aantal elementen om te kopiëren |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) methode

Kopieert een opgegeven aantal elementen van de bronarray beginnend op de opgegeven index naar de opgegeven positie in de doelarray.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| SrcType | Type van elementen in bronarray |
| DstType | Type van elementen in doelarray |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Bronarray |
| srcIndex | **int64_t** | [Index](../../index/) in de bronarray die het begin van het bereik van te kopiëren items aangeeft |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Doelarray |
| dstIndex | **int64_t** | [Index](../../index/) in de doelarray om de gekopieerde items in te voegen |
| count | **int64_t** | Het aantal elementen om te kopiëren |

## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) methode

Kopieert een opgegeven aantal elementen van de bron-array-view beginnend op de opgegeven index naar de opgegeven positie in de doelarray.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| SrcType | Type van elementen in bron-array-view |
| DstType | Type van elementen in doelarray |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Bronarray-view |
| srcIndex | **int64_t** | [Index](../../index/) in de bron-array-view die het begin van het bereik van te kopiëren items aangeeft |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Doelarray |
| dstIndex | **int64_t** | [Index](../../index/) in de doelarray om de gekopieerde items in te voegen |
| count | **int64_t** | Het aantal elementen om te kopiëren |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) methode

Kopieert een opgegeven aantal elementen van de bronarray beginnend op de opgegeven index naar de opgegeven positie in de doel-array-view.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| SrcType | Type van elementen in bronarray |
| DstType | Type van elementen in doel-array-view |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Bronarray |
| srcIndex | **int64_t** | [Index](../../index/) in de bronarray die het begin van het bereik van te kopiëren items aangeeft |
| dstArray | System::Details::ArrayView\<DstType\> | Doel-array-view |
| dstIndex | **int64_t** | [Index](../../index/) in de doel-array-view om de gekopieerde items in te voegen |
| count | **int64_t** | Het aantal elementen om te kopiëren |

## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) methode

Kopieert een opgegeven aantal elementen van de bron-array-view beginnend op de opgegeven index naar de opgegeven positie in de doel-array-view.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| SrcType | Type van elementen in bron-array-view |
| DstType | Type van elementen in doel-array-view |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Bronarray-view |
| srcIndex | **int64_t** | [Index](../../index/) in de bron-array-view die het begin van het bereik van te kopiëren items aangeeft |
| dstArray | System::Details::ArrayView\<DstType\> | Doel-array-view |
| dstIndex | **int64_t** | [Index](../../index/) in de doel-array-view om de gekopieerde items in te voegen |
| count | **int64_t** | Het aantal elementen om te kopiëren |

## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) methode

Kopieert een opgegeven aantal elementen van de bronarray op de stack beginnend op de opgegeven index naar de opgegeven positie in de doelarray.

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| SrcType | Type van elementen in bronarray op de stack |
| DstType | Type van elementen in doelarray |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | Bronarray op de stack |
| srcIndex | **int64_t** | [Index](../../index/) in de bronarray op de stack die het begin van het bereik van te kopiëren items aangeeft |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Doelarray |
| dstIndex | **int64_t** | [Index](../../index/) in de doelarray om de gekopieerde items in te voegen |
| count | **int64_t** | Het aantal elementen om te kopiëren |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, N\>\&, int64_t, int64_t) methode

Kopieert een opgegeven aantal elementen van de bronarray beginnend op de opgegeven index naar de opgegeven positie in de doelarray op de stack.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, N> &dstArray, int64_t dstIndex, int64_t count)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| SrcType | Type van elementen in bronarray |
| DstType | Type van elementen in doelarray op de stack |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Bronarray |
| srcIndex | **int64_t** | [Index](../../index/) in de bronarray die het begin van het bereik van te kopiëren items aangeeft |
| dstArray | System::Details::StackArray\<DstType, N\>\& | Doelarray op de stack |
| dstIndex | **int64_t** | [Index](../../index/) in de doelarray op de stack om de gekopieerde items in te voegen |
| count | **int64_t** | Het aantal elementen om te kopiëren |

## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) methode

Kopieert een opgegeven aantal elementen van de bronarray op de stack beginnend op de opgegeven index naar de opgegeven positie in de doelarray op de stack.

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| SrcType | Type van elementen in bronarray op de stack |
| DstType | Type van elementen in doelarray op de stack |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | Bronarray op de stack |
| srcIndex | **int64_t** | [Index](../../index/) in de bronarray op de stack die het begin van het bereik van te kopiëren items aangeeft |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Doelarray op de stack |
| dstIndex | **int64_t** | [Index](../../index/) in de doelarray op de stack om de gekopieerde items in te voegen |
| count | **int64_t** | Het aantal elementen om te kopiëren |

## Array::Copy(System::Details::ArrayView\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) methode

Kopieert een opgegeven aantal elementen van de bron-array-view beginnend op de opgegeven index naar de opgegeven positie in de doel-array op de stack.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| SrcType | Type van elementen in bronarray op de stack |
| DstType | Type van elementen in doelarray op de stack |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\>\& | Bronarray-view |
| srcIndex | **int64_t** | [Index](../../index/) in de bronarray-view die het begin van het bereik van te kopiëren items aangeeft |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Doelarray op de stack |
| dstIndex | **int64_t** | [Index](../../index/) in de doelarray op de stack om de gekopieerde items in te voegen |
| count | **int64_t** | Het aantal elementen om te kopiëren |

## Zie ook

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)