---
title: operator<()
second_title: Aspose.Slides für C++ API Referenz
description: Stellt die Vergleichssemantik „weniger“ für die SmartPtr-Klasse bereit.
type: docs
weight: 235
url: /de/system/smartptr/operator_less/
---
## SmartPtr::operator<(Y *) const method


Stellt die Vergleichssemantik „weniger“ für die Klasse [SmartPtr](../) bereit.

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(Y *p) const
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Y | Typ des Zeigers, mit dem der aktuelle verglichen wird. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| p | Y * | Zeiger, mit dem der aktuelle verglichen wird. |

### Rückgabewert

Wahr, wenn das von [SmartPtr](../) referenzierte Objekt „weniger“ als p ist, andernfalls falsch.

## SmartPtr::operator<(SmartPtr\<Y\> const\&) const method


Stellt die Vergleichssemantik „weniger“ für die Klasse [SmartPtr](../) bereit.

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(SmartPtr<Y> const &x) const
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Y | Typ des Zeigers, mit dem der aktuelle verglichen wird. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | [SmartPtr](../)\<Y\> const\& | Zeiger, mit dem der aktuelle verglichen wird. |

### Rückgabewert

Wahr, wenn das von [SmartPtr](../) referenzierte Objekt „weniger“ als x ist, andernfalls falsch.

## Siehe auch

* Klasse [SmartPtr](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)