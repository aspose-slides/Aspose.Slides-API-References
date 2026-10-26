---
title: Parallel
second_title: Aspose.Slides for C++ Referência da API
description: Fornece suporte para loops e regiões paralelas.
type: docs
weight: 1
url: /pt/system.threading.tasks/parallel/
---
## Parallel classe


Fornece suporte para loops e regiões paralelas.

```cpp
class Parallel
```

## Métodos

| Method | Description |
| --- | --- |
| static [ParallelLoopResult](../parallelloopresult/) [ForEach](./foreach/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<TSource\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[ParallelOptions](../paralleloptions/)\>\&, const [Action](../../system/action/)\<TSource\>\&) | Executa uma operação foreach em um IEnumerable em que as iterações podem ser executadas em paralelo. |
| static [ParallelLoopResult](../parallelloopresult/) [ForEach](./foreach/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<TSource\>\>\&, const [Action](../../system/action/)\<TSource\>\&) | Executa uma operação foreach em um IEnumerable em que as iterações podem ser executadas em paralelo. |
## Observações


Esta classe fornece métodos para execução paralela de loops e operações. 
## Veja Também

* Namespace [System::Threading::Tasks](../)
* Biblioteca [Aspose.Slides](../../)