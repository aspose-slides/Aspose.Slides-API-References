---
title: PrintToString()
second_title: Aspose.Slides C++ API referencia
description: Az objektumot karakterláncra írja ki a megfelelő sorosító függvény kiválasztásával.
type: docs
weight: 1
url: /hu/system.testpredicates.details/printtostring/
---
## System::TestPredicates::Details::PrintToString(const T&) függvény


Az objektumot karakterláncra írja ki a megfelelő sorosító függvény kiválasztásával.

```cpp
template<typename T> std::enable_if_t<!TypeTraits::IsEnumerable<T>::value, std::string> System::TestPredicates::Details::PrintToString(const T &value)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | [Object](../../system/object/) típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) nyomtatandó. |

### Visszatérési érték

[String](../../system/string/) reprezentációk a átadott objektumról.

## System::TestPredicates::Details::PrintToString(const T&) függvény


Az ICollection-stílusú konténereket karakterláncra írja ki az elemeik (legfeljebb 32) nyomtatásával.

```cpp
template<typename T> std::enable_if_t<TypeTraits::IsEnumerable<T>::value, std::string> System::TestPredicates::Details::PrintToString(const T &value)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | [Object](../../system/object/) típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) nyomtatandó. |

### Visszatérési érték

Az elemek összefűzött karakterlánc ábrázolása.

## System::TestPredicates::Details::PrintToString(std::nullptr_t) függvény


A nullptr-et karakterláncra írja.

```cpp
std::string System::TestPredicates::Details::PrintToString(std::nullptr_t)
```


### Visszatérési érték

"nullptr" karakterlánc.

## System::TestPredicates::Details::PrintToString(const Collections::Generic::IEnumerable\<bool\>\&) függvény


A [IEnumerable<bool>](../../system.collections.generic/ienumerable/) gyűjteményeket karakterláncra írja ki az elemeik (legfeljebb 32) nyomtatásával.

```cpp
std::string System::TestPredicates::Details::PrintToString(const Collections::Generic::IEnumerable<bool> &value)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | [Object](../../system/object/) típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<**bool**\>\& | [Object](../../system/object/) nyomtatandó. |

### Visszatérési érték

Az elemek összefűzött karakterlánc ábrázolása.

## Lásd még

* Osztály [IEnumerable](../../system.collections.generic/ienumerable/)
* Struktúra [IsEnumerable](../../system.testpredicates.typetraits/isenumerable/)
* Névtere [System::TestPredicates::Details](../)
* Könyvtár [Aspose.Slides](../../)