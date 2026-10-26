---
title: Compare()
second_title: Referência da API Aspose.Slides para C++
description: Menor-igual-maior compara duas substrings.
type: docs
weight: 820
url: /pt/system/string/compare/
---
## String::Compare(const String\&, int, const String\&, int, int, bool) método

Menor-igual-maior compara duas substrings.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, bool ignoreCase=false)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| strA | const [String](../)\& | Primeira string a ser comparada. |
| indexA | int | Início da substring da primeira string. |
| strB | const [String](../)\& | Segunda string a ser comparada. |
| indexB | int | Início da substring da segunda string. |
| length | int | Número de caracteres a comparar. |
| ignoreCase | **bool** | Especifica se a comparação é sensível a maiúsculas/minúsculas. |

### Valor de Retorno

Valor negativo se a primeira substring for menor que a segunda, zero se coincidirem, valor positivo caso contrário.

## String::Compare(const String\&, int, const String\&, int, int, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) método

Menor-igual-maior compara duas substrings.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &ci)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| strA | const [String](../)\& | Primeira string a ser comparada. |
| indexA | int | Início da substring da primeira string. |
| strB | const [String](../)\& | Segunda string a ser comparada. |
| indexB | int | Início da substring da segunda string. |
| length | int | Número de caracteres a comparar. |
| ignoreCase | **bool** | Especifica se a comparação é sensível a maiúsculas/minúsculas. |
| ci | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Cultura a ser usada na comparação. |

### Valor de Retorno

Valor negativo se a primeira substring for menor que a segunda, zero se coincidirem, valor positivo caso contrário.

## String::Compare(const String\&, const String\&, System::StringComparison) método

Menor-igual-maior compara duas strings.

```cpp
static int System::String::Compare(const String &strA, const String &strB, System::StringComparison comparison_type)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| strA | const [String](../)\& | Primeira string a ser comparada. |
| strB | const [String](../)\& | Segunda string a ser comparada. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | Modo [Comparison](../../comparison/). |

### Valor de Retorno

Valor negativo se a primeira substring for menor que a segunda, zero se coincidirem, valor positivo caso contrário.

## String::Compare(const String\&, int, const String\&, int, int, System::StringComparison) método

Menor-igual-maior compara duas strings.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, System::StringComparison comparison_type)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| strA | const [String](../)\& | Primeira string a ser comparada. |
| indexA | int | Início da substring da primeira string. |
| strB | const [String](../)\& | Segunda string a ser comparada. |
| indexB | int | Início da substring da segunda string. |
| length | int | Número de caracteres a comparar. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | Modo [Comparison](../../comparison/). |

### Valor de Retorno

Valor negativo se a primeira substring for menor que a segunda, zero se coincidirem, valor positivo caso contrário.

## String::Compare(const String\&, const String\&, bool) método

Menor-igual-maior compara duas strings.

```cpp
static int System::String::Compare(const String &strA, const String &strB, bool ignoreCase=false)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| strA | const [String](../)\& | Primeira string a ser comparada. |
| strB | const [String](../)\& | Segunda string a ser comparada. |
| ignoreCase | **bool** | Especifica se a comparação é sensível a maiúsculas/minúsculas. |

### Valor de Retorno

Valor negativo se a primeira substring for menor que a segunda, zero se coincidirem, valor positivo caso contrário.

## String::Compare(const String\&, const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) método

Menor-igual-maior compara duas strings.

```cpp
static int System::String::Compare(const String &strA, const String &strB, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &ci)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| strA | const [String](../)\& | Primeira string a ser comparada. |
| strB | const [String](../)\& | Segunda string a ser comparada. |
| ignoreCase | **bool** | Especifica se a comparação é sensível a maiúsculas/minúsculas. |
| ci | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Cultura a ser usada na comparação. |

### Valor de Retorno

Valor negativo se a primeira substring for menor que a segunda, zero se coincidirem, valor positivo caso contrário.

## Veja Também

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../)
* Classe [CultureInfo](../../../system.globalization/cultureinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)