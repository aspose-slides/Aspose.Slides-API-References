---
title: Equals()
second_title: Aspose.Slides dla C++ – odniesienie API
description: 
type: docs
weight: 14
url: /pl/system/objectext/equals/
---
## ObjectExt::Equals(const T\&, const T2\&) metoda




```cpp
template<typename T,typename T2> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```

## ObjectExt::Equals(const T\&, const T2\&) metoda


Podstawienie dla wywołań C# [Object.Equals](../../object/equals/) działających dla dowolnego typu w C++. Przeciążenie dla typów inteligentnych wskaźników.

```cpp
template<typename T,typename T2> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ pierwszego obiektu. |
| T2 | Typ drugiego obiektu. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const T\& | Pierwszy obiekt. |
| another | const T2\& | Drugi obiekt. |

### Wartość zwracana

Zwraca true, jeśli obiekty są uznane za równe, w przeciwnym razie false.

## ObjectExt::Equals(T, const T2\&) metoda


Podstawienie dla wywołań C# [Object.Equals](../../object/equals/) działających dla dowolnego typu w C++. Przeciążenie dla typów strukturalnych.

```cpp
template<typename T,typename T2> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(T obj, const T2 &another)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ pierwszego obiektu. |
| T2 | Typ drugiego obiektu. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | T | Pierwszy obiekt. |
| another | const T2\& | Drugi obiekt. |

### Wartość zwracana

Zwraca true, jeśli obiekty są uznane za równe, w przeciwnym razie false.

## ObjectExt::Equals(const T\&, const T2\&) metoda


Podstawienie dla wywołań C# [Object.Equals](../../object/equals/) działających dla dowolnego typu w C++. Przeciążenie dla typów skalarnych.

```cpp
template<typename T,typename T2> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ pierwszego obiektu. |
| T2 | Typ drugiego obiektu. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const T\& | Pierwszy obiekt. |
| another | const T2\& | Drugi obiekt. |

### Wartość zwracana

Zwraca true, jeśli obiekty są uznane za równe, w przeciwnym razie false.

## ObjectExt::Equals(const char_t(&), String) metoda


Podstawienie dla wywołań C# [Object.Equals](../../object/equals/) działających dla dowolnego typu w C++. Przeciążenie dla literału znakowego z porównaniem ciągów.

```cpp
template<size_t> static bool System::ObjectExt::Equals(const char_t(&obj)[N], String another)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| N | [String](../../string/) rozmiar literału. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const char_t(&) | [String](../../string/) literał. |
| another | [String](../../string/) | [String](../../string/). |

### Wartość zwracana

Zwraca true, jeśli obiekty są uznane za równe, w przeciwnym razie false.

## ObjectExt::Equals(const float\&, const float\&) metoda


Emuluje porównanie zmiennoprzecinkowe w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równe żadnej wartości, włącznie z NaN.

```cpp
bool System::ObjectExt::Equals(const float &obj, const float &another)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const **float**\& | Wartość zmiennoprzecinkowa LHS. |
| another | const **float**\& | Wartość zmiennoprzecinkowa RHS. |

### Wartość zwracana

Zwraca true, jeśli **obj** i **another** są oba NaN lub równe, w przeciwnym razie false.

## ObjectExt::Equals(const double\&, const double\&) metoda


Emuluje porównanie zmiennoprzecinkowe w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równe żadnej wartości, włącznie z NaN.

```cpp
bool System::ObjectExt::Equals(const double &obj, const double &another)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const **double**\& | Wartość zmiennoprzecinkowa LHS. |
| another | const **double**\& | Wartość zmiennoprzecinkowa RHS. |

### Wartość zwracana

Zwraca true, jeśli **obj** i **another** są oba NaN lub równe, w przeciwnym razie false.

## Zobacz także

* Klasa [ObjectExt](../)
* Klasa [String](../../string/)
* Struktura [IsExceptionWrapper](../../isexceptionwrapper/)
* Struktura [IsSmartPtr](../../issmartptr/)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)