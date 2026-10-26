---
title: PrintToStringImpl()
second_title: Aspose.Slides für C++ API Referenz
description: "Gibt die Unterklasse System::Object als Zeichenkette aus, indem die ToString()-Methode verwendet wird."
type: docs
weight: 14
url: /de/system.testpredicates.details/printtostringimpl/
---
## System::TestPredicates::Details::PrintToStringImpl(const SharedPtr\<T\>\&, long long) Funktion

Gibt die Unterklasse [System::Object](../../system/object/) als Zeichenkette aus, indem die ToString()-Methode verwendet wird.

```cpp
template<typename T> std::enable_if<System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const SharedPtr<T> &value, long long s)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Final class type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [SharedPtr](../../system/sharedptr/)\<T\>\& | Pointer to object to print. |
| s | long long | A service parameter which serves as a selector of function overload based on the type of this parameter; the value of the parameter is ignored |

### Rückgabewert

[String](../../system/string/) Darstellung des übergebenen Objekts oder \"nullptr\", falls **value** null ist.

## System::TestPredicates::Details::PrintToStringImpl(const WeakPtr\<T\>\&, long long) Funktion

Gibt die Unterklasse [System::Object](../../system/object/) als Zeichenkette aus, indem die ToString()-Methode verwendet wird.

```cpp
template<typename T> std::enable_if<System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const WeakPtr<T> &value, long long s)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Final class type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [WeakPtr](../../system/weakptr/)\<T\>\& | Pointer to object to print. |
| s | long long | A service parameter which serves as a selector of function overload based on the type of this parameter; the value of the parameter is ignored |

### Rückgabewert

[String](../../system/string/) Darstellung des übergebenen Objekts oder \"nullptr\", falls **value** null ist.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) Funktion

Gibt das Objekt als Zeichenkette aus, indem die ToString()-Methode verwendet wird.

```cpp
template<typename T> std::enable_if<!TypeTraits::has_print_to_method<T>::value &&System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) to print. |
| s | long long | A service parameter which serves as a selector of function overload based on the type of this parameter; the value of the parameter is ignored |

### Rückgabewert

[String](../../system/string/) Darstellung des übergebenen Objekts.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) Funktion

Gibt das Objekt als Zeichenkette aus, indem die PrintTo-Methode verwendet wird.

```cpp
template<typename T> std::enable_if<TypeTraits::has_print_to_method<T>::value &&!TypeTraits::IsEnumerable<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) to print. |
| s | long long | A service parameter which serves as a selector of function overload based on the type of this parameter; the value of the parameter is ignored |

### Rückgabewert

[String](../../system/string/) Darstellung des übergebenen Objekts.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) Funktion

Gibt das Objekt als Zeichenkette aus, indem die PrintTo-Methode verwendet wird.

```cpp
template<typename T> std::enable_if<TypeTraits::has_print_to_method<T>::value &&TypeTraits::IsEnumerable<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) to print. |
| s | long long | A service parameter which serves as a selector of function overload based on the type of this parameter; the value of the parameter is ignored |

### Rückgabewert

[String](../../system/string/) Darstellung des übergebenen Objekts.

## System::TestPredicates::Details::PrintToStringImpl(const std::pair\<T1, T2\>\&, long long) Funktion

Gibt das Paar als Zeichenkette aus.

```cpp
template<typename T1,typename T2> std::string System::TestPredicates::Details::PrintToStringImpl(const std::pair<T1, T2> &value, long long s)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | First pair type argument. |
| T2 | Second pair type argument. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const std::pair\<T1, T2\>\& | [Object](../../system/object/) to print. |
| s | long long | A service parameter which serves as a selector of function overload based on the type of this parameter; the value of the parameter is ignored |

### Rückgabewert

Gemeinsame Zeichenkettenrepräsentationen von erster und zweiter Paar-Komponente.

## System::TestPredicates::Details::PrintToStringImpl(const Collections::Generic::KeyValuePair\<T1, T2\>\&, long long) Funktion

Gibt das Paar als Zeichenkette aus.

```cpp
template<typename T1,typename T2> std::string System::TestPredicates::Details::PrintToStringImpl(const Collections::Generic::KeyValuePair<T1, T2> &value, long long s)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | First pair type argument. |
| T2 | Second pair type argument. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<T1, T2\>\& | [Object](../../system/object/) to print. |
| s | long long | A service parameter which serves as a selector of function overload based on the type of this parameter; the value of the parameter is ignored |

### Rückgabewert

Gemeinsame Zeichenkettenrepräsentationen von erster und zweiter Paar-Komponente.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) Funktion

Gibt STL-ähnliche Container als Zeichenkette aus, indem deren Elemente (nicht mehr als 32) ausgegeben werden.

```cpp
template<typename T> std::enable_if<TypeTraits::IsCppContainer<T>::value &&!std::is_base_of<Object, T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &container, long long s)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| container | const T\& | [Object](../../system/object/) to print. |
| s | long long | A service parameter which serves as a selector of function overload based on the type of this parameter; the value of the parameter is ignored |

### Rückgabewert

Gemeinsame Zeichenkettenrepräsentationen der enthaltenen Elemente.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, int) Funktion

Gibt andere Typen als Zeichenkette aus, indem gtest-bereitgestellte Funktionen verwendet werden.

```cpp
template<typename T> std::string System::TestPredicates::Details::PrintToStringImpl(const T &value, int s)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) to print. |
| s | int | A service parameter which serves as a selector of function overload based on the type of this parameter; the value of the parameter is ignored |

### Rückgabewert

[String](../../system/string/) Darstellungen des übergebenen Objekts.

## Siehe auch

* Typedef [SharedPtr](../../system/sharedptr/)
* Klasse [WeakPtr](../../system/weakptr/)
* Klasse [KeyValuePair](../../system.collections.generic/keyvaluepair/)
* Klasse [Object](../../system/object/)
* Struktur [has_print_to_method](../../system.testpredicates.typetraits/has_print_to_method/)
* Struktur [IsEnumerable](../../system.testpredicates.typetraits/isenumerable/)
* Struktur [IsCppContainer](../../system.testpredicates.typetraits/iscppcontainer/)
* Namensraum [System::TestPredicates::Details](../)
* Bibliothek [Aspose.Slides](../../)