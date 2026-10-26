---
title: Split()
second_title: Referência da API Aspose.Slides for C++
description: Divide a string por caractere.
type: docs
weight: 768
url: /pt/system/string/split/
---
## String::Split(char_t, StringSplitOptions) const método


Divide a string por caractere.

```cpp
ArrayPtr<String> System::String::Split(char_t separator=u' ', StringSplitOptions opt=StringSplitOptions::None) const
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| separator | char_t | Caractere usado para dividir a string. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Opções de divisão. |

### Valor de Retorno

[Array](../../array/) de subsequências.

## String::Split(char_t, int32_t, StringSplitOptions) const método


Divide a string por caractere.

```cpp
ArrayPtr<String> System::String::Split(char_t separator, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| separator | char_t | Caractere usado para dividir a string. |
| count | **int32_t** | O número máximo de subsequências a serem retornadas. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Opções de divisão. |

### Valor de Retorno

[Array](../../array/) de subsequências.

## String::Split(char_t, char_t, StringSplitOptions) const método


Divide a string por um de dois caracteres.

```cpp
ArrayPtr<String> System::String::Split(char_t separatorA, char_t separatorB, StringSplitOptions opt=StringSplitOptions::None) const
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| separatorA | char_t | Primeiro caractere usado para dividir a string. |
| separatorB | char_t | Segundo caractere usado para dividir a string. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Opções de divisão. |

### Valor de Retorno

[Array](../../array/) de subsequências.

## String::Split(const ArrayPtr\<char_t\>\&, StringSplitOptions) const método


Divide a string por um dos caracteres especificados.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) de caracteres separadores. Se vazio, qualquer caractere de espaço em branco é considerado um separador. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Opções de divisão. |

### Valor de Retorno

[Array](../../array/) de subsequências.

## String::Split(const ArrayPtr\<char_t\>\&, int32_t, StringSplitOptions) const método


Divide a string por um dos caracteres especificados.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) de caracteres separadores. Se vazio, qualquer caractere de espaço em branco é considerado um separador. |
| count | **int32_t** | O número máximo de subsequências a serem retornadas. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Opções de divisão. |

### Valor de Retorno

[Array](../../array/) de subsequências.

## String::Split(const String\&, StringSplitOptions) const método


Divide a string por subsequência.

```cpp
ArrayPtr<String> System::String::Split(const String &separator, StringSplitOptions opt=StringSplitOptions::None) const
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| separator | const [String](../)\& | Subsequência atuando como separador. Se vazio, o caractere de espaço em branco atua como separador. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Opções de divisão. |

### Valor de Retorno

[Array](../../array/) de subsequências.

## String::Split(const String\&, int, StringSplitOptions) const método


Divide a string por subsequência.

```cpp
ArrayPtr<String> System::String::Split(const String &separator, int count, StringSplitOptions opt=StringSplitOptions::None) const
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| separator | const [String](../)\& | Subsequência atuando como separador. Se vazio, o caractere de espaço em branco atua como separador. |
| count | int | Número máximo de elementos na matriz de divisões. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Opções de divisão. |

### Valor de Retorno

[Array](../../array/) de subsequências.

## String::Split(const ArrayPtr\<String\>\&, StringSplitOptions) const método


Divide a string por subsequência.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) de cadeias separadoras. Se vazio, nenhuma divisão é feita. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Opções de divisão. |

### Valor de Retorno

[Array](../../array/) de subsequências.

## String::Split(const ArrayPtr\<String\>\&, int, StringSplitOptions) const método


Divide a string por subsequência. Atualmente, suporta apenas matriz de separadores com zero ou um elemento.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, int count, StringSplitOptions opt=StringSplitOptions::None) const
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) de cadeias separadoras. Se vazio, nenhuma divisão é feita. |
| count | int | Número máximo de elementos na matriz de divisões. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Opções de divisão. |

### Valor de Retorno

[Array](../../array/) de subsequências.

## Veja Também

* Enum [StringSplitOptions](../../stringsplitoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)