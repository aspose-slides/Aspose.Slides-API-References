---
title: operator<()
second_title: Aspose.Slides for C++ API hivatkozás
description: Kevesebb-összehasonlítási szemantikai viselkedést biztosít a SmartPtr osztály számára.
type: docs
weight: 235
url: /hu/system/smartptr/operator_less/
---
## SmartPtr::operator<(Y *) const method

Kevesebb-összehasonlítási szemantikai viselkedést biztosít a [SmartPtr](../) osztály számára.

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(Y *p) const
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| Y | A pointer típusa, amelyhez az aktuális összehasonlítandó. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| p | Y * | A pointer, amelyhez az aktuális összehasonlítandó. |

### Visszatérési érték

Igaz, ha a [SmartPtr](../) által hivatkozott objektum 'kevesebb', mint p, egyébként hamis.

## SmartPtr::operator<(SmartPtr\<Y\> const\&) const method

Kevesebb-összehasonlítási szemantikai viselkedést biztosít a [SmartPtr](../) osztály számára.

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(SmartPtr<Y> const &x) const
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| Y | A pointer típusa, amelyhez az aktuális összehasonlítandó. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | [SmartPtr](../)\<Y\> const\& | A pointer, amelyhez az aktuális összehasonlítandó. |

### Visszatérési érték

Igaz, ha a [SmartPtr](../) által hivatkozott objektum 'kevesebb', mint x, egyébként hamis.

## Lásd még

* Osztály [SmartPtr](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)