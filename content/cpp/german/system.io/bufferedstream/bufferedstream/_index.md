---
title: BufferedStream()
second_title: Aspose.Slides für C++ API-Referenz
description: Konstruiert ein BufferedStream-Objekt, das den angegebenen Stream einhüllt und einen 4096 Byte langen Puffer verwendet.
type: docs
weight: 1
url: /de/system.io/bufferedstream/bufferedstream/
---
## BufferedStream::BufferedStream(const SharedPtr\<Stream\>\&) Konstruktor

Konstruiert ein [BufferedStream](../)-Objekt, das den angegebenen Stream einhüllt und einen 4096 Byte langen Puffer verwendet.

```cpp
System::IO::BufferedStream::BufferedStream(const SharedPtr<Stream> &stream)
```

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Das zugrunde liegende [Stream](../../stream/)-Objekt |

## BufferedStream::BufferedStream(const SharedPtr\<Stream\>\&, int) Konstruktor

Konstruiert ein [BufferedStream](../)-Objekt, das den angegebenen Stream einhüllt und einen Puffer der angegebenen Größe verwendet.

```cpp
System::IO::BufferedStream::BufferedStream(const SharedPtr<Stream> &stream, int bufferSize)
```

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Das zugrunde liegende [Stream](../../stream/)-Objekt |
| bufferSize | int | Die Größe des Puffers in Bytes |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Stream](../../stream/)
* Klasse [BufferedStream](../)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)