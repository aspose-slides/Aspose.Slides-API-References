---
title: Parallel
second_title: Referencia de API de Aspose.Slides para C++
description: Proporciona soporte para bucles y regiones paralelas.
type: docs
weight: 1
url: /es/system.threading.tasks/parallel/
---
## Clase Parallel


Proporciona soporte para bucles y regiones paralelas.

```cpp
class Parallel
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [ParallelLoopResult](../parallelloopresult/) [ForEach](./foreach/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<TSource\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[ParallelOptions](../paralleloptions/)\>\&, const [Action](../../system/action/)\<TSource\>\&) | Ejecuta una operación foreach en un IEnumerable en la que las iteraciones pueden ejecutarse en paralelo. |
| static [ParallelLoopResult](../parallelloopresult/) [ForEach](./foreach/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<TSource\>\>\&, const [Action](../../system/action/)\<TSource\>\&) | Ejecuta una operación foreach en un IEnumerable en la que las iteraciones pueden ejecutarse en paralelo. |
## Observaciones


Esta clase proporciona métodos para la ejecución paralela de bucles y operaciones. 
## Ver también

* Espacio de nombres [System::Threading::Tasks](../)
* Biblioteca [Aspose.Slides](../../)