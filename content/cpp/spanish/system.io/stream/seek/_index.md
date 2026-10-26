---
title: Seek()
second_title: Referencia de API de Aspose.Slides para C++
description: Establece la posición del flujo representado por el objeto actual.
type: docs
weight: 79
url: /es/system.io/stream/seek/
---
## Stream::Seek(int64_t, SeekOrigin) método

Establece la posición del flujo representado por el objeto actual.

```cpp
virtual int64_t System::IO::Stream::Seek(int64_t offset, SeekOrigin origin)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| offset | **int64_t** | El desplazamiento en bytes relativo a una posición especificada por **origin** |
| origin | [SeekOrigin](../../seekorigin/) | Especifica la posición desde la cual y la dirección hacia la cual se calcula el desplazamiento |

### Valor de retorno

La nueva posición del flujo

## Ver también

* Enumeración [SeekOrigin](../../seekorigin/)
* Clase [Stream](../)
* Espacio de nombres [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)