---
title: Seek()
second_title: Referencia de la API de Aspose.Slides para C++
description: Establece la posición del flujo representado por el objeto actual.
type: docs
weight: 105
url: /es/system.io/memorystream/seek/
---
## MemoryStream::Seek(int64_t, SeekOrigin) método

Establece la posición del flujo representado por el objeto actual.

```cpp
int64_t System::IO::MemoryStream::Seek(int64_t offset, SeekOrigin origin) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| offset | **int64_t** | El desplazamiento de bytes relativo a una posición especificada por **origin** |
| origin | [SeekOrigin](../../seekorigin/) | Especifica la posición desde la cual y la dirección hacia la cual se calcula el desplazamiento |

### Valor de retorno

La nueva posición del flujo

## Ver también

* Enumeración [SeekOrigin](../../seekorigin/)
* Clase [MemoryStream](../)
* Espacio de nombres [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)