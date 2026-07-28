---
title: operator+()
second_title: Aspose.Slides for C++ API-referencia
description: Visszaad egy új Decimal osztálypéldányt, amely egy olyan értéket képvisel, amely a megadott érték és a megadott Decimal objektum által képviselt érték összege.
type: docs
weight: 2185
url: /hu/system/operator_plus/
---
## System::operator+(const T\&, const Decimal\&) függvény


Visszaad egy új [Decimal](../decimal/) osztálypéldányt, amely egy olyan értéket képvisel, amely a megadott érték és a megadott [Decimal](../decimal/) objektum által képviselt érték összege.

```cpp
template<typename T,typename _> Decimal System::operator+(const T &x, const Decimal &d)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | const T\& | Az első összeadó |
| d | const [Decimal](../decimal/)\& | A konstans referencia a [Decimal](../decimal/) objektumra, amely a második összeadót képviseli |

### Visszatérési érték

Egy új [Decimal](../decimal/) osztálypéldány, amely egy olyan értéket képvisel, amely **x** és **d** által képviselt érték összege.

## System::operator+(MulticastDelegate\<T\>, MulticastDelegate\<T\>) függvény


Összekapcsolja a jobb oldali delegate összes visszahívását a bal oldali delegate visszahívási listájának végére.

```cpp
template<typename T> MulticastDelegate<T> System::operator+(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | A delegate, amelyhez a visszahívásokat hozzáadják. |
| rhv | MulticastDelegate\<T\> | Az a delegate, amelynek visszahívásait hozzáadják. |

### Visszatérési érték

Visszaad egy delegát, amely tartalmazza a bal oldali érték visszahívásait, majd a jobb oldaliakat.

## System::operator+(const T1\&, const Nullable\<T2\>\&) függvény


Összeadja a nullable és nem nullable értékeket.

```cpp
template<typename T1,typename T2,typename> auto System::operator+(const T1 &some, const Nullable<T2> &other) -> System::Nullable<decltype(some+other.get_Value())>
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | Bal operandus típusa. |
| T2 | Jobb operandus típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| some | const T1\& | Bal operandus. |
| other | const [Nullable](../nullable/)\<T2\>\& | Jobb operandus. |

### Visszatérési érték

Összegzés eredménye.

## System::operator+(T\&, const String\&) függvény


[String](../string/) összefűzés.

```cpp
template<typename T> std::enable_if<IsStringLiteral<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | [String](../string/) literális típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| left | T\& | Literal to concatenate to string. |
| right | const [String](../string/)\& | [String](../string/) a fűzéshez. |

### Visszatérési érték

Összefűzött karakterlánc.

## System::operator+(T\&, const String\&) függvény


[String](../string/) összefűzés.

```cpp
template<typename T> std::enable_if<IsStringPointer<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | [String](../string/) mutató típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| left | T\& | [String](../string/) mutató a stringhez fűzve. |
| right | const [String](../string/)\& | [String](../string/) a fűzéshez. |

### Visszatérési érték

Összefűzött karakterlánc.

## System::operator+(const char_t, const String\&) függvény


[String](../string/) összefűzés.

```cpp
String System::operator+(const char_t left, const String &right)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| left | const char_t | A karakter, amelyet a stringhez fűznek. |
| right | const [String](../string/)\& | [String](../string/) a fűzéshez. |

### Visszatérési érték

Összefűzött karakterlánc.

## Lásd még

* Osztály [Decimal](../decimal/)
* Osztály [Nullable](../nullable/)
* Osztály [String](../string/)
* Struktúra [IsStringLiteral](../isstringliteral/)
* Struktúra [IsStringPointer](../isstringpointer/)
* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)