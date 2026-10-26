---
title: Format()
second_title: Aspose.Slides C++ API referencia
description: Formáz egy stringet C# stílusban.
type: docs
weight: 885
url: /hu/system/string/format/
---
## String::Format(const SharedPtr\<IFormatProvider\>\&, const String\&, const Args\&...) method

Formáz egy stringet C# stílusban.

```cpp
template<class...> String System::String::Format(const SharedPtr<IFormatProvider> &fp, const String &format, const Args &... args)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Args | A string formázásához szükséges argumentumok. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fp | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formázó szolgáltató, amelyet az argumentumok stringgé konvertálásához használunk. |
| format | const [String](../)\& | Formázó string. |
| args | const Args\&... | A string formázásához szükséges argumentumok. |

## String::Format(std::nullptr_t, const String\&, const Args\&...) method

Formáz egy stringet C# stílusban.

```cpp
template<class...> String System::String::Format(std::nullptr_t, const String &format, const Args &... args)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Args | A string formázásához szükséges argumentumok. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| format | std::nullptr_t | Formázó string. |
| args | const [String](../)\& | A string formázásához szükséges argumentumok. |

## String::Format(std::nullptr_t, const char16_t(&), const Args\&...) method

Formáz egy stringet C# stílusban.

```cpp
template<std::size_t,class...> String System::String::Format(std::nullptr_t, const char16_t(&format)[N], const Args &... args)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Args | A string formázásához szükséges argumentumok. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| format | std::nullptr_t | Formázó string. |
| args | const char16_t(&) | A string formázásához szükséges argumentumok. |

## String::Format(const String\&, const Args\&...) method

Formáz egy stringet C# stílusban.

```cpp
template<class...> String System::String::Format(const String &format, const Args &... args)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Args | A string formázásához szükséges argumentumok. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| format | const [String](../)\& | Formázó string. |
| args | const Args\&... | A string formázásához szükséges argumentumok. |

## String::Format(const String\&, const System::ArrayPtr\<T\>\&) method

Formáz egy stringet C# stílusban.

```cpp
template<class T> String System::String::Format(const String &format, const System::ArrayPtr<T> &args)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A string formázásához szükséges argumentumok. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| format | const [String](../)\& | Formázó string. |
| args | const [System::ArrayPtr](../../arrayptr/)\<T\>\& | A string formázásához szükséges argumentumok. |

## Lásd még

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)