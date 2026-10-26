---
title: PrintToString()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Wypisuje obiekt jako ciąg znaków, wybierając odpowiednią funkcję serializacji.
type: docs
weight: 1
url: /pl/system.testpredicates.details/printtostring/
---
## System::TestPredicates::Details::PrintToString(const T\&) function


Wypisuje obiekt jako ciąg znaków, wybierając odpowiednią funkcję serializacji.

```cpp
template<typename T> std::enable_if_t<!TypeTraits::IsEnumerable<T>::value, std::string> System::TestPredicates::Details::PrintToString(const T &value)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | [Object](../../system/object/) typ. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) do wypisania. |

### Wartość zwracana

[String](../../system/string/) reprezentacje przekazanego obiektu.

## System::TestPredicates::Details::PrintToString(const T\&) function


Wypisuje kontenery w stylu ICollection jako ciąg znaków, wypisując ich elementy (nie więcej niż 32).

```cpp
template<typename T> std::enable_if_t<TypeTraits::IsEnumerable<T>::value, std::string> System::TestPredicates::Details::PrintToString(const T &value)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | [Object](../../system/object/) typ. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) do wypisania. |

### Wartość zwracana

Połączone reprezentacje ciągów znaków zawartych elementów.

## System::TestPredicates::Details::PrintToString(std::nullptr_t) function


Wypisuje nullptr jako ciąg znaków.

```cpp
std::string System::TestPredicates::Details::PrintToString(std::nullptr_t)
```


### Wartość zwracana

"nullptr" ciąg znaków.

## System::TestPredicates::Details::PrintToString(const Collections::Generic::IEnumerable\<bool\>\&) function


Wypisuje kolekcje [IEnumerable<bool>](../../system.collections.generic/ienumerable/) jako ciąg znaków, wypisując ich elementy (nie więcej niż 32).

```cpp
std::string System::TestPredicates::Details::PrintToString(const Collections::Generic::IEnumerable<bool> &value)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | [Object](../../system/object/) typ. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<**bool**\>\& | [Object](../../system/object/) do wypisania. |

### Wartość zwracana

Połączone reprezentacje ciągów znaków zawartych elementów.

## Zobacz także

* Klasa [IEnumerable](../../system.collections.generic/ienumerable/)
* Struktura [IsEnumerable](../../system.testpredicates.typetraits/isenumerable/)
* Przestrzeń nazw [System::TestPredicates::Details](../)
* Biblioteka [Aspose.Slides](../../)