---
title: BufferedStream()
second_title: Referencia de la API de Aspose.Slides para C++
description: Construye un objeto BufferedStream que envuelve el stream especificado y utiliza un búfer de 4096 bytes de longitud.
type: docs
weight: 1
url: /es/system.io/bufferedstream/bufferedstream/
---
## BufferedStream::BufferedStream(const SharedPtr\<Stream\>\&) constructor


Construye un objeto [BufferedStream](../) que envuelve el stream especificado y utiliza un búfer de 4096 bytes de longitud.

```cpp
System::IO::BufferedStream::BufferedStream(const SharedPtr<Stream> &stream)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | El objeto subyacente [Stream](../../stream/) |

## BufferedStream::BufferedStream(const SharedPtr\<Stream\>\&, int) constructor


Construye un objeto [BufferedStream](../) que envuelve el stream especificado y utiliza un búfer del tamaño especificado.

```cpp
System::IO::BufferedStream::BufferedStream(const SharedPtr<Stream> &stream, int bufferSize)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | El objeto subyacente [Stream](../../stream/) |
| bufferSize | int | El tamaño del búfer en bytes |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Stream](../../stream/)
* Clase [BufferedStream](../)
* Espacio de nombres [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)