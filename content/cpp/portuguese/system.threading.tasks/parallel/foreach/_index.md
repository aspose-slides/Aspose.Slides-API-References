---
title: ForEach()
second_title: Aspose.Slides para C++ Referência da API
description: Executa uma operação foreach em um IEnumerable em que as iterações podem ser executadas em paralelo.
type: docs
weight: 1
url: /pt/system.threading.tasks/parallel/foreach/
---
## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const SharedPtr\<ParallelOptions\>\&, const Action\<TSource\>\&) method


Executa uma operação foreach em um IEnumerable em que as iterações podem ser executadas em paralelo.

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const SharedPtr<ParallelOptions> &parallelOptions, const Action<TSource> &body)
```


### Parâmetros do modelo

| Parâmetro | Descrição |
| --- | --- |
| TSource | O tipo dos dados na origem. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| source | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<TSource\>\>\& | Uma fonte de dados enumerável. |
| parallelOptions | const [SharedPtr](../../../system/sharedptr/)\<[ParallelOptions](../../paralleloptions/)\>\& | Um objeto que configura o comportamento desta operação. |
| body | const [Action](../../../system/action/)\<TSource\>\& | O delegate que é invocado uma vez por iteração. |

### Valor de retorno

Uma estrutura [ParallelLoopResult](../../parallelloopresult/) que contém informações sobre qual parte do loop foi concluída.
## Observações



Este método particiona o IEnumerable de origem e executa o delegate body em várias threads simultaneamente. 
## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const Action\<TSource\>\&) method


Executa uma operação foreach em um IEnumerable em que as iterações podem ser executadas em paralelo.

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const Action<TSource> &body)
```


### Parâmetros do modelo

| Parâmetro | Descrição |
| --- | --- |
| TSource | O tipo dos dados na origem. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| source | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<TSource\>\>\& | Uma fonte de dados enumerável. |
| body | const [Action](../../../system/action/)\<TSource\>\& | O delegate que é invocado uma vez por iteração. |

### Valor de retorno

Uma estrutura [ParallelLoopResult](../../parallelloopresult/) que contém informações sobre qual parte do loop foi concluída.
## Observações



Usa o [ParallelOptions](../../paralleloptions/) padrão com paralelismo ilimitado e sem cancelamento. 
## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Action](../../../system/action/)
* Class [ParallelLoopResult](../../parallelloopresult/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [ParallelOptions](../../paralleloptions/)
* Class [Parallel](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)