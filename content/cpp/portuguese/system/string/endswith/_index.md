---
title: EndsWith()
second_title: Referência da API Aspose.Slides para C++
description: Verifica se a string termina com a substring especificada.
type: docs
weight: 482
url: /pt/system/string/endswith/
---
## String::EndsWith(const String\&) const método

Verifica se String termina com a subcadeia especificada.

```cpp
bool System::String::EndsWith(const String &value) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../)\& | String de pesquisa. |

### Valor de retorno

true se String termina com a subcadeia especificada, false caso contrário.

## String::EndsWith(const String\&, System::StringComparison) const método

Verifica se String termina com a subcadeia especificada.

```cpp
bool System::String::EndsWith(const String &value, System::StringComparison comparisonType) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../)\& | String de pesquisa. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | modo [Comparison](../../comparison/), consulte [System::StringComparison](../../stringcomparison/) para detalhes. |

### Valor de retorno

true se String termina com a subcadeia especificada, false caso contrário.

## String::EndsWith(const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const método

Verifica se String termina com a subcadeia especificada.

```cpp
bool System::String::EndsWith(const String &value, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &culture=nullptr) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../)\& | String de pesquisa. |
| ignoreCase | **bool** | Especifica se a comparação é insensível a maiúsculas/minúsculas. |
| culture | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Cultura a ser usada ao realizar a comparação de string. |

### Valor de retorno

true se String termina com a subcadeia especificada, false caso contrário.

## Veja também

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)