---
title: Format()
second_title: Referência da API Aspose.Slides para C++
description: Formata string no estilo C#.
type: docs
weight: 885
url: /pt/system/string/format/
---
## String::Format(const SharedPtr\<IFormatProvider\>\&, const String\&, const Args\&...) método

Formata string no estilo C#.

```cpp
template<class...> String System::String::Format(const SharedPtr<IFormatProvider> &fp, const String &format, const Args &... args)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Args | Arguments to format string. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fp | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format provider to use to convert arguments to strings. |
| format | const [String](../)\& | Format string. |
| args | const Args\&... | Arguments to format string. |

## String::Format(std::nullptr_t, const String\&, const Args\&...) método

Formata string no estilo C#.

```cpp
template<class...> String System::String::Format(std::nullptr_t, const String &format, const Args &... args)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Args | Arguments to format string. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| format | std::nullptr_t | Format string. |
| args | const [String](../)\& | Arguments to format string. |

## String::Format(std::nullptr_t, const char16_t(&), const Args\&...) método

Formata string no estilo C#.

```cpp
template<std::size_t,class...> String System::String::Format(std::nullptr_t, const char16_t(&format)[N], const Args &... args)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Args | Arguments to format string. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| format | std::nullptr_t | Format string. |
| args | const char16_t(&) | Arguments to format string. |

## String::Format(const String\&, const Args\&...) método

Formata string no estilo C#.

```cpp
template<class...> String System::String::Format(const String &format, const Args &... args)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Args | Arguments to format string. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| format | const [String](../)\& | Format string. |
| args | const Args\&... | Arguments to format string. |

## String::Format(const String\&, const System::ArrayPtr\<T\>\&) método

Formata string no estilo C#.

```cpp
template<class T> String System::String::Format(const String &format, const System::ArrayPtr<T> &args)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Arguments to format string. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| format | const [String](../)\& | Format string. |
| args | const [System::ArrayPtr](../../arrayptr/)\<T\>\& | Arguments to format string. |

## Veja também

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Classe [String](../)
* Classe [IFormatProvider](../../iformatprovider/)
* Espaço de nomes [System](../../)
* Library [Aspose.Slides](../../../)