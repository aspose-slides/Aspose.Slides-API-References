---
title: Equals()
second_title: Aspose.Slides für C++ API-Referenz
description:
type: docs
weight: 14
url: /de/system/objectext/equals/
---
## ObjectExt::Equals(const T\&, const T2\&) Methode

```cpp
template<typename T,typename T2> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```

## ObjectExt::Equals(const T\&, const T2\&) Methode

Ersetzung für C# [Object.Equals](../../object/equals/) Aufrufe, die für jeden Typ in C++ funktionieren. Überladung für Smart-Pointer-Typen.

```cpp
template<typename T,typename T2> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Erster Objekttyp. |
| T2 | Zweiter Objekttyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const T\& | Erstes Objekt. |
| another | const T2\& | Zweites Objekt. |

### Rückgabewert

Wahr, wenn Objekte als gleich angesehen werden, sonst falsch.

## ObjectExt::Equals(T, const T2\&) Methode

Ersetzung für C# [Object.Equals](../../object/equals/) Aufrufe, die für jeden Typ in C++ funktionieren. Überladung für Strukturtypen.

```cpp
template<typename T,typename T2> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(T obj, const T2 &another)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Erster Objekttyp. |
| T2 | Zweiter Objekttyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | T | Erstes Objekt. |
| another | const T2\& | Zweites Objekt. |

### Rückgabewert

Wahr, wenn Objekte als gleich angesehen werden, sonst falsch.

## ObjectExt::Equals(const T\&, const T2\&) Methode

Ersetzung für C# [Object.Equals](../../object/equals/) Aufrufe, die für jeden Typ in C++ funktionieren. Überladung für Skalartypen.

```cpp
template<typename T,typename T2> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Erster Objekttyp. |
| T2 | Zweiter Objekttyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const T\& | Erstes Objekt. |
| another | const T2\& | Zweites Objekt. |

### Rückgabewert

Wahr, wenn Objekte als gleich angesehen werden, sonst falsch.

## ObjectExt::Equals(const char_t(&), String) Methode

Ersetzung für C# [Object.Equals](../../object/equals/) Aufrufe, die für jeden Typ in C++ funktionieren. Überladung für Zeichenkettenliteral mit Zeichenkettenvergleich.

```cpp
template<size_t> static bool System::ObjectExt::Equals(const char_t(&obj)[N], String another)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| N | [String](../../string/) Literalgröße. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const char_t(&) | [String](../../string/) Literal. |
| another | [String](../../string/) | [String](../../string/). |

### Rückgabewert

Wahr, wenn Zeichenketten übereinstimmen, sonst falsch.

## ObjectExt::Equals(const float\&, const float\&) Methode

Emuliert den C#-artigen Vergleich von Gleitkommazahlen, wobei zwei NaNs als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist.

```cpp
bool System::ObjectExt::Equals(const float &obj, const float &another)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const **float**\& | Linker Fließkommawert. |
| another | const **float**\& | Rechter Fließkommawert. |

### Rückgabewert

Wahr, wenn **obj** und **another** beide NaN oder gleich sind, sonst falsch.

## ObjectExt::Equals(const double\&, const double\&) Methode

Emuliert den C#-artigen Vergleich von Gleitkommazahlen, wobei zwei NaNs als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist.

```cpp
bool System::ObjectExt::Equals(const double &obj, const double &another)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const **double**\& | Linker Fließkommawert. |
| another | const **double**\& | Rechter Fließkommawert. |

### Rückgabewert

Wahr, wenn **obj** und **another** beide NaN oder gleich sind, sonst falsch.

## Siehe auch

* Klasse [ObjectExt](../)
* Klasse [String](../../string/)
* Struktur [IsExceptionWrapper](../../isexceptionwrapper/)
* Struktur [IsSmartPtr](../../issmartptr/)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)