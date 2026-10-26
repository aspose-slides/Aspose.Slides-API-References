---
title: ComparerAdapter
second_title: Aspose.Slides für C++ API Referenz
description: Adapter zur Verwendung von IComparer in einer STL-Umgebung. Verwendet IComparer, falls gesetzt; andernfalls wird operator < (falls verfügbar) verwendet oder false zurückgegeben (falls nicht).
type: docs
weight: 638
url: /de/system.collections.generic/compareradapter/
---
## ComparerAdapter struct

Adapter zur Verwendung von [IComparer](../icomparer/) in einer STL-Umgebung. Verwendet [IComparer](../icomparer/), falls gesetzt; andernfalls wird operator < (falls verfügbar) verwendet oder false zurückgegeben (falls nicht verfügbar).

```cpp
template<class T>class ComparerAdapter
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Zu vergleichender Typ. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  [ComparerAdapter](./compareradapter/)() | Konstruktor für Adapter ohne verfügbaren Comparator. |
|  [ComparerAdapter](./compareradapter/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | Konstruktor für Adapter. |
| std::enable_if\<detail::has_operator_less\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [Comparison](../../system/comparison/) Funktion für Typen mit verfügbarem operator <. |
| std::enable_if<\!detail::has_operator_less\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [Comparison](../../system/comparison/) Funktion für Typen ohne operator <. |
| void [set_Comparator](./set_comparator/)(const [SharedPtr](../../system/sharedptr/)\<[IComparer](../icomparer/)\<T\>\>\&) | Setzt Comparator-Objekt. |

## Siehe auch

* Namespace [System::Collections::Generic](../)
* Library [Aspose.Slides](../../)