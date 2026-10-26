---
title: MakeDiff()
second_title: Referência da API Aspose.Slides para C++
description: Calcula 'diff' entre duas coleções. Para cada elemento de cada coleção como chave, o valor resultante será positivo se o elemento ocorrer mais vezes na coleção \"expected\", negativo se o elemento ocorrer mais vezes na coleção \"actual\", e zero se o elemento ocorrer o mesmo número de vezes em cada coleção.
type: docs
weight: 1
url: /pt/system/collectionasserthelper/makediff/
---
## CollectionAssertHelper::MakeDiff(const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T1\>\>\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T2\>\>\&) método

Calcula 'diff' entre duas coleções. Para cada elemento de cada coleção como chave, o valor resultante será positivo se o elemento ocorrer mais vezes na coleção \"expected\", negativo se o elemento ocorrer mais vezes na coleção \"actual\", e zero se o elemento ocorrer o mesmo número de vezes em cada coleção.

```cpp
template<typename T1,typename T2> static System::SharedPtr<System::Collections::Generic::Dictionary<T1, int32_t>> System::CollectionAssertHelper::MakeDiff(const System::SharedPtr<System::Collections::Generic::IEnumerable<T1>> &expected, const System::SharedPtr<System::Collections::Generic::IEnumerable<T2>> &actual)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | Tipo de elemento da coleção esperada. |
| T2 | Tipo de elemento da coleção real. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| expected | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T1\>\>\& | Coleção esperada. |
| actual | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T2\>\>\& | Coleção real. |

### Valor de retorno

Mapa dos resultados de comparação por valor conforme as regras acima.

## Ver também

* Typedef [SharedPtr](../../sharedptr/)
* Classe [Dictionary](../../../system.collections.generic/dictionary/)
* Classe [IEnumerable](../../../system.collections.generic/ienumerable/)
* Struct [CollectionAssertHelper](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)