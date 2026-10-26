---
title: LINQ_SelectMany()
second_title: Aspose.Slides für C++ API Referenz
description: Projektiert jedes Element einer Sequenz und kombiniert die resultierenden Sequenzen zu einer einzigen Sequenz.
type: docs
weight: 300
url: /de/system.collections.generic/ienumerable/linq_selectmany/
---
## IEnumerable::LINQ_SelectMany(const Func\<T, SharedPtr\<IEnumerable\<ResultType\>\>\>\&) Methode


Projektiert jedes Element einer Sequenz und kombiniert die resultierenden Sequenzen zu einer einzigen Sequenz.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<T, SharedPtr<IEnumerable<ResultType>>> &selector)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| ResultType | Der Typ des von dem **selector** zurückgegebenen Wertes. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, [SharedPtr](../../../system/sharedptr/)\<[IEnumerable](../)\<ResultType\>\>\>\& | Eine Transformationsfunktion. |

### Rückgabewert

Ein [IEnumerable](../) der das Ergebnis des Aufrufs einer Eins-zu-Viele-Projektionsfunktion für jedes Element der Eingabesequenz enthält.

## IEnumerable::LINQ_SelectMany(const Func\<Source, SharedPtr\<IEnumerable\<Result\>\>\>\&) Methode




```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<Source, SharedPtr<IEnumerable<Result>>> &selector)
```

## Siehe auch

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klasse [IEnumerable](../)
* Klasse [Func](../../../system/func/)
* Namensraum [System::Collections::Generic](../../)
* Bibliothek [Aspose.Slides](../../../)