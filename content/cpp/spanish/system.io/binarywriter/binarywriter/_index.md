---
title: BinaryWriter()
second_title: Referencia de la API de Aspose.Slides para C++
description: Construye una instancia de la clase BinaryWriter que escribe datos en el flujo especificado usando la codificación especificada.
type: docs
weight: 1
url: /es/system.io/binarywriter/binarywriter/
---
## BinaryWriter::BinaryWriter(const StreamPtr\&, const EncodingPtr\&, bool) constructor

Construye una instancia de la clase [BinaryWriter](../) que escribe datos en el flujo especificado usando la codificación especificada.

```cpp
System::IO::BinaryWriter::BinaryWriter(const StreamPtr &stream, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked(), bool leaveopen=false)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | El flujo de salida |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | La codificación a usar |
| leaveopen | **bool** | Especifica si el flujo **stream** debe permanecer abierto (true) después de que el objeto actual haya sido eliminado o no (false) |

## Ver también

* Typedef [StreamPtr](../../../system/streamptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [BinaryWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)