---
title: ForEach()
second_title: Referencia de API de Aspose.Slides para C++
description: Ejecuta una operación foreach sobre un IEnumerable en la que las iteraciones pueden ejecutarse en paralelo.
type: docs
weight: 1
url: /es/system.threading.tasks/parallel/foreach/
---
## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const SharedPtr\<ParallelOptions\>\&, const Action\<TSource\>\&) método

Ejecuta una operación foreach sobre un IEnumerable en la que las iteraciones pueden ejecutarse en paralelo.

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const SharedPtr<ParallelOptions> &parallelOptions, const Action<TSource> &body)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TSource | El tipo de los datos en la fuente. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<TSource\>\>\& | Una fuente de datos enumerable. |
| parallelOptions | const [SharedPtr](../../../system/sharedptr/)\<[ParallelOptions](../../paralleloptions/)\>\& | Un objeto que configura el comportamiento de esta operación. |
| body | const [Action](../../../system/action/)\<TSource\>\& | El delegado que se invoca una vez por iteración. |

### Valor de retorno

Una estructura [ParallelLoopResult](../../parallelloopresult/) que contiene información sobre qué parte del bucle se completó.

## Observaciones

Este método divide la fuente enumerable y ejecuta el delegado body en múltiples hilos simultáneamente.

## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const Action\<TSource\>\&) método

Ejecuta una operación foreach sobre un IEnumerable en la que las iteraciones pueden ejecutarse en paralelo.

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const Action<TSource> &body)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| TSource | El tipo de los datos en la fuente. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<TSource\>\>\& | Una fuente de datos enumerable. |
| body | const [Action](../../../system/action/)\<TSource\>\& | El delegado que se invoca una vez por iteración. |

### Valor de retorno

Una estructura [ParallelLoopResult](../../parallelloopresult/) que contiene información sobre qué parte del bucle se completó.

## Observaciones

Utiliza [ParallelOptions](../../paralleloptions/) predeterminado con paralelismo ilimitado y sin cancelación.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Action](../../../system/action/)
* Clase [ParallelLoopResult](../../parallelloopresult/)
* Clase [IEnumerable](../../../system.collections.generic/ienumerable/)
* Clase [ParallelOptions](../../paralleloptions/)
* Clase [Parallel](../)
* Espacio de nombres [System::Threading::Tasks](../../)
* Biblioteca [Aspose.Slides](../../../)