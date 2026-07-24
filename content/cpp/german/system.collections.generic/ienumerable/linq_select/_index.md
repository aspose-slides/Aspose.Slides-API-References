---
title: LINQ_Select()
second_title: Aspose.Slides für C++ API-Referenz
description: Wandelt Elemente einer Sequenz um.
type: docs
weight: 248
url: /de/system.collections.generic/ienumerable/linq_select/
---
## IEnumerable::LINQ_Select(const Func\<T, ResultType\>\&) Methode

Wandelt Elemente einer Sequenz um.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, ResultType> &selector)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| ResultType | Der Typ des von der **selector** zurückgegebenen Wertes. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | Eine Transformationsfunktion. |

### Rückgabewert

Ein [IEnumerable](../), das Elemente enthält, die von der **selector**-Funktion zurückgegeben werden.

## IEnumerable::LINQ_Select(const Func\<T, int32_t, ResultType\>\&) Methode

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, int32_t, ResultType> &selector)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| ResultType | Der Typ des von der **selector** zurückgegebenen Wertes. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, **int32_t**, ResultType\>\& | Eine Transformationsfunktion. |

### Rückgabewert

Ein [IEnumerable](../), das Elemente enthält, die von der **selector**-Funktion zurückgegeben werden.

## IEnumerable::LINQ_Select(const Func\<Source, Result\>\&) Methode

```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, Result> &selector)
```

## IEnumerable::LINQ_Select(const Func\<Source, int32_t, Result\>\&) Methode

```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, int32_t, Result> &selector)
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IEnumerable](../)
* Klasse [Func](../../../system/func/)
* Namensraum [System::Collections::Generic](../../)
* Bibliothek [Aspose.Slides](../../../)