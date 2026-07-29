---
title: PrintToString()
second_title: Aspose.Slides för C++ API-referens
description: Skriver ut objekt till sträng genom att välja rätt serialiseringsfunktion.
type: docs
weight: 1
url: /sv/system.testpredicates.details/printtostring/
---
## System::TestPredicates::Details::PrintToString(const T&) funktion


Skriver ut objekt till sträng genom att välja rätt serialiseringsfunktion.

```cpp
template<typename T> std::enable_if_t<!TypeTraits::IsEnumerable<T>::value, std::string> System::TestPredicates::Details::PrintToString(const T &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | [Object](../../system/object/) typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const T& | [Object](../../system/object/) att skriva ut. |

### Returvärde

[String](../../system/string/) representationer av det överförda objektet.

## System::TestPredicates::Details::PrintToString(const T&) funktion


Skriver ut ICollection-liknande behållare till sträng genom att skriva ut deras element (max 32).

```cpp
template<typename T> std::enable_if_t<TypeTraits::IsEnumerable<T>::value, std::string> System::TestPredicates::Details::PrintToString(const T &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | [Object](../../system/object/) typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const T& | [Object](../../system/object/) att skriva ut. |

### Returvärde

Sammanfogade strängrepresentationer av innehållna element.

## System::TestPredicates::Details::PrintToString(std::nullptr_t) funktion


Skriver ut nullptr till sträng.

```cpp
std::string System::TestPredicates::Details::PrintToString(std::nullptr_t)
```


### Returvärde

"nullptr" sträng.

## System::TestPredicates::Details::PrintToString(const Collections::Generic::IEnumerable\<bool\>&) funktion


Skriver ut [IEnumerable<bool>](../../system.collections.generic/ienumerable/) samlingar till sträng genom att skriva ut deras element (max 32).

```cpp
std::string System::TestPredicates::Details::PrintToString(const Collections::Generic::IEnumerable<bool> &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | [Object](../../system/object/) typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)<**bool**>& | [Object](../../system/object/) att skriva ut. |

### Returvärde

Sammanfogade strängrepresentationer av innehållna element.

## Se även

* Klass [IEnumerable](../../system.collections.generic/ienumerable/)
* Struktur [IsEnumerable](../../system.testpredicates.typetraits/isenumerable/)
* Namnrymd [System::TestPredicates::Details](../)
* Bibliotek [Aspose.Slides](../../)