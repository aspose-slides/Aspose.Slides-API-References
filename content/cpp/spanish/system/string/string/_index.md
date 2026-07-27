---
title: String()
second_title: Referencia de API de Aspose.Slides para C++ 
description: Constructor predeterminado. Crea un objeto string que se considera nulo.
type: docs
weight: 14
url: /es/system/string/string/
---
## String::String() constructor

Constructor predeterminado. Crea un objeto string que se considera nulo.

```cpp
System::String::String()
```

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char16_t\>::value\>::type *) constructor

Construye una cadena a partir de un literal de cadena. Considera el literal como una cadena terminada en nulo y calcula la longitud de la cadena objetivo en función del tamaño del literal.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char16_t>::value>::type *=nullptr)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | T\& | [String](../) puntero literal. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char16_t\>::value\>::type *) constructor

Construye una cadena a partir de un puntero a cadena de caracteres. Trata la cadena apuntada como terminada en nulo y calcula la longitud de la cadena objetivo en función del carácter nulo.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char16_t>::value>::type *=nullptr)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const T\& | Puntero a cadena de caracteres. |

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char\>::value\>::type *) constructor

Construye una cadena a partir de un literal de cadena. Considera el literal como una cadena terminada en nulo en UTF8 y calcula la longitud de la cadena objetivo en función del tamaño del literal.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char>::value>::type *=nullptr)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | T\& | [String](../) puntero literal. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char\>::value\>::type *) constructor

Construye una cadena a partir de un puntero a cadena de caracteres. Trata la cadena apuntada como terminada en nulo en UTF8 y calcula la longitud de la cadena objetivo en función del carácter nulo.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char>::value>::type *=nullptr)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const T\& | Puntero a cadena de caracteres. |

## String::String(const char16_t *, int) constructor

Construye una cadena a partir de un puntero a cadena de caracteres y una longitud explícita.

```cpp
System::String::String(const char16_t *str, int length)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const char16_t * | [String](../) puntero, puede ser literal o arreglo. |
| length | int | Longitud de cadena explícita |

## String::String(const ReadOnlySpan\<char16_t\>\&) constructor

Inicializa una nueva instancia de la clase [System.String](../) con los caracteres Unicode indicados en el span de solo lectura especificado.

```cpp
System::String::String(const ReadOnlySpan<char16_t> &value)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [ReadOnlySpan](../../readonlyspan/)\<char16_t\>\& | Un span de solo lectura de caracteres Unicode. |

## String::String(const char *, int) constructor

Construye una cadena a partir de un puntero a cadena de caracteres y una longitud explícita.

```cpp
System::String::String(const char *str, int length)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const char * | [String](../) puntero a los datos UTF8, puede ser literal o arreglo. |
| length | int | Longitud de cadena explícita |

## String::String(const char16_t *, int, int) constructor

Construye una cadena a partir de un puntero a cadena de caracteres desde una posición inicial usando una longitud.

```cpp
System::String::String(const char16_t *str, int start, int length)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const char16_t * | [String](../) puntero, puede ser literal o arreglo. |
| start | int | Posición inicial. |
| length | int | [String](../) longitud. |

## String::String(const char16_t, int) constructor

Constructor de relleno.

```cpp
System::String::String(const char16_t ch, int count)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ch | const char16_t | Carácter de relleno. |
| count | int | Longitud objetivo. |

## String::String(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) constructor

Constructor nullptr. Declarado como plantilla para resolver prioridades con otros constructores plantilla.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<std::is_same<T, std::nullptr_t>::value>::type *=nullptr)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Debe ser nullptr_t |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const T\& | nullptr |

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, wchar_t\>::value\>::type *) constructor

Construye una cadena a partir de un literal de cadena ancha. Considera el literal como una cadena terminada en nulo y calcula la longitud de la cadena objetivo en función del tamaño del literal. La conversión desde **wchar_t** es lenta en algunas plataformas, por lo que no se permiten conversiones implícitas.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, wchar_t>::value>::type *=nullptr)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | T\& | [String](../) puntero literal. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, wchar_t\>::value\>::type *) constructor

Construye una cadena a partir de un puntero a cadena de caracteres anchos. Trata la cadena apuntada como terminada en nulo y calcula la longitud de la cadena objetivo en función del carácter nulo. La conversión desde **wchar_t** es lenta en algunas plataformas, por lo que no se permiten conversiones implícitas.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, wchar_t>::value>::type *=nullptr)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const T\& | Puntero a cadena de caracteres. |

## String::String(const wchar_t *, int) constructor

Construye una cadena a partir de un puntero a cadena de caracteres anchos y una longitud explícita. La conversión desde **wchar_t** es lenta en algunas plataformas, por lo que no se permiten conversiones implícitas.

```cpp
System::String::String(const wchar_t *str, int length)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const **wchar_t** * | [String](../) puntero, puede ser literal o arreglo. |
| length | int | Longitud de cadena explícita |

## String::String(const wchar_t, int) constructor

Constructor de relleno. La conversión desde **wchar_t** es lenta en algunas plataformas, por lo que no se permiten conversiones implícitas.

```cpp
System::String::String(const wchar_t ch, int count=1)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ch | const **wchar_t** | Carácter de relleno. |
| count | int | Longitud objetivo. |

## String::String(const String\&) constructor

Constructor de copia.

```cpp
System::String::String(const String &str)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) a copiar. |

## String::String(String\&&) constructor

Constructor de movimiento.

```cpp
System::String::String(String &&str) noexcept
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | [String](../)\&& | [String](../) del que mover los datos. |

## String::String(const ArrayPtr\<char16_t\>\&) constructor

Convierte todo el arreglo de caracteres a una cadena.

```cpp
System::String::String(const ArrayPtr<char16_t> &arr)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | [Array](../../array/) a convertir a cadena. |

## String::String(const ArrayPtr\<char16_t\>\&, int, int) constructor

Convierte un subrango de un arreglo de caracteres a una cadena. Si los parámetros están fuera de los límites del arreglo, se construye una cadena vacía.

```cpp
System::String::String(const ArrayPtr<char16_t> &arr, int offset, int len)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | Arreglo de caracteres. |
| offset | int | Índice de inicio del subarreglo. |
| len | int | Longitud del subarreglo. |

## String::String(const codeporting_icu::UnicodeString\&) constructor

Envuelve UnicodeString en [String](../).

```cpp
System::String::String(const codeporting_icu::UnicodeString &str)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const codeporting_icu::UnicodeString\& | UnicodeString a envolver en [String](../). |

## String::String(codeporting_icu::UnicodeString\&&) constructor

Constructor de movimiento.

```cpp
System::String::String(codeporting_icu::UnicodeString &&str) noexcept
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | codeporting_icu::UnicodeString\&& | UnicodeString a envolver en [String](../). |

## String::String(const std::wstring\&) constructor

Crea [String](../) a partir de un widestring.

```cpp
System::String::String(const std::wstring &str)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const std::wstring\& | Widestring a convertir en [String](../). |

## String::String(const std::u16string\&) constructor

Crea [String](../) a partir de una cadena utf16.

```cpp
System::String::String(const std::u16string &str)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const std::u16string\& | Cadena Utf16 a convertir en [String](../). |

## String::String(const std::string\&) constructor

Crea [String](../) a partir de una cadena std::string presentada en formato UTF-8.

```cpp
System::String::String(const std::string &utf8str)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| utf8str | const std::string\& | Cadena std::string a convertir en [String](../). |

## String::String(const std::u32string\&) constructor

Crea [String](../) a partir de una cadena std::u32string.

```cpp
System::String::String(const std::u32string &u32str)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| u32str | const std::u32string\& | Cadena std::u32string a convertir en [String](../). |

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Class [ReadOnlySpan](../../readonlyspan/)
* Struct [IsStringLiteral](../../isstringliteral/)
* Struct [IsStringPointer](../../isstringpointer/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)