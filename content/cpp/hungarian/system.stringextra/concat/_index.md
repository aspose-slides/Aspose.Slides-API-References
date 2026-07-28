---
title: Concat()
second_title: Aspose.Slides C++ API referenciája
description: Összefűzi a karakterlánc tömböt.
type: docs
weight: 1
url: /hu/system.stringextra/concat/
---
## System::StringExtra::Concat(const ArrayPtr\<String\>\&) függvény


Összefűzi a karakterlánc tömböt.

```cpp
String System::StringExtra::Concat(const ArrayPtr<String> &parts)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| parts | const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\& | [Array](../../system/array/) a csatlakoztatandó karakterláncok. |

### Visszatérési érték

Összefűzött karakterlánc.

## System::StringExtra::Concat(const String\&, const String\&) függvény


Összefűzi a karakterláncokat.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | Az első összefűzendő karakterlánc. |
| str1 | const [String](../../system/string/)\& | A második összefűzendő karakterlánc. |

### Visszatérési érték

Összefűzött paraméterkarakterláncok.

## System::StringExtra::Concat(const String\&, const String\&, const String\&) függvény


Összefűzi a karakterláncokat.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1, const String &str2)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | Az első összefűzendő karakterlánc. |
| str1 | const [String](../../system/string/)\& | A második összefűzendő karakterlánc. |
| str2 | const [String](../../system/string/)\& | A harmadik összefűzendő karakterlánc. |

### Visszatérési érték

Összefűzött paraméterkarakterláncok.

## System::StringExtra::Concat(const String\&, const String\&, const String\&, const String\&) függvény


Összefűzi a karakterláncokat.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1, const String &str2, const String &str3)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | Az első összefűzendő karakterlánc. |
| str1 | const [String](../../system/string/)\& | A második összefűzendő karakterlánc. |
| str2 | const [String](../../system/string/)\& | A harmadik összefűzendő karakterlánc. |
| str3 | const [String](../../system/string/)\& | A negyedik összefűzendő karakterlánc. |

### Visszatérési érték

Összefűzött paraméterkarakterláncok.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) függvény


Átalakít több objektumot karakterlánccá, és összefűzi a kapott karakterláncokat. Specializáció a [SmartPtr](../../system/smartptr/) típusokra.

```cpp
template<typename T> std::enable_if_t<IsSmartPtr<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) átalakításra és összefűzésre. |

### Visszatérési érték

[String](../../system/string/) érték összefűzve az összes átadott objektum karakterlánc-ábrázolásából.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) függvény


Átalakít több objektumot karakterlánccá, és összefűzi a kapott karakterláncokat. Specializáció aritmetikus típusokra.

```cpp
template<typename T> std::enable_if_t<std::is_arithmetic<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) átalakításra és összefűzésre. |

### Visszatérési érték

[String](../../system/string/) érték összefűzve az összes átadott objektum karakterlánc-ábrázolásából.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) függvény


Átalakít több objektumot karakterlánccá, és összefűzi a kapott karakterláncokat. Specializáció struktúrákra és egyéb értéktípusokra.

```cpp
template<typename T> std::enable_if_t<!IsSmartPtr<T>::value &&!std::is_arithmetic<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) átalakításra és összefűzésre. |

### Visszatérési érték

[String](../../system/string/) érték összefűzve az összes átadott objektum karakterlánc-ábrázolásából.

## Lásd még

* Typedef [ArrayPtr](../../system/arrayptr/)
* Osztály [String](../../system/string/)
* Struktúra [IsSmartPtr](../../system/issmartptr/)
* Névtér [System::StringExtra](../)
* Könyvtár [Aspose.Slides](../../)