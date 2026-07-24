---
title: LINQ_Min()
second_title: Aspose.Slides für C++ API-Referenz
description: Ruft eine Transformationsfunktion für jedes Element einer generischen Sequenz auf und gibt den kleinsten resultierenden Wert zurück.
type: docs
weight: 339
url: /de/system.collections.generic/ienumerable/linq_min/
---
## IEnumerable::LINQ_Min(const Func\<T, ResultType\>\&) method


Ruft eine Transformationsfunktion für jedes Element einer generischen Sequenz auf und gibt den kleinsten resultierenden Wert zurück.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<T, ResultType> &selector)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| ResultType | Der Typ des von selector zurückgegebenen Wertes. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | Eine Transformationsfunktion, die auf jedes Element angewendet wird. |

### Rückgabewert

Der kleinste Wert in der Sequenz.

## IEnumerable::LINQ_Min(const Func\<Source, ResultType\>\&) method




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<Source, ResultType> &selector)
```

## Siehe auch

* Klasse [Func](../../../system/func/)
* Klasse [IEnumerable](../)
* Namensraum [System::Collections::Generic](../../)
* Bibliothek [Aspose.Slides](../../../)