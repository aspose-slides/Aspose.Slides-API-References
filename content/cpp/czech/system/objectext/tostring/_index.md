---
title: ToString()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Náhrada metody C# ToString pro práci s libovolným typem C++.
type: docs
weight: 27
url: /cs/system/objectext/tostring/
---
## ObjectExt::ToString(const char_t *) metoda

Náhrada metody C# ToString pro práci s libovolným typem C++.

```cpp
static String System::ObjectExt::ToString(const char_t *obj)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const char_t * | [String](../../string/) literál k převodu na řetězec. |

### Návratová hodnota

[String](../../string/) reprezentace **obj**.

## ObjectExt::ToString(const Nullable\<T\>\&) metoda

Náhrada metody C# ToString pro práci s libovolným typem C++.

```cpp
template<typename T> static String System::ObjectExt::ToString(const Nullable<T> &obj)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | [Nullable](../../nullable/) typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const [Nullable](../../nullable/)\<T\>\& | [Nullable](../../nullable/) objekt k převodu na řetězec. |

### Návratová hodnota

[String](../../string/) reprezentace **obj**.

## ObjectExt::ToString(const T\&) metoda

Náhrada metody C# ToString pro práci s libovolným typem C++.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | [Enum](../../enum/) typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const T\& | [Enum](../../enum/) hodnota k převodu na řetězec. |

### Návratová hodnota

[String](../../string/) reprezentace **obj**.

## ObjectExt::ToString(const T\&) metoda

Náhrada metody C# ToString pro práci s libovolným typem C++.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Smart pointer typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const T\& | [SmartPtr](../../smartptr/) hodnota k převodu na řetězec. |

### Návratová hodnota

[String](../../string/) reprezentace **obj**.

## ObjectExt::ToString(T\&) metoda

Náhrada metody C# ToString pro práci s libovolným typem C++.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value||std::is_pointer<T>::value||IsExceptionWrapper<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Smart pointer typ nebo [ExceptionWrapper](../../exceptionwrapper/). |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | T\& | Smart pointer nebo [ExceptionWrapper](../../exceptionwrapper/) k převodu na řetězec. |

### Návratová hodnota

[String](../../string/) reprezentace **obj**.

## ObjectExt::ToString(T\&) metoda

Náhrada metody C# ToString pro práci s libovolným typem C++.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Scalar typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | T\& | Scalar hodnota k převodu na řetězec. |

### Návratová hodnota

[String](../../string/) reprezentace **obj**.

## ObjectExt::ToString(T\&&) metoda

Náhrada metody C# ToString pro práci s libovolným typem C++.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Scalar typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | T\&& | Scalar hodnota k převodu na řetězec. |

### Návratová hodnota

[String](../../string/) reprezentace **obj**.

## ObjectExt::ToString(T\&) metoda

Náhrada metody C# ToString pro práci s libovolným typem C++.

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Structure typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | T\& | Structure hodnota k převodu na řetězec. |

### Návratová hodnota

[String](../../string/) reprezentace **obj**.

## ObjectExt::ToString(const T\&) metoda

Náhrada metody C# ToString pro práci s libovolným typem C++.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Structure typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const T\& | Structure hodnota k převodu na řetězec. |

### Návratová hodnota

[String](../../string/) reprezentace **obj**.

## ObjectExt::ToString(T\&&) metoda

Náhrada metody C# ToString pro práci s libovolným typem C++.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value &&!std::is_reference<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Scalar typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | T\&& | Scalar hodnota k převodu na řetězec. |

### Návratová hodnota

[String](../../string/) reprezentace **obj**.

## Viz také

* Třída [String](../../string/)
* Třída [ObjectExt](../)
* Třída [Nullable](../../nullable/)
* Struktura [IsSmartPtr](../../issmartptr/)
* Struktura [IsExceptionWrapper](../../isexceptionwrapper/)
* Struktura [IsNullable](../../isnullable/)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)