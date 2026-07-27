---
title: TryGetFirst()
second_title: Referência da API Aspose.Slides para C++
description: Tenta obter o primeiro elemento da coleção.
type: docs
weight: 248
url: /pt/system.collections.generic.details/trygetfirst/
---
## System::Collections::Generic::Details::TryGetFirst(IEnumerable\<T\>\&, bool\&) função


Tenta obter o primeiro elemento da coleção.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetFirst(IEnumerable<T> &enumerable, bool &found)
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

Retorna o primeiro elemento da coleção. O valor padrão do tipo será retornado quando a coleção estiver vazia.

## System::Collections::Generic::Details::TryGetFirst(IEnumerable\<T\>\&, const Func\<T, bool\>\&, bool\&) função


Tenta obter o primeiro elemento da coleção que satisfaça a função predicado.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetFirst(IEnumerable<T> &enumerable, const Func<T, bool> &predicate, bool &found)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos da coleção. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | A coleção da qual um elemento será adquirido. |
| predicate | const [Func](../../system/func/)\<T, **bool**\>\& | A função predicado. |
| found | **bool**\& | O parâmetro de saída. Retorna true quando a coleção contém algum elemento. Caso contrário, retorna false. |

### Valor de retorno

Retorna o primeiro elemento da coleção. O valor padrão do tipo será retornado quando nenhum elemento que satisfaça a função predicado especificada for encontrado.

## Veja também

* Classe [IEnumerable](../../system.collections.generic/ienumerable/)
* Classe [Func](../../system/func/)
* Espaço de nomes [System::Collections::Generic::Details](../)
* Biblioteca [Aspose.Slides](../../)