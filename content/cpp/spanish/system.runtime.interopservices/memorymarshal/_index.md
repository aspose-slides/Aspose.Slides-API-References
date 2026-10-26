---
title: MemoryMarshal
second_title: Referencia de API de Aspose.Slides para C++
description: Proporciona una implementación de marshaling de memoria. Solo para compatibilidad con código traducido, ya que no se admite código administrado en el lado C++. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio.
type: docs
weight: 27
url: /es/system.runtime.interopservices/memorymarshal/
---
## MemoryMarshal clase


Proporciona una implementación de marshaling de memoria. Solo para compatibilidad con código traducido, ya que no se admite código administrado en el lado C++. Este es un tipo estático sin servicios de instancia. Nunca debe crear instancias de él por ningún medio.

```cpp
class MemoryMarshal
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [Span](../../system/span/)\<**uint8_t**\> [AsBytes](./asbytes/)(const [Span](../../system/span/)\<T\>\&) | Convierte un [Span](../../system/span/) de un tipo primitivo T a [Span](../../system/span/) de bytes. |
| static [Span](../../system/span/)\<TTo\> [Cast](./cast/)(const [Span](../../system/span/)\<TFrom\>\&) | Convierte un [Span](../../system/span/) de un tipo primitivo TFrom a otro tipo primitivo TTo. |
## Ver también

* Espacio de nombres [System::Runtime::InteropServices](../)
* Biblioteca [Aspose.Slides](../../)