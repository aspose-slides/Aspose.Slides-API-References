---
title: ToString()
second_title: Aspose.Slides för C++ API-referens
description: Ersättning för C# ToString-metoden för att fungera på alla C++-typer.
type: docs
weight: 27
url: /sv/system/objectext/tostring/
---
## ObjectExt::ToString(const char_t *) metod

Ersättning för C# ToString-metoden för att fungera på alla C++-typer.

```cpp
static String System::ObjectExt::ToString(const char_t *obj)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const char_t * | [String](../../string/) literal för att konvertera till sträng. |

### Returvärde

[String](../../string/) representation av **obj**.

## ObjectExt::ToString(const Nullable\<T\>\&) metod

Ersättning för C# ToString-metoden för att fungera på alla C++-typer.

```cpp
template<typename T> static String System::ObjectExt::ToString(const Nullable<T> &obj)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | [Nullable](../../nullable/) typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const [Nullable](../../nullable/)\<T\>\& | [Nullable](../../nullable/) objekt för att konvertera till sträng. |

### Returvärde

[String](../../string/) representation av **obj**.

## ObjectExt::ToString(const T\&) metod

Ersättning för C# ToString-metoden för att fungera på alla C++-typer.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | [Enum](../../enum/) typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const T\& | [Enum](../../enum/) värde för att konvertera till sträng. |

### Returvärde

[String](../../string/) representation av **obj**.

## ObjectExt::ToString(const T\&) metod

Ersättning för C# ToString-metoden för att fungera på alla C++-typer.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Smart-pekartyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const T\& | [SmartPtr](../../smartptr/) värde för att konvertera till sträng. |

### Returvärde

[String](../../string/) representation av **obj**.

## ObjectExt::ToString(T\&) metod

Ersättning för C# ToString-metoden för att fungera på alla C++-typer.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value||std::is_pointer<T>::value||IsExceptionWrapper<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Smart-pekartyp eller [ExceptionWrapper](../../exceptionwrapper/). |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | T\& | Smart-pekare eller [ExceptionWrapper](../../exceptionwrapper/) för att konvertera till sträng. |

### Returvärde

[String](../../string/) representation av **obj**.

## ObjectExt::ToString(T\&) metod

Ersättning för C# ToString-metoden för att fungera på alla C++-typer.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Skalär typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | T\& | Skalärt värde för att konvertera till sträng. |

### Returvärde

[String](../../string/) representation av **obj**.

## ObjectExt::ToString(T\&&) metod

Ersättning för C# ToString-metoden för att fungera på alla C++-typer.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Skalär typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | T\&& | Skalärt värde för att konvertera till sträng. |

### Returvärde

[String](../../string/) representation av **obj**.

## ObjectExt::ToString(T\&) metod

Ersättning för C# ToString-metoden för att fungera på alla C++-typer.

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Strukturtyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | T\& | Strukturvärde för att konvertera till sträng. |

### Returvärde

[String](../../string/) representation av **obj**.

## ObjectExt::ToString(const T\&) metod

Ersättning för C# ToString-metoden för att fungera på alla C++-typer.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Strukturtyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const T\& | Strukturvärde för att konvertera till sträng. |

### Returvärde

[String](../../string/) representation av **obj**.

## ObjectExt::ToString(T\&&) metod

Ersättning för C# ToString-metoden för att fungera på alla C++-typer.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value &&!std::is_reference<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Skalär typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | T\&& | Skalärt värde för att konvertera till sträng. |

### Returvärde

[String](../../string/) representation av **obj**.

## Se också

* Klass [String](../../string/)
* Klass [ObjectExt](../)
* Klass [Nullable](../../nullable/)
* Struktur [IsSmartPtr](../../issmartptr/)
* Struktur [IsExceptionWrapper](../../isexceptionwrapper/)
* Struktur [IsNullable](../../isnullable/)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)