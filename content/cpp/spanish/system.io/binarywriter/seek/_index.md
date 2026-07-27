---
title: Seek()
second_title: Referencia de API de Aspose.Slides para C++
description: Establece la posición del flujo representado por el objeto actual.
type: docs
weight: 79
url: /es/system.io/binarywriter/seek/
---
## BinaryWriter::Seek(int, System::IO::SeekOrigin) método

Establece la posición del flujo representado por el objeto actual.

```cpp
int64_t System::IO::BinaryWriter::Seek(int offset, System::IO::SeekOrigin origin=System::IO::SeekOrigin::Begin)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| offset | int | El desplazamiento en bytes relativo a una posición especificada por **origin** |
| origin | [System::IO::SeekOrigin](../../seekorigin/) | Especifica la posición desde la cual y la dirección hacia la cual se calcula el desplazamiento |

### Valor devuelto

La nueva posición del flujo

## Ver también

* Enum [SeekOrigin](../../seekorigin/)
* Class [BinaryWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)