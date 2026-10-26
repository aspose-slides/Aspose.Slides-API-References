---
title: MakeYieldEnumerable()
second_title: Referência da API Aspose.Slides para C++
description: Cria um IEnumerable a partir de uma função yield.
type: docs
weight: 2419
url: /pt/system/makeyieldenumerable/
---
## System::MakeYieldEnumerable(const Details::YieldFunction\<T\>\&) function

Cria um IEnumerable a partir de uma função de yield.

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerable<T>> System::MakeYieldEnumerable(const Details::YieldFunction<T> &fnc)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos na sequência |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fnc | const Details::YieldFunction\<T\>\& | A função de yield a ser executada |

### Valor de retorno

Ponteiro compartilhado para o IEnumerable

## Veja Também

* Typedef [SharedPtr](../sharedptr/)
* Classe [IEnumerable](../../system.collections.generic/ienumerable/)
* Espaço de nomes [System](../)
* Biblioteca [Aspose.Slides](../../)