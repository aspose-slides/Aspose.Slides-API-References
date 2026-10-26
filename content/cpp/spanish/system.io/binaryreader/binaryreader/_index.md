---
title: BinaryReader()
second_title: Referencia de la API de Aspose.Slides para C++
description: Construye una instancia de la clase BinaryReader que lee datos del flujo especificado usando codificación UTF-8.
type: docs
weight: 1
url: /es/system.io/binaryreader/binaryreader/
---
## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&) constructor

Construye una instancia de la clase [BinaryReader](../) que lee datos del flujo especificado usando codificación UTF-8.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | El flujo de entrada |

## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&) constructor

Construye una instancia de la clase [BinaryReader](../) que lee datos del flujo especificado usando la codificación especificada.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | El flujo de entrada |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | La codificación a usar |

## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&, bool) constructor

Construye una instancia de la clase [BinaryReader](../) que lee datos del flujo especificado usando la codificación especificada.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding, bool leaveOpen)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | El flujo de entrada |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | La codificación a usar |
| leaveOpen | **bool** | Especifica si el flujo **input** debe permanecer abierto (true) después de que el objeto actual haya sido eliminado o no (false) |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Stream](../../stream/)
* Clase [BinaryReader](../)
* Clase [Encoding](../../../system.text/encoding/)
* Espacio de nombres [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)