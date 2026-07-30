---
title: Format()
second_title: Aspose.Slides pro referenci API C++
description: Formátuje řetězec ve stylu C#.
type: docs
weight: 885
url: /cs/system/string/format/
---
## String::Format(const SharedPtr\<IFormatProvider\>\&, const String\&, const Args\&...) metoda

Formátuje řetězec ve stylu C#.

```cpp
template<class...> String System::String::Format(const SharedPtr<IFormatProvider> &fp, const String &format, const Args &... args)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Args | Argumenty pro formátování řetězce. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| fp | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Poskytovatel formátu, který se použije k převodu argumentů na řetězce. |
| format | const [String](../)\& | Formátovací řetězec. |
| args | const Args\&... | Argumenty pro formátování řetězce. |

## String::Format(std::nullptr_t, const String\&, const Args\&...) metoda

Formátuje řetězec ve stylu C#.

```cpp
template<class...> String System::String::Format(std::nullptr_t, const String &format, const Args &... args)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Args | Argumenty pro formátování řetězce. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| format | std::nullptr_t | Formátovací řetězec. |
| args | const [String](../)\& | Argumenty pro formátování řetězce. |

## String::Format(std::nullptr_t, const char16_t(&), const Args\&...) metoda

Formátuje řetězec ve stylu C#.

```cpp
template<std::size_t,class...> String System::String::Format(std::nullptr_t, const char16_t(&format)[N], const Args &... args)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Args | Argumenty pro formátování řetězce. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| format | std::nullptr_t | Formátovací řetězec. |
| args | const char16_t(&) | Argumenty pro formátování řetězce. |

## String::Format(const String\&, const Args\&...) metoda

Formátuje řetězec ve stylu C#.

```cpp
template<class...> String System::String::Format(const String &format, const Args &... args)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Args | Argumenty pro formátování řetězce. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| format | const [String](../)\& | Formátovací řetězec. |
| args | const Args\&... | Argumenty pro formátování řetězce. |

## String::Format(const String\&, const System::ArrayPtr\<T\>\&) metoda

Formátuje řetězec ve stylu C#.

```cpp
template<class T> String System::String::Format(const String &format, const System::ArrayPtr<T> &args)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Argumenty pro formátování řetězce. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| format | const [String](../)\& | Formátovací řetězec. |
| args | const [System::ArrayPtr](../../arrayptr/)\<T\>\& | Argumenty pro formátování řetězce. |

## Viz také

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Třída [String](../)
* Třída [IFormatProvider](../../iformatprovider/)
* Jmenný prostor [System](../../)
* Library [Aspose.Slides](../../../)