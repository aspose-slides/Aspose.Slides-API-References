---
title: Cast()
second_title: Aspose.Slides för C++ API-referens
description: Kastar pekare till dess egen typ.
type: docs
weight: 287
url: /sv/system/smartptr/cast/
---
## SmartPtr::Cast() const metod


Kastar pekare till dess egen typ.

```cpp
template<class Y,typename Check> std::enable_if_t<std::is_same<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Y | Måltyp för pekat objekt. |
| Check | Flaggor för att kasta undantag om ingen kast är tillgänglig. |

### Returvärde

Pekare av ändrad typ som alltid är i delat läge.

## SmartPtr::Cast() const metod


Kastar pekare till basklass med static_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<!std::is_same<Y, T>::value &&std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Y | Måltyp för pekat objekt. |
| Check | Flaggor för att kasta undantag om ingen kast är tillgänglig. |

### Returvärde

Pekare av ändrad typ som alltid är i delat läge.

## SmartPtr::Cast() const metod


Kastar pekare till en avledd typ med dynamic_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Y | Måltyp för pekat objekt. |
| Check | Flaggor för att kasta undantag om ingen kast är tillgänglig. |

### Returvärde

Pekare av ändrad typ som alltid är i delat läge. Kastar InvalidCastException om ingen konvertering är tillgänglig.

## SmartPtr::Cast() const metod


Kastar pekare till en avledd typ med dynamic_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<!Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Y | Måltyp för pekat objekt. |
| Check | Flaggor för att kasta undantag om ingen kast är tillgänglig. |

### Returvärde

Pekare av ändrad typ som alltid är i delat läge. Returnerar nullptr om ingen konvertering är tillgänglig.

## Se även

* Klass [SmartPtr](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)