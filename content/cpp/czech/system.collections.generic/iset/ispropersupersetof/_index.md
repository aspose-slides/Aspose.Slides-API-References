---
title: IsProperSupersetOf()
second_title: Aspose.Slides pro C++ API Reference
description: Kontroluje, zda je aktuální množina přísnou nadmnožinou kontejneru other.
type: docs
weight: 53
url: /cs/system.collections.generic/iset/ispropersupersetof/
---
## ISet::IsProperSupersetOf(IEnumerablePtr) metoda

Checks if current set is a strict superset of other container.

```cpp
virtual bool System::Collections::Generic::ISet<T>::IsProperSupersetOf(IEnumerablePtr other)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| other | [IEnumerablePtr](../ienumerableptr/) | Podmnožina, proti které se kontroluje. |

### Návratová hodnota

True pokud jsou všechny prvky v **other** přítomny v množině a množina má více prvků než **other**, false jinak.

## Viz také

* Typedef [IEnumerablePtr](../ienumerableptr/)
* Třída [ISet](../)
* Jmenný prostor [System::Collections::Generic](../../)
* Knihovna [Aspose.Slides](../../../)