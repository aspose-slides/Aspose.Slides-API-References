---
title: CopyTo()
second_title: Aspose.Slides für C++ API-Referenz
description: Kopiert alle Elemente des aktuellen Array in das angegebene Ziel-Array. Die Elemente werden in das Ziel-Array eingefügt, beginnend mit dem durch das Argument arrayIndex angegebenen Index.
type: docs
weight: 118
url: /de/system/array/copyto/
---
## Array::CopyTo(ArrayPtr\<T\>, int) Methode

Kopiert alle Elemente des aktuellen Arrays in das angegebene Ziel-Array. Die Elemente werden in das Ziel-Array eingefügt, beginnend mit dem durch das Argument arrayIndex angegebenen Index.

```cpp
virtual void System::Array<T>::CopyTo(ArrayPtr<T> arr, int arrayIndex) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arr | [ArrayPtr](../../arrayptr/)\<T\> | Ziel-Array |
| arrayIndex | int | [Index](../../index/) im Ziel-Array, um das Einfügen der kopierten Elemente zu beginnen |

## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t) const Methode

Kopiert alle Elemente des aktuellen Arrays in das angegebene Ziel-Array. Die Elemente werden in das Ziel-Array eingefügt, beginnend mit dem durch das Argument dstIndex angegebenen Index.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t dstIndex) const
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| DstType | Typ der Elemente im Ziel-Array |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Ziel-Array |
| dstIndex | **int64_t** | [Index](../../index/) im Ziel-Array, um das Einfügen der kopierten Elemente zu beginnen |

## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t) const Methode

Kopiert alle Elemente des aktuellen Arrays in die angegebene Ziel-Array-Ansicht. Die Elemente werden in die Ziel-Array-Ansicht eingefügt, beginnend mit dem durch das Argument dstIndex angegebenen Index.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t dstIndex) const
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| DstType | Typ der Elemente in der Ziel-Array-Ansicht |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | Ziel-Array-Ansicht |
| dstIndex | **int64_t** | [Index](../../index/) in der Ziel-Array-Ansicht, um das Einfügen der kopierten Elemente zu beginnen |

## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t, int64_t, int64_t) const Methode

Kopiert eine bestimmte Anzahl von Elementen des aktuellen Arrays, beginnend an einer angegebenen Position, in das angegebene Ziel-Array. Die Elemente werden in das Ziel-Array eingefügt, beginnend mit dem durch das Argument dstIndex angegebenen Index.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| DstType | Typ der Elemente im Ziel-Array |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Ziel-Array |
| srcIndex | **int64_t** | [Index](../../index/) im Quell-Array, um das Kopieren der Elemente zu beginnen |
| dstIndex | **int64_t** | [Index](../../index/) im Ziel-Array, um das Einfügen der kopierten Elemente zu beginnen |
| count | **int64_t** | Anzahl der zu kopierenden Elemente |

## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t, int64_t, int64_t) const Methode

Kopiert eine bestimmte Anzahl von Elementen des aktuellen Arrays, beginnend an einer angegebenen Position, in die angegebene Ziel-Array-Ansicht. Die Elemente werden in die Ziel-Array-Ansicht eingefügt, beginnend mit dem durch das Argument dstIndex angegebenen Index.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| DstType | Typ der Elemente in der Ziel-Array-Ansicht |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | Ziel-Array-Ansicht |
| srcIndex | **int64_t** | [Index](../../index/) im Quell-Array, um das Kopieren der Elemente zu beginnen |
| dstIndex | **int64_t** | [Index](../../index/) in der Ziel-Array-Ansicht, um das Einfügen der kopierten Elemente zu beginnen |
| count | **int64_t** | Anzahl der zu kopierenden Elemente |

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Klasse [Array](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)