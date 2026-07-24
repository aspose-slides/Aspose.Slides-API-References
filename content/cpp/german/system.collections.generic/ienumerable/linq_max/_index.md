---
title: LINQ_Max()
second_title: Aspose.Slides für C++ API Referenz
description: Ruft eine Transformationsfunktion für jedes Element einer generischen Sequenz auf und gibt den maximalen resultierenden Wert zurück.
type: docs
weight: 352
url: /de/system.collections.generic/ienumerable/linq_max/
---
## IEnumerable::LINQ_Max(const Func\<T, ResultType\>\&) Methode

Ruft eine Transformationsfunktion für jedes Element einer generischen Sequenz auf und gibt den maximalen resultierenden Wert zurück.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<T, ResultType> &selector)
```

### Vorlagenparameter

| Parameter | Beschreibung |
| --- | --- |
| ResultType | Der Typ des von selector zurückgegebenen Werts. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | Eine Transformationsfunktion, die auf jedes Element angewendet wird. |

### Rückgabewert

Der maximale Wert in der Sequenz.

## IEnumerable::LINQ_Max(const Func\<Source, ResultType\>\&) Methode




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<Source, ResultType> &selector)
```

## Siehe auch

* Klasse [Func](../../../system/func/)
* Klasse [IEnumerable](../)
* Namensraum [System::Collections::Generic](../../)
* Bibliothek [Aspose.Slides](../../../)