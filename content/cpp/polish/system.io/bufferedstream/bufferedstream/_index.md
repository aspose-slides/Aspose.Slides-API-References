---
title: BufferedStream()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Tworzy obiekt BufferedStream, który otacza określony strumień i używa bufora o długości 4096 bajtów.
type: docs
weight: 1
url: /pl/system.io/bufferedstream/bufferedstream/
---
## BufferedStream::BufferedStream(const SharedPtr\<Stream\>\&) konstruktor


Tworzy obiekt [BufferedStream](../), który otacza określony strumień i używa bufora o długości 4096 bajtów.

```cpp
System::IO::BufferedStream::BufferedStream(const SharedPtr<Stream> &stream)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Podstawowy obiekt [Stream](../../stream/) |

## BufferedStream::BufferedStream(const SharedPtr\<Stream\>\&, int) konstruktor


Tworzy obiekt [BufferedStream](../), który otacza określony strumień i używa bufora o podanym rozmiarze.

```cpp
System::IO::BufferedStream::BufferedStream(const SharedPtr<Stream> &stream, int bufferSize)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Podstawowy obiekt [Stream](../../stream/) |
| bufferSize | int | Rozmiar bufora w bajtach |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Stream](../../stream/)
* Klasa [BufferedStream](../)
* Przestrzeń nazw [System::IO](../../)
* Library [Aspose.Slides](../../../)