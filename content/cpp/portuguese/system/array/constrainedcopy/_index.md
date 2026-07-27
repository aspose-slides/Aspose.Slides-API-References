---
title: ConstrainedCopy()
second_title: Referência da API Aspose.Slides para C++
description: Copia um intervalo de elementos de um System.Array a partir da fonte especificada.
type: docs
weight: 716
url: /pt/system/array/constrainedcopy/
---
## Array::ConstrainedCopy(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) método

Copia um intervalo de elementos de um [System.Array](../) começando na fonte especificada.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::ConstrainedCopy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| SrcType | Tipo dos elementos no array de origem |
| DstType | Tipo dos elementos no array de destino |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Array de origem |
| srcIndex | **int64_t** | [Index](../../index/) no array de origem designando o início do intervalo de itens a copiar |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Array de destino |
| dstIndex | **int64_t** | [Index](../../index/) no array de destino para começar a inserir os itens copiados |
| count | **int64_t** | O número de elementos a copiar |
## Observações

IMPLEMENTAÇÃO BRUTA TEMPORÁRIA SEM NENHUM DESFEITO!
## Veja Também

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [Array](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)