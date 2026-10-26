---
title: StreamWriter()
second_title: Aspose.Slides dla C++ Referencja API
description: Tworzy instancję obiektu StreamWriter, który zapisuje znaki do określonego strumienia bazowego przy użyciu kodowania UTF-8 i bufora o domyślnym rozmiarze 1024 bajtów.
type: docs
weight: 1
url: /pl/system.io/streamwriter/streamwriter/
---
## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&) constructor

Tworzy instancję obiektu [StreamWriter](../), który zapisuje znaki do określonego strumienia bazowego przy użyciu kodowania UTF-8 i bufora o domyślnym rozmiarze 1024 bajtów.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | The underlying stream to write characters to |

## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&) constructor

Tworzy instancję obiektu [StreamWriter](../), który zapisuje znaki do określonego strumienia bazowego przy użyciu podanego kodowania i bufora o domyślnym rozmiarze 1024 bajtów.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | The underlying stream to write characters to |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | The encoding to use |

## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&, int, bool) constructor

Tworzy instancję obiektu [StreamWriter](../), który zapisuje znaki do określonego strumienia bazowego przy użyciu podanego kodowania oraz bufora o określonym rozmiarze. Parametr określa, czy strumień bazowy ma zostać zamknięty po zwolnieniu obiektu [StreamWriter](../).

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, int buffer_size, bool leave_open=false)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | The underlying stream to write characters to |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | The encoding to use |
| buffer_size | int | The minimum size of the buffer in bytes |
| leave_open | **bool** | Specifies whether the underlying stream should be left open after the current [StreamWriter](../) object is disposed |

## StreamWriter::StreamWriter(const String\&) constructor

Tworzy instancję obiektu [StreamWriter](../), który zapisuje znaki do określonego pliku przy użyciu kodowania UTF-8 i bufora o domyślnym rozmiarze 1024 bajtów.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | The path of the file to write characters to |

## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&) constructor

Tworzy instancję obiektu [StreamWriter](../), który zapisuje znaki do określonego pliku przy użyciu podanego kodowania i bufora o domyślnym rozmiarze 1024 bajtów. Parametr określa, czy dane mają być dopisane do pliku, czy plik ma być nadpisany.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked())
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | The path of the file to write characters to |
| append | **bool** | Specifies whether the data should be appended to the specified file (true) or the file should be overwritten (false) |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | The encoding to use |

## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&, int) constructor

Tworzy instancję obiektu [StreamWriter](../), który zapisuje znaki do określonego pliku przy użyciu podanego kodowania i rozmiaru bufora. Parametr określa, czy dane mają być dopisane do pliku, czy plik ma być nadpisany.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding, int buffer_size)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | The path of the file to write characters to |
| append | **bool** | Specifies whether the data should be appended to the specified file (true) or the file should be overwritten (false) |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | The encoding to use |
| buffer_size | int | The size of buffer to use |

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Definicja typu [EncodingPtr](../../../system/encodingptr/)
* Klasa [Stream](../../stream/)
* Klasa [StreamWriter](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [System::IO](../../)
* Biblioteka [Aspose.Slides](../../../)