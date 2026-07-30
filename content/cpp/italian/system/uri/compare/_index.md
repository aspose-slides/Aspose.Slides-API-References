---
title: Compare()
second_title: Riferimento API di Aspose.Slides per C++
description: Confronta gli oggetti Uri specificati utilizzando le regole di confronto specificate.
type: docs
weight: 521
url: /it/system/uri/compare/
---
## Uri::Compare(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, UriComponents, UriFormat, StringComparison) metodo

Confronta gli oggetti [Uri](../) specificati utilizzando le regole di confronto specificate.

```cpp
static int32_t System::Uri::Compare(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2, UriComponents partsToCompare, UriFormat compareFormat, StringComparison comparisonType)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uri1 | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Il primo comparando |
| uri2 | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Il secondo comparando |
| partsToCompare | [UriComponents](../../uricomponents/) | Specifica le parti di **uri1** e **uri2** da confrontare |
| compareFormat | [UriFormat](../../uriformat/) | Specifica la codifica dei caratteri utilizzata quando i componenti degli URI vengono confrontati |
| comparisonType | [StringComparison](../../stringcomparison/) | Uno dei valori di StringComparison |

### Valore di ritorno

Un valore negativo se **uri1** è minore di **uri2**; 0 se uri1 e uri2 sono uguali; un valore positivo se **uri1** è maggiore di **uri2**

## Vedi anche

* Enum [UriComponents](../../uricomponents/)
* Enum [UriFormat](../../uriformat/)
* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)