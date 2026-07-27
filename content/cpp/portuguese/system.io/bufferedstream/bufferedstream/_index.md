---
title: BufferedStream()
second_title: Referência da API Aspose.Slides para C++
description: Constrói um objeto BufferedStream que encapsula o fluxo especificado e usa um buffer de 4096 bytes.
type: docs
weight: 1
url: /pt/system.io/bufferedstream/bufferedstream/
---
## BufferedStream::BufferedStream(const SharedPtr\<Stream\>\&) constructor

Constrói um objeto [BufferedStream](../) que encapsula o fluxo especificado e usa um buffer de 4096 bytes.

```cpp
System::IO::BufferedStream::BufferedStream(const SharedPtr<Stream> &stream)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | O objeto [Stream](../../stream/) subjacente |

## BufferedStream::BufferedStream(const SharedPtr\<Stream\>\&, int) constructor

Constrói um objeto [BufferedStream](../) que encapsula o fluxo especificado e usa um buffer do tamanho especificado.

```cpp
System::IO::BufferedStream::BufferedStream(const SharedPtr<Stream> &stream, int bufferSize)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | O objeto [Stream](../../stream/) subjacente |
| bufferSize | int | O tamanho do buffer em bytes |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Stream](../../stream/)
* Classe [BufferedStream](../)
* Namespace [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)