---
title: Split()
second_title: Referencia de API de Aspose.Slides para C++
description: Divide la cadena por carácter.
type: docs
weight: 768
url: /es/system/string/split/
---
## String::Split(char_t, StringSplitOptions) const método


Divide la cadena por carácter.

```cpp
ArrayPtr<String> System::String::Split(char_t separator=u' ', StringSplitOptions opt=StringSplitOptions::None) const
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| separator | char_t | Carácter con el que dividir la cadena. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Opciones de división. |

### Valor devuelto

[Array](../../array/) de subcadenas.

## String::Split(char_t, int32_t, StringSplitOptions) const método


Divide la cadena por carácter.

```cpp
ArrayPtr<String> System::String::Split(char_t separator, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| separator | char_t | Carácter con el que dividir la cadena. |
| count | **int32_t** | Número máximo de subcadenas a devolver. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Opciones de división. |

### Valor devuelto

[Array](../../array/) de subcadenas.

## String::Split(char_t, char_t, StringSplitOptions) const método


Divide la cadena por uno de dos caracteres.

```cpp
ArrayPtr<String> System::String::Split(char_t separatorA, char_t separatorB, StringSplitOptions opt=StringSplitOptions::None) const
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| separatorA | char_t | Primer carácter con el que dividir la cadena. |
| separatorB | char_t | Segundo carácter con el que dividir la cadena. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Opciones de división. |

### Valor devuelto

[Array](../../array/) de subcadenas.

## String::Split(const ArrayPtr\<char_t\>\&, StringSplitOptions) const método


Divide la cadena por uno de los caracteres especificados.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) de caracteres separadores. Si está vacío, cualquier carácter de espacio en blanco se considera un separador. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Opciones de división. |

### Valor devuelto

[Array](../../array/) de subcadenas.

## String::Split(const ArrayPtr\<char_t\>\&, int32_t, StringSplitOptions) const método


Divide la cadena por uno de los caracteres especificados.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) de caracteres separadores. Si está vacío, cualquier carácter de espacio en blanco se considera un separador. |
| count | **int32_t** | Número máximo de subcadenas a devolver. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Opciones de división. |

### Valor devuelto

[Array](../../array/) de subcadenas.

## String::Split(const String\&, StringSplitOptions) const método


Divide la cadena por una subcadena.

```cpp
ArrayPtr<String> System::String::Split(const String &separator, StringSplitOptions opt=StringSplitOptions::None) const
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| separator | const [String](../)\& | Subcadena que actúa como separador. Si está vacía, el carácter de espacio en blanco actúa como separador. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Opciones de división. |

### Valor devuelto

[Array](../../array/) de subcadenas.

## String::Split(const String\&, int, StringSplitOptions) const método


Divide la cadena por una subcadena.

```cpp
ArrayPtr<String> System::String::Split(const String &separator, int count, StringSplitOptions opt=StringSplitOptions::None) const
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| separator | const [String](../)\& | Subcadena que actúa como separador. Si está vacía, el carácter de espacio en blanco actúa como separador. |
| count | int | Número máximo de elementos en la matriz de divisiones. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Opciones de división. |

### Valor devuelto

[Array](../../array/) de subcadenas.

## String::Split(const ArrayPtr\<String\>\&, StringSplitOptions) const método


Divide la cadena por una subcadena.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) de cadenas separadoras. Si está vacío, no se realiza división. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Opciones de división. |

### Valor devuelto

[Array](../../array/) de subcadenas.

## String::Split(const ArrayPtr\<String\>\&, int, StringSplitOptions) const método


Divide la cadena por una subcadena. Actualmente, solo se admiten matrices de separadores de cero o un elemento.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, int count, StringSplitOptions opt=StringSplitOptions::None) const
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) de cadenas separadoras. Si está vacío, no se realiza división. |
| count | int | Número máximo de elementos en la matriz de divisiones. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Opciones de división. |

### Valor devuelto

[Array](../../array/) de subcadenas.

## Véase también

* Enum [StringSplitOptions](../../stringsplitoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Clase [String](../)
* Espacio de nombres [System](../../)
* Library [Aspose.Slides](../../../)