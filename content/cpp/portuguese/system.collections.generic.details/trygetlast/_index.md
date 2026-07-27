---
title: TryGetLast()
second_title: Referência da API Aspose.Slides para C++
description: Tenta obter o último elemento da coleção.
type: docs
weight: 261
url: /pt/system.collections.generic.details/trygetlast/
---
## System::Collections::Generic::Details::TryGetLast(IEnumerable\<T\>\&, bool\&) função


Tenta obter o último elemento da coleção.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetLast(IEnumerable<T> &enumerable, bool &found)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos da coleção. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | A coleção da qual um elemento será adquirido. |
| found | **bool**\& | O parâmetro de saída. Retorna true quando a coleção contém algum elemento. Caso contrário, retorna false. |

### Valor de retorno

Retorna o último elemento da coleção. O valor padrão do tipo será retornado quando a coleção estiver vazia.

## Veja Também

* Classe [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Collections::Generic::Details](../)
* Biblioteca [Aspose.Slides](../../)