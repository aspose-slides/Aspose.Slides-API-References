---
title: Format()
second_title: Referencia de API de Aspose.Slides para C++
description: Formatea la cadena al estilo C#.
type: docs
weight: 885
url: /es/system/string/format/
---
## String::Format(const SharedPtr\<IFormatProvider\>\&, const String\&, const Args\&...) método


Formatea la cadena al estilo C#.

```cpp
template<class...> String System::String::Format(const SharedPtr<IFormatProvider> &fp, const String &format, const Args &... args)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Args | Argumentos para la cadena de formato. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fp | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Proveedor de formato a usar para convertir los argumentos a cadenas. |
| format | const [String](../)\& | Cadena de formato. |
| args | const Args\&... | Argumentos para la cadena de formato. |

## String::Format(std::nullptr_t, const String\&, const Args\&...) método


Formatea la cadena al estilo C#.

```cpp
template<class...> String System::String::Format(std::nullptr_t, const String &format, const Args &... args)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Args | Argumentos para la cadena de formato. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| format | std::nullptr_t | Cadena de formato. |
| args | const [String](../)\& | Argumentos para la cadena de formato. |

## String::Format(std::nullptr_t, const char16_t(&), const Args\&...) método


Formatea la cadena al estilo C#.

```cpp
template<std::size_t,class...> String System::String::Format(std::nullptr_t, const char16_t(&format)[N], const Args &... args)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Args | Argumentos para la cadena de formato. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| format | std::nullptr_t | Cadena de formato. |
| args | const char16_t(&) | Argumentos para la cadena de formato. |

## String::Format(const String\&, const Args\&...) método


Formatea la cadena al estilo C#.

```cpp
template<class...> String System::String::Format(const String &format, const Args &... args)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Args | Argumentos para la cadena de formato. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| format | const [String](../)\& | Cadena de formato. |
| args | const Args\&... | Argumentos para la cadena de formato. |

## String::Format(const String\&, const System::ArrayPtr\<T\>\&) método


Formatea la cadena al estilo C#.

```cpp
template<class T> String System::String::Format(const String &format, const System::ArrayPtr<T> &args)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Argumentos para la cadena de formato. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| format | const [String](../)\& | Cadena de formato. |
| args | const [System::ArrayPtr](../../arrayptr/)\<T\>\& | Argumentos para la cadena de formato. |

## Ver también

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Clase [String](../)
* Clase [IFormatProvider](../../iformatprovider/)
* Espacio de nombres [System](../../)
* Library [Aspose.Slides](../../../)