---
title: BufferedStream()
second_title: Aspose.Slides för C++ API-referens
description: Skapar ett BufferedStream-objekt som omsluter den angivna strömmen och använder en 4096 byte lång buffert.
type: docs
weight: 1
url: /sv/system.io/bufferedstream/bufferedstream/
---
## BufferedStream::BufferedStream(const SharedPtr\<Stream\>\&) konstruktor

Skapar ett [BufferedStream](../)-objekt som omsluter den angivna strömmen och använder en 4096 byte lång buffert.

```cpp
System::IO::BufferedStream::BufferedStream(const SharedPtr<Stream> &stream)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Det underliggande [Stream](../../stream/)-objektet |

## BufferedStream::BufferedStream(const SharedPtr\<Stream\>\&, int) konstruktor

Skapar ett [BufferedStream](../)-objekt som omsluter den angivna strömmen och använder en buffert med den angivna storleken.

```cpp
System::IO::BufferedStream::BufferedStream(const SharedPtr<Stream> &stream, int bufferSize)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Det underliggande [Stream](../../stream/)-objektet |
| bufferSize | int | Storleken på bufferten i byte |

## Se även

* Typdef [SharedPtr](../../../system/sharedptr/)
* Klass [Stream](../../stream/)
* Klass [BufferedStream](../)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)