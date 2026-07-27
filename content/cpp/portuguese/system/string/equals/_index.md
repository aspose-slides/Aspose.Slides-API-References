---
title: Equals()
second_title: Referência da API Aspose.Slides para C++
description: Comparação de igualdade de strings. Vários modos fornecidos pela enumeração StringComparison são suportados.
type: docs
weight: 391
url: /pt/system/string/equals/
---
## String::Equals(const String\&, System::StringComparison) const método

[String](../) comparação de igualdade. Vários modos fornecidos pela enumeração StringComparison são suportados.

```cpp
bool System::String::Equals(const String &str, System::StringComparison comparison_type) const
```

### Arguments

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) para comparar com a atual. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modo (veja [System::StringComparison](../../stringcomparison/) para detalhes). |

### Valor de Retorno

true se as strings coincidem usando o tipo de comparação selecionado, false caso contrário.

## String::Equals(const String\&) const método

[String](../) comparação de igualdade. Usa modo de comparação [System::StringComparison::Ordinal](../../stringcomparison/).

```cpp
bool System::String::Equals(const String &str) const
```

### Arguments

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) para comparar com a atual. |

### Valor de Retorno

true se as strings coincidem, false caso contrário.

## String::Equals(const String\&, const String\&) método

Compara duas strings usando o modo de comparação Ordial.

```cpp
static bool System::String::Equals(const String &strA, const String &strB)
```

### Arguments

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| strA | const [String](../)\& | Primeira string para comparar. |
| strB | const [String](../)\& | Segunda string para comparar. |

### Valor de Retorno

true se as strings coincidem, false caso contrário.

## String::Equals(const String\&, const String\&, System::StringComparison) método

```cpp
static bool System::String::Equals(const String &strA, const String &strB, System::StringComparison comparison_type)
```

### Arguments

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| strA | const [String](../)\& | Primeira string para comparar. |
| strB | const [String](../)\& | Segunda string para comparar. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modo. |

### Valor de Retorno

true se as strings coincidem, false caso contrário.

## See Also

* Enum [StringComparison](../../stringcomparison/)
* Classe [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)