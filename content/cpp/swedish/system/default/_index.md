---
title: Default()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar en referens till den enda standardkonstruerade instansen av undantagstypen.
type: docs
weight: 2224
url: /sv/system/default/
---
## System::Default() funktion


Returnerar en referens till den enda standardkonstruerade instansen av undantagstypen.

```cpp
template<typename T> std::enable_if<IsExceptionWrapper<T>::value, constT &>::type System::Default()
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen vars instans returneras |

## System::Default() funktion


Returnerar en referens till den enda standardkonstruerade instansen av den icke-undantagstypen.

```cpp
template<typename T> std::enable_if<!IsExceptionWrapper<T>::value, constT &>::type System::Default()
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen vars instans returneras |

## Se även

* Struct [IsExceptionWrapper](../isexceptionwrapper/)
* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)