---
title: Compare()
second_title: Referência da API Aspose.Slides para C++
description: Compara os objetos Uri especificados usando as regras de comparação especificadas.
type: docs
weight: 521
url: /pt/system/uri/compare/
---
## Uri::Compare(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, UriComponents, UriFormat, StringComparison) método

Compara os objetos [Uri](../) especificados usando as regras de comparação especificadas.

```cpp
static int32_t System::Uri::Compare(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2, UriComponents partsToCompare, UriFormat compareFormat, StringComparison comparisonType)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| uri1 | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | O primeiro comparando |
| uri2 | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | O segundo comparando |
| partsToCompare | [UriComponents](../../uricomponents/) | Especifica as partes de **uri1** e **uri2** a serem comparadas |
| compareFormat | [UriFormat](../../uriformat/) | Especifica o escape de caracteres usado quando os componentes de URIs são comparados |
| comparisonType | [StringComparison](../../stringcomparison/) | Um dos valores de StringComparison |

### Valor de Retorno

Um valor negativo se **uri1** for menor que **uri2**; 0 se uri1 e uri2 forem iguais; um valor positivo se **uri1** for maior que **uri2**

## Ver Também

* Enum [UriComponents](../../uricomponents/)
* Enum [UriFormat](../../uriformat/)
* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Classe [Uri](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)