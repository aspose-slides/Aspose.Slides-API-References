---
title: Equals()
second_title: Aspose.Slides C++ API referencia
description: 
type: docs
weight: 14
url: /hu/system/objectext/equals/
---
## ObjectExt::Equals(const T\&, const T2\&) metódus




```cpp
template<typename T,typename T2> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```

## ObjectExt::Equals(const T\&, const T2\&) metódus


C# [Object.Equals](../../object/equals/) hívások helyettesítése, amely bármely típusra működik C++-ban. Túlterhelés okos mutató típusokhoz.

```cpp
template<typename T,typename T2> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Az első objektum típusa. |
| T2 | A második objektum típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const T\& | Az első objektum. |
| another | const T2\& | A második objektum. |

### Visszatérési érték

Igaz, ha az objektumok egyenlőnek tekinthetők, egyébként hamis.

## ObjectExt::Equals(T, const T2\&) metódus


C# [Object.Equals](../../object/equals/) hívások helyettesítése, amely bármely típusra működik C++-ban. Túlterhelés struktúratípusokhoz.

```cpp
template<typename T,typename T2> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(T obj, const T2 &another)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Az első objektum típusa. |
| T2 | A második objektum típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | T | Az első objektum. |
| another | const T2\& | A második objektum. |

### Visszatérési érték

Igaz, ha az objektumok egyenlőnek tekinthetők, egyébként hamis.

## ObjectExt::Equals(const T\&, const T2\&) metódus


C# [Object.Equals](../../object/equals/) hívások helyettesítése, amely bármely típusra működik C++-ban. Túlterhelés skalár típusokhoz.

```cpp
template<typename T,typename T2> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Az első objektum típusa. |
| T2 | A második objektum típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const T\& | Az első objektum. |
| another | const T2\& | A második objektum. |

### Visszatérési érték

Igaz, ha az objektumok egyenlőnek tekinthetők, egyébként hamis.

## ObjectExt::Equals(const char_t(&), String) metódus


C# [Object.Equals](../../object/equals/) hívások helyettesítése, amely bármely típusra működik C++-ban. Túlterhelés karakterlánc literál és string összehasonlítás esetén.

```cpp
template<size_t> static bool System::ObjectExt::Equals(const char_t(&obj)[N], String another)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| N | [String](../../string/) literál mérete. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const char_t(&) | [String](../../string/) literál. |
| another | [String](../../string/) | [String](../../string/). |

### Visszatérési érték

Igaz, ha a karakterláncok megegyeznek, egyébként hamis.

## ObjectExt::Equals(const float\&, const float\&) metódus


C#-stílusú lebegőpontos összehasonlítás, ahol két NaN is egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is.

```cpp
bool System::ObjectExt::Equals(const float &obj, const float &another)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const **float**\& | Bal oldalú lebegőpontos érték. |
| another | const **float**\& | Jobb oldalú lebegőpontos érték. |

### Visszatérési érték

Igaz, ha **obj** és **another** egyaránt NaN vagy egyenlő, egyébként hamis.

## ObjectExt::Equals(const double\&, const double\&) metódus


C#-stílusú lebegőpontos összehasonlítás, ahol két NaN is egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is.

```cpp
bool System::ObjectExt::Equals(const double &obj, const double &another)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const **double**\& | Bal oldalú lebegőpontos érték. |
| another | const **double**\& | Jobb oldalú lebegőpontos érték. |

### Visszatérési érték

Igaz, ha **obj** és **another** egyaránt NaN vagy egyenlő, egyébként hamis.

## Lásd még

* Osztály [ObjectExt](../)
* Osztály [String](../../string/)
* Struktúra [IsExceptionWrapper](../../isexceptionwrapper/)
* Struktúra [IsSmartPtr](../../issmartptr/)
* Névterület [System](../../)
* Könyvtár [Aspose.Slides](../../../)