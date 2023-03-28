---
title: StreamReader()
second_title: Aspose.Slides for C++ API Reference
description: Constructs an instance of StreamReader object that reads characters from the specified underlying stream using UTF-8 encoding and a buffer with default size of 1024 bytes.
type: docs
weight: 1
url: /cpp/system.io/streamreader/streamreader/
---
## StreamReader::StreamReader(const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\&) constructor


Constructs an instance of [StreamReader](../) object that reads characters from the specified underlying stream using UTF-8 encoding and a buffer with default size of 1024 bytes.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | The underlying stream to read characters from |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
## StreamReader::StreamReader(const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\&, **bool**) constructor


Constructs an instance of [StreamReader](../) object that reads characters from the specified underlying stream using UTF-8 encoding and a buffer with default size of 1024 bytes. A parameter specifies if byte order mark detection should be enabled.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, bool detectEncodingFromByteOrderMarks)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | The underlying stream to read characters from |
| detectEncodingFromByteOrderMarks | **bool** | True to look for byte order marks at the beginning of the stream, otherwise - false |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
## StreamReader::StreamReader(const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\&, const [EncodingPtr](../../../system/encodingptr/)\&) constructor


Constructs an instance of [StreamReader](../) object that reads characters from the specified underlying stream using the specified encoding and a buffer with default size of 1024 bytes.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | The underlying stream to read characters from |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | The encoding to use |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
## StreamReader::StreamReader(const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\&, const [EncodingPtr](../../../system/encodingptr/)\&, **bool**) constructor


Constructs an instance of [StreamReader](../) object that reads characters from the specified underlying stream using the specified encoding and a buffer with default size of 1024 bytes. A parameter specifies if byte order mark detection should be enabled.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | The underlying stream to read characters from |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | The encoding to use |
| detectEncodingFromByteOrderMarks | **bool** | True to look for byte order marks at the beginning of the stream, otherwise - false |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
## StreamReader::StreamReader(const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\&, const [EncodingPtr](../../../system/encodingptr/)\&, **bool**, int) constructor


Constructs an instance of [StreamReader](../) object that reads characters from the specified underlying stream using the specified encoding and a buffer of the specified size. A parameter specifies if byte order mark detection should be enabled.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | The underlying stream to read characters from |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | The encoding to use |
| detectEncodingFromByteOrderMarks | **bool** | True to look for byte order marks at the beginning of the stream, otherwise - false |
| bufferSize | int | The minimum size of the buffer in bytes |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
## StreamReader::StreamReader(const [System::String](../../../system/string/)\&) constructor


Constructs an instance of [StreamReader](../) object that reads characters from the specified file using UTF-8 encoding and a buffer with default size of 4096 bytes.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | The path of the file to read characters from |

## See Also

* Class [String](../../../system/string/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
## StreamReader::StreamReader(const [System::String](../../../system/string/)\&, **bool**) constructor


Constructs an instance of [StreamReader](../) object that reads characters from the specified file using UTF-8 encoding and a buffer with default size of 4096 bytes. A parameter specifies if byte order mark detection should be enabled.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, bool detectEncodingFromByteOrderMarks)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | The path of the file to read characters from |
| detectEncodingFromByteOrderMarks | **bool** | True to look for byte order marks at the beginning of the file, otherwise - false |

## See Also

* Class [String](../../../system/string/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
## StreamReader::StreamReader(const [System::String](../../../system/string/)\&, const [EncodingPtr](../../../system/encodingptr/)\&) constructor


Constructs an instance of [StreamReader](../) object that reads characters from the specified file using the specified encoding and a buffer with default size of 4096 bytes.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | The path of the file to read characters from |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | The encoding to use |

## See Also

* Class [String](../../../system/string/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
## StreamReader::StreamReader(const [System::String](../../../system/string/)\&, const [EncodingPtr](../../../system/encodingptr/)\&, **bool**) constructor


Constructs an instance of [StreamReader](../) object that reads characters from the specified underlying stream using the specified encoding and a buffer with default size of 4096 bytes. A parameter specifies if byte order mark detection should be enabled.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | The path of the file to read characters from |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | The encoding to use |
| detectEncodingFromByteOrderMarks | **bool** | True to look for byte order marks at the beginning of the file, otherwise - false |

## See Also

* Class [String](../../../system/string/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
## StreamReader::StreamReader(const [System::String](../../../system/string/)\&, const [EncodingPtr](../../../system/encodingptr/)\&, **bool**, int) constructor


Constructs an instance of [StreamReader](../) object that reads characters from the specified file using the specified encoding and a buffer of the specified size. A parameter specifies if byte order mark detection should be enabled.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | The path of the file to read characters from |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | The encoding to use |
| detectEncodingFromByteOrderMarks | **bool** | True to look for byte order marks at the beginning of the file, otherwise - false |
| bufferSize | int | The minimum size of the buffer in bytes |

## See Also

* Class [String](../../../system/string/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)
