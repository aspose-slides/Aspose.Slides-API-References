---
title: Seek()
second_title: Referencia de API de Aspose.Slides para C++
description: Establece la posición del flujo representado por el objeto actual.
type: docs
weight: 209
url: /es/system.io/filestream/seek/
---
## FileStream::Seek(int64_t, SeekOrigin) método


Establece la posición del flujo representado por el objeto actual.

```cpp
int64_t System::IO::FileStream::Seek(int64_t offset, SeekOrigin origin) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| offset | **int64_t** | El desplazamiento en bytes relativo a una posición especificada por **origin**. |
| origin | [SeekOrigin](../../seekorigin/) | Especifica la posición desde la cual y la dirección hacia la cual se calcula el desplazamiento. |

### Valor devuelto

La nueva posición del flujo.

## Véase también

* Enumeración [SeekOrigin](../../seekorigin/)
* Clase [FileStream](../)
* Espacio de nombres [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)