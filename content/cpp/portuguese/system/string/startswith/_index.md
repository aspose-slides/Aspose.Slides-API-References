---
title: StartsWith()
second_title: Referência da API Aspose.Slides para C++
description: Verifica se a string começa com a substring especificada.
type: docs
weight: 469
url: /pt/system/string/startswith/
---
## String::StartsWith(const String\&) const method

Verifica se a string começa com a substring especificada.

```cpp
bool System::String::StartsWith(const String &value) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../)\& | String de pesquisa. |

### Valor de Retorno

true se a string iniciar com a substring especificada, false caso contrário.

## String::StartsWith(const String\&, System::StringComparison) const method

Verifica se a string começa com a substring especificada.

```cpp
bool System::String::StartsWith(const String &value, System::StringComparison comparisonType) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../)\& | String de pesquisa. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modo, veja [System::StringComparison](../../stringcomparison/) para detalhes. |

### Valor de Retorno

true se a string iniciar com a substring especificada, false caso contrário.

## String::StartsWith(const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const method

Verifica se a string começa com a substring especificada.

```cpp
bool System::String::StartsWith(const String &value, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &culture=nullptr) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../)\& | String de pesquisa. |
| ignoreCase | **bool** | Especifica se a comparação distingue maiúsculas de minúsculas. |
| culture | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Cultura a ser usada ao realizar a comparação de strings. |

### Valor de Retorno

true se a string iniciar com a substring especificada, false caso contrário.

## Veja Também

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../)
* Classe [CultureInfo](../../../system.globalization/cultureinfo/)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)