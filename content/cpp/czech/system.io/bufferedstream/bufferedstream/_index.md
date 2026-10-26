---
title: BufferedStream()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vytvoří objekt BufferedStream, který obaluje zadaný stream a používá 4096 bajtů dlouhý buffer.
type: docs
weight: 1
url: /cs/system.io/bufferedstream/bufferedstream/
---
## BufferedStream::BufferedStream(const SharedPtr\<Stream\>\&) konstruktor


Vytvoří objekt [BufferedStream](../), který obaluje zadaný stream a používá 4096 bajtů dlouhý buffer.

```cpp
System::IO::BufferedStream::BufferedStream(const SharedPtr<Stream> &stream)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Podkladový objekt [Stream](../../stream/) |

## BufferedStream::BufferedStream(const SharedPtr\<Stream\>\&, int) konstruktor


Vytvoří objekt [BufferedStream](../), který obaluje zadaný stream a používá buffer o specifikované velikosti.

```cpp
System::IO::BufferedStream::BufferedStream(const SharedPtr<Stream> &stream, int bufferSize)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Podkladový objekt [Stream](../../stream/) |
| bufferSize | int | Velikost bufferu v bajtech |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [Stream](../../stream/)
* třída [BufferedStream](../)
* jmenný prostor [System::IO](../../)
* knihovna [Aspose.Slides](../../../)