---
title: BufferedStream()
second_title: Aspose.Slides C++ API-referencia
description: Létrehoz egy BufferedStream objektumot, amely becsomagolja a megadott adatfolyamot, és egy 4096 bájt hosszú puffert használ.
type: docs
weight: 1
url: /hu/system.io/bufferedstream/bufferedstream/
---
## BufferedStream::BufferedStream(const SharedPtr\<Stream\>\&) konstruktor

Létrehoz egy [BufferedStream](../) objektumot, amely becsomagolja a megadott adatfolyamot, és 4096 bájt hosszú puffert használ.

```cpp
System::IO::BufferedStream::BufferedStream(const SharedPtr<Stream> &stream)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Az alapul szolgáló [Stream](../../stream/) objektum |

## BufferedStream::BufferedStream(const SharedPtr\<Stream\>\&, int) konstruktor

Létrehoz egy [BufferedStream](../) objektumot, amely becsomagolja a megadott adatfolyamot, és a megadott méretű puffert használ.

```cpp
System::IO::BufferedStream::BufferedStream(const SharedPtr<Stream> &stream, int bufferSize)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Az alapul szolgáló [Stream](../../stream/) objektum |
| bufferSize | int | A puffert mérete bájtokban |

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [Stream](../../stream/)
* Osztály [BufferedStream](../)
* Névtér [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)