---
title: BufferedStream()
second_title: Aspose.Slides voor C++ API-referentie
description: Construeert een BufferedStream object dat de opgegeven stream omsluit en een buffer van 4096 bytes gebruikt.
type: docs
weight: 1
url: /nl/system.io/bufferedstream/bufferedstream/
---
## BufferedStream::BufferedStream(const SharedPtr\<Stream\>\&) constructor

Construeert een [BufferedStream](../) object dat de opgegeven stream omsluit en een buffer van 4096 bytes gebruikt.

```cpp
System::IO::BufferedStream::BufferedStream(const SharedPtr<Stream> &stream)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Het onderliggende [Stream](../../stream/) object |

## BufferedStream::BufferedStream(const SharedPtr\<Stream\>\&, int) constructor

Construeert een [BufferedStream](../) object dat de opgegeven stream omsluit en een buffer van de opgegeven grootte gebruikt.

```cpp
System::IO::BufferedStream::BufferedStream(const SharedPtr<Stream> &stream, int bufferSize)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Het onderliggende [Stream](../../stream/) object |
| bufferSize | int | De grootte van de buffer in bytes |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Stream](../../stream/)
* Klasse [BufferedStream](../)
* Naamruimte [System::IO](../../)
* Bibliotheek [Aspose.Slides](../../../)