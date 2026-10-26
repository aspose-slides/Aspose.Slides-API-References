---
title: ToString()
second_title: Aspose.Slides für C++ API-Referenz
description: Ersatz für die C# ToString-Methode, um mit jedem C++-Typ zu arbeiten.
type: docs
weight: 27
url: /de/system/objectext/tostring/
---
## ObjectExt::ToString(const char_t *) Methode

Substitution für die C# ToString-Methode, um mit jedem C++-Typ zu arbeiten.

```cpp
static String System::ObjectExt::ToString(const char_t *obj)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const char_t * | [String](../../string/) Literal, das in eine Zeichenkette umgewandelt werden soll. |

### Rückgabewert

[String](../../string/) Darstellung von **obj**.

## ObjectExt::ToString(const Nullable\<T\>\&) Methode

Substitution für die C# ToString-Methode, um mit jedem C++-Typ zu arbeiten.

```cpp
template<typename T> static String System::ObjectExt::ToString(const Nullable<T> &obj)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | [Nullable](../../nullable/) type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const [Nullable](../../nullable/)\<T\>\& | [Nullable](../../nullable/) Objekt, das in eine Zeichenkette umgewandelt werden soll. |

### Rückgabewert

[String](../../string/) Darstellung von **obj**.

## ObjectExt::ToString(const T\&) Methode

Substitution für die C# ToString-Methode, um mit jedem C++-Typ zu arbeiten.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | [Enum](../../enum/) type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const T\& | [Enum](../../enum/) Wert, der in eine Zeichenkette umgewandelt werden soll. |

### Rückgabewert

[String](../../string/) Darstellung von **obj**.

## ObjectExt::ToString(const T\&) Methode

Substitution für die C# ToString-Methode, um mit jedem C++-Typ zu arbeiten.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Smart pointer type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const T\& | [SmartPtr](../../smartptr/) Wert, der in eine Zeichenkette umgewandelt werden soll. |

### Rückgabewert

[String](../../string/) Darstellung von **obj**.

## ObjectExt::ToString(T\&) Methode

Substitution für die C# ToString-Methode, um mit jedem C++-Typ zu arbeiten.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value||std::is_pointer<T>::value||IsExceptionWrapper<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Smart pointer type or [ExceptionWrapper](../../exceptionwrapper/). |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | T\& | Smart pointer oder [ExceptionWrapper](../../exceptionwrapper/) zum Konvertieren in eine Zeichenkette. |

### Rückgabewert

[String](../../string/) Darstellung von **obj**.

## ObjectExt::ToString(T\&) Methode

Substitution für die C# ToString-Methode, um mit jedem C++-Typ zu arbeiten.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Scalar type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | T\& | Skalarwert, der in eine Zeichenkette umgewandelt werden soll. |

### Rückgabewert

[String](../../string/) Darstellung von **obj**.

## ObjectExt::ToString(T\&&) Methode

Substitution für die C# ToString-Methode, um mit jedem C++-Typ zu arbeiten.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Scalar type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | T\&& | Skalarwert, der in eine Zeichenkette umgewandelt werden soll. |

### Rückgabewert

[String](../../string/) Darstellung von **obj**.

## ObjectExt::ToString(T\&) Methode

Substitution für die C# ToString-Methode, um mit jedem C++-Typ zu arbeiten.

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Structure type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | T\& | Strukturwert, der in eine Zeichenkette umgewandelt werden soll. |

### Rückgabewert

[String](../../string/) Darstellung von **obj**.

## ObjectExt::ToString(const T\&) Methode

Substitution für die C# ToString-Methode, um mit jedem C++-Typ zu arbeiten.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Structure type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const T\& | Strukturwert, der in eine Zeichenkette umgewandelt werden soll. |

### Rückgabewert

[String](../../string/) Darstellung von **obj**.

## ObjectExt::ToString(T\&&) Methode

Substitution für die C# ToString-Methode, um mit jedem C++-Typ zu arbeiten.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value &&!std::is_reference<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Scalar type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | T\&& | Skalarwert, der in eine Zeichenkette umgewandelt werden soll. |

### Rückgabewert

[String](../../string/) Darstellung von **obj**.

## Siehe auch

* Klasse [String](../../string/)
* Klasse [ObjectExt](../)
* Klasse [Nullable](../../nullable/)
* Struktur [IsSmartPtr](../../issmartptr/)
* Struktur [IsExceptionWrapper](../../isexceptionwrapper/)
* Struktur [IsNullable](../../isnullable/)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)