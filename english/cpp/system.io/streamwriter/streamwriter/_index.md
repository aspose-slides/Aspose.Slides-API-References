---
title: StreamWriter()
second_title: Aspose.Slides for C++ API Reference
description: Constructs an instance of StreamWriter object that writes characters to the specified underlying stream using UTF-8 encoding and a buffer with default size of 1024 bytes.
type: docs
weight: 1
url: /cpp/system.io/streamwriter/streamwriter/
---
## StreamWriter::StreamWriter(const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\&) constructor


Constructs an instance of [StreamWriter](../) object that writes characters to the specified underlying stream using UTF-8 encoding and a buffer with default size of 1024 bytes.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | The underlying stream to write characters to |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
## StreamWriter::StreamWriter(const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\&, const [EncodingPtr](../../../system/encodingptr/)\&) constructor


Constructs an instance of [StreamWriter](../) object that writes characters to the specified underlying stream using the specified encoding and a buffer with default size of 1024 bytes.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | The underlying stream to write characters to |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | The encoding to use |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
## StreamWriter::StreamWriter(const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\&, const [EncodingPtr](../../../system/encodingptr/)\&, int, **bool**) constructor


Constructs an instance of [StreamWriter](../) object that writes characters to the specified underlying stream using the specified encoding and a buffer of the specified size. A parameter specifies whether the underlying stream should be closed when the [StreamWriter](../) object is disposed.

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

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
## StreamWriter::StreamWriter(const [String](../../../system/string/)\&) constructor


Constructs an instance of [StreamWriter](../) object that writes characters to the specified file using UTF-8 encoding and a buffer with default size of 1024 bytes.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | The path of the file to write characters to |

## See Also

* Class [String](../../../system/string/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
## StreamWriter::StreamWriter(const [String](../../../system/string/)\&, **bool**, const [EncodingPtr](../../../system/encodingptr/)\&) constructor


Constructs an instance of [StreamWriter](../) object that writes characters to the specified file using the specified encoding and a buffer with default size of 1024 bytes. A parameter specifies whether the data should be appened to the file or the file should be overwritten.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked())
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | The path of the file to write characters to |
| append | **bool** | Specifies whether the data should be appended to the specified file (true) or the file should be overwritten (false) |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | The encoding to use |

## See Also

* Class [String](../../../system/string/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
## StreamWriter::StreamWriter(const [String](../../../system/string/)\&, **bool**, const [EncodingPtr](../../../system/encodingptr/)\&, int) constructor


Constructs an instance of [StreamWriter](../) object that writes characters to the specified file using the specified encoding and buffer size. A parameter specifies whether the data should be appened to the file or the file should be overwritten.

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

## See Also

* Class [String](../../../system/string/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [StreamWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
