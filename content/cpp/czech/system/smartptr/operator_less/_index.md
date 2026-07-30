---
title: operator<()
second_title: Aspose.Slides pro C++ API Reference
description: Poskytuje méně-porovnávací sémantiku pro třídu SmartPtr.
type: docs
weight: 235
url: /cs/system/smartptr/operator_less/
---
## SmartPtr::operator<(Y *) const metoda

Poskytuje méně-porovnávací sémantiku pro třídu [SmartPtr](../).

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(Y *p) const
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Y | Typ ukazatele, se kterým se porovnává aktuální. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| p | Y * | Ukazatel, se kterým se porovnává aktuální. |

### Návratová hodnota

True pokud objekt odkazovaný [SmartPtr](../) je 'méně' než p a false jinak.

## SmartPtr::operator<(SmartPtr\<Y\> const\&) const metoda

Poskytuje méně-porovnávací sémantiku pro třídu [SmartPtr](../).

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(SmartPtr<Y> const &x) const
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Y | Typ ukazatele, se kterým se porovnává aktuální. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | [SmartPtr](../)\<Y\> const\& | Ukazatel, se kterým se porovnává aktuální. |

### Návratová hodnota

True pokud objekt odkazovaný [SmartPtr](../) je 'méně' než x a false jinak.

## Viz také

* Třída [SmartPtr](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)