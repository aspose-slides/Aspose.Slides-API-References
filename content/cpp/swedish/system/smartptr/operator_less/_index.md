---
title: operator<()
second_title: Aspose.Slides för C++ API-referens
description: Tillhandahåller mindre-jämförelsesemantik för SmartPtr-klass.
type: docs
weight: 235
url: /sv/system/smartptr/operator_less/
---
## SmartPtr::operator<(Y *) const metod


Tillhandahåller mindre-jämförelsesemantik för [SmartPtr](../) klass.

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(Y *p) const
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Y | Typ av pekare att jämföra den aktuella med. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| p | Y * | Pekare att jämföra den aktuella med. |

### Returvärde

Sant om objektet som refereras av [SmartPtr](../) är 'less' än p och falskt annars.

## SmartPtr::operator<(SmartPtr\<Y\> const\&) const metod


Tillhandahåller mindre-jämförelsesemantik för [SmartPtr](../) klass.

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(SmartPtr<Y> const &x) const
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Y | Typ av pekare att jämföra den aktuella med. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | [SmartPtr](../)\<Y\> const\& | Pekare att jämföra den aktuella med. |

### Returvärde

Sant om objektet som refereras av [SmartPtr](../) är 'less' än x och falskt annars.

## Se även

* Klass [SmartPtr](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)