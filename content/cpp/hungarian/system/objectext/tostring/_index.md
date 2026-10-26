---
title: ToString()
second_title: Aspose.Slides C++ API referencia
description: A C# ToString metódus helyettesítője, amely bármely C++ típuson működik.
type: docs
weight: 27
url: /hu/system/objectext/tostring/
---
## ObjectExt::ToString(const char_t *) metódus

A C# ToString metódus helyettesítője, amely bármely C++ típuson működik.

```cpp
static String System::ObjectExt::ToString(const char_t *obj)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const char_t * | [String](../../string/) literál a stringgé konvertáláshoz. |

### Visszatérési érték

[String](../../string/) reprezentációja a **obj**-nak.

## ObjectExt::ToString(const Nullable\<T\>\&) metódus

A C# ToString metódus helyettesítője, amely bármely C++ típuson működik.

```cpp
template<typename T> static String System::ObjectExt::ToString(const Nullable<T> &obj)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | [Nullable](../../nullable/) típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const [Nullable](../../nullable/)\<T\>\& | [Nullable](../../nullable/) objektum a stringgé konvertáláshoz. |

### Visszatérési érték

[String](../../string/) reprezentációja a **obj**-nak.

## ObjectExt::ToString(const T\&) metódus

A C# ToString metódus helyettesítője, amely bármely C++ típuson működik.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | [Enum](../../enum/) típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const T\& | [Enum](../../enum/) érték a stringgé konvertáláshoz. |

### Visszatérési érték

[String](../../string/) reprezentációja a **obj**-nak.

## ObjectExt::ToString(const T\&) metódus

A C# ToString metódus helyettesítője, amely bármely C++ típuson működik.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Smart pointer típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const T\& | [SmartPtr](../../smartptr/) érték a stringgé konvertáláshoz. |

### Visszatérési érték

[String](../../string/) reprezentációja a **obj**-nak.

## ObjectExt::ToString(T\&) metódus

A C# ToString metódus helyettesítője, amely bármely C++ típuson működik.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value||std::is_pointer<T>::value||IsExceptionWrapper<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Smart pointer típus vagy [ExceptionWrapper](../../exceptionwrapper/). |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | T\& | Smart pointer vagy [ExceptionWrapper](../../exceptionwrapper/) a stringgé konvertáláshoz. |

### Visszatérési érték

[String](../../string/) reprezentációja a **obj**-nak.

## ObjectExt::ToString(T\&) metódus

A C# ToString metódus helyettesítője, amely bármely C++ típuson működik.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Skalár típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | T\& | Skalár érték a stringgé konvertáláshoz. |

### Visszatérési érték

[String](../../string/) reprezentációja a **obj**-nak.

## ObjectExt::ToString(T\&&) metódus

A C# ToString metódus helyettesítője, amely bármely C++ típuson működik.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Skalár típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | T\&& | Skalár érték a stringgé konvertáláshoz. |

### Visszatérési érték

[String](../../string/) reprezentációja a **obj**-nak.

## ObjectExt::ToString(T\&) metódus

A C# ToString metódus helyettesítője, amely bármely C++ típuson működik.

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Struktúra típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | T\& | Struktúra érték a stringgé konvertáláshoz. |

### Visszatérési érték

[String](../../string/) reprezentációja a **obj**-nak.

## ObjectExt::ToString(const T\&) metódus

A C# ToString metódus helyettesítője, amely bármely C++ típuson működik.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Struktúra típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const T\& | Struktúra érték a stringgé konvertáláshoz. |

### Visszatérési érték

[String](../../string/) reprezentációja a **obj**-nak.

## ObjectExt::ToString(T\&&) metódus

A C# ToString metódus helyettesítője, amely bármely C++ típuson működik.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value &&!std::is_reference<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Skalár típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | T\&& | Skalár érték a stringgé konvertáláshoz. |

### Visszatérési érték

[String](../../string/) reprezentációja a **obj**-nak.

## Lásd még

* Osztály [String](../../string/)
* Osztály [ObjectExt](../)
* Osztály [Nullable](../../nullable/)
* Struktúra [IsSmartPtr](../../issmartptr/)
* Struktúra [IsExceptionWrapper](../../isexceptionwrapper/)
* Struktúra [IsNullable](../../isnullable/)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)