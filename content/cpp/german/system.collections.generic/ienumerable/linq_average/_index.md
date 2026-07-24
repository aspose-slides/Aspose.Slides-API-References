---
title: LINQ_Average()
second_title: Aspose.Slides für C++ API Referenz
description: Berechnet den Durchschnitt einer Sequenz numerischer Werte.
type: docs
weight: 365
url: /de/system.collections.generic/ienumerable/linq_average/
---
## IEnumerable::LINQ_Average() Methode


Berechnet den Durchschnitt einer Sequenz numerischer Werte.

```cpp
Source System::Collections::Generic::IEnumerable<Source>::LINQ_Average()
```


### Rückgabewert

Der Durchschnitt der Werte in der Sequenz.

## IEnumerable::LINQ_Average(const Func\<T, ResultType\>\&) Methode


Berechnet den Durchschnitt einer Sequenz von Werten, die durch Aufrufen einer Transformationsfunktion für jedes Element der Eingabesequenz erhalten werden.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Average(const Func<T, ResultType> &selector)
```


### Template-Parameter
| Parameter | Description |
| --- | --- |
| ResultType | Der Typ des von selector zurückgegebenen Werts. |

### Argumente
| Parameter | Type | Description |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | Eine Transformationsfunktion, die auf jedes Element angewendet wird. |

### Rückgabewert
Der Durchschnitt der projizierten Werte.

## IEnumerable::LINQ_Average(const Func\<Source, ResultType\>\&) Methode




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Average(const Func<Source, ResultType> &selector)
```

## Siehe auch
* Klasse [IEnumerable](../)
* Klasse [Func](../../../system/func/)
* Namensraum [System::Collections::Generic](../../)
* Bibliothek [Aspose.Slides](../../../)