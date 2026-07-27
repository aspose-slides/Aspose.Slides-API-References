---
title: MakeYieldEnumerator()
second_title: Referência da API Aspose.Slides para C++
description: Cria um IEnumerator a partir de uma função yield.
type: docs
weight: 2432
url: /pt/system/makeyieldenumerator/
---
## System::MakeYieldEnumerator(const Details::YieldFunction\<T\>\&) função

Cria um IEnumerator a partir de uma função yield.

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerator<T>> System::MakeYieldEnumerator(const Details::YieldFunction<T> &fnc)
```

### Parâmetros de modelo

| Parameter | Description |
| --- | --- |
| T | O tipo de elementos na sequência |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| fnc | const Details::YieldFunction\<T\>\& | A função yield a ser executada |

### Valor de retorno

Ponteiro compartilhado para o IEnumerator

## Veja Também

* Typedef [SharedPtr](../sharedptr/)
* Classe [IEnumerator](../../system.collections.generic/ienumerator/)
* Espaço de nomes [System](../)
* Biblioteca [Aspose.Slides](../../)