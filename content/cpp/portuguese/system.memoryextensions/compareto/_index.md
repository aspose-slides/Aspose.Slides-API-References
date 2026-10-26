---
title: CompareTo()
second_title: Referência da API Aspose.Slides para C++
description: Compara duas faixas de caracteres com as regras de comparação de strings especificadas.
type: docs
weight: 404
url: /pt/system.memoryextensions/compareto/
---
## System::MemoryExtensions::CompareTo(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) função

Compara duas faixas de caracteres com as regras de comparação de strings especificadas.

```cpp
int32_t System::MemoryExtensions::CompareTo(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &other, StringComparison comparisonType)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | A primeira faixa de caracteres |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | A segunda faixa de caracteres |
| comparisonType | [StringComparison](../../system/stringcomparison/) | O tipo de comparação de string a ser executado |

### Valor de Retorno

Valor negativo se span < other, zero se igual, positivo se span > other

## Veja Também

* Enum [StringComparison](../../system/stringcomparison/)
* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)