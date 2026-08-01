---
title: CopyTo()
second_title: Aspose.Slides voor C++ API-referentie
description: Kopieert alle elementen van de huidige array naar de opgegeven doel-array. Elementen worden in de doel-array ingevoegd beginnend bij de index die wordt opgegeven door het argument arrayIndex.
type: docs
weight: 118
url: /nl/system/array/copyto/
---
## Array::CopyTo(ArrayPtr\<T\>, int) methode


Kopieert alle elementen van de huidige array naar de opgegeven doel-array. Elementen worden in de doel-array ingevoegd beginnend bij de index die wordt opgegeven door het argument arrayIndex.

```cpp
virtual void System::Array<T>::CopyTo(ArrayPtr<T> arr, int arrayIndex) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arr | [ArrayPtr](../../arrayptr/)\<T\> | Doel-array |
| arrayIndex | int | [Index](../../index/) in destination array om te beginnen met het invoegen van gekopieerde items |

## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t) const methode


Kopieert alle elementen van de huidige array naar de opgegeven doel-array. Elementen worden in de doel-array ingevoegd beginnend bij de index die wordt opgegeven door het argument dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t dstIndex) const
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| DstType | Type van elementen in de doel-array |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Doel-array |
| dstIndex | **int64_t** | [Index](../../index/) in destination array om te beginnen met het invoegen van gekopieerde items |

## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t) const methode


Kopieert alle elementen van de huidige array naar de opgegeven doel-array-view. Elementen worden in de doel-array-view ingevoegd beginnend bij de index die wordt opgegeven door het argument dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t dstIndex) const
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| DstType | Type van elementen in de doel-array-view |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | Doel-array-view |
| dstIndex | **int64_t** | [Index](../../index/) in destination array view om te beginnen met het invoegen van gekopieerde items |

## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t, int64_t, int64_t) const methode


Kopieert een opgegeven aantal elementen van de huidige array, beginnend op een opgegeven positie, naar de opgegeven doel-array. Elementen worden in de doel-array ingevoegd beginnend bij de index die wordt opgegeven door het argument dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| DstType | Type van elementen in de doel-array |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Doel-array |
| srcIndex | **int64_t** | [Index](../../index/) in source array om te beginnen met het kopiëren van items |
| dstIndex | **int64_t** | [Index](../../index/) in destination array om te beginnen met het invoegen van gekopieerde items |
| count | **int64_t** | Aantal te kopiëren elementen |

## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t, int64_t, int64_t) const methode


Kopieert een opgegeven aantal elementen van de huidige array, beginnend op een opgegeven positie, naar de opgegeven doel-array-view. Elementen worden in de doel-array-view ingevoegd beginnend bij de index die wordt opgegeven door het argument dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| DstType | Type van elementen in de doel-array-view |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | Doel-array-view |
| srcIndex | **int64_t** | [Index](../../index/) in source array om te beginnen met het kopiëren van items |
| dstIndex | **int64_t** | [Index](../../index/) in destination array view om te beginnen met het invoegen van gekopieerde items |
| count | **int64_t** | Aantal te kopiëren elementen |

## Zie ook

* Typedef [ArrayPtr](../../arrayptr/)
* Klasse [Array](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)