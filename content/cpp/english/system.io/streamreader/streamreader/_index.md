---
title: StreamReader()
second_title: Aspose.Slides for C++ API Reference
description: Constructs an instance of StreamReader object that reads characters from the specified underlying stream using UTF-8 encoding and a buffer with default size of 1024 bytes.
type: docs
weight: 1
url: /system.io/streamreader/streamreader/
---
## StreamReader::StreamReader(const SharedPtr\<Stream\>\&) constructor


Constructs an instance of [StreamReader](../) object that reads characters from the specified underlying stream using UTF-8 encoding and a buffer with default size of 1024 bytes.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | The underlying stream to read characters from |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, bool) constructor


Constructs an instance of [StreamReader](../) object that reads characters from the specified underlying stream using UTF-8 encoding and a buffer with default size of 1024 bytes. A parameter specifies if byte order mark detection should be enabled.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, bool detectEncodingFromByteOrderMarks)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | The underlying stream to read characters from |
| detectEncodingFromByteOrderMarks | **bool** | True to look for byte order marks at the beginning of the stream, otherwise - false |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&) constructor


Constructs an instance of [StreamReader](../) object that reads characters from the specified underlying stream using the specified encoding and a buffer with default size of 1024 bytes.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | The underlying stream to read characters from |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | The encoding to use |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool) constructor


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

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool, int) constructor


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

## StreamReader::StreamReader(const System::String\&) constructor


Constructs an instance of [StreamReader](../) object that reads characters from the specified file using UTF-8 encoding and a buffer with default size of 4096 bytes.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | The path of the file to read characters from |

## StreamReader::StreamReader(const System::String\&, bool) constructor


Constructs an instance of [StreamReader](../) object that reads characters from the specified file using UTF-8 encoding and a buffer with default size of 4096 bytes. A parameter specifies if byte order mark detection should be enabled.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, bool detectEncodingFromByteOrderMarks)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | The path of the file to read characters from |
| detectEncodingFromByteOrderMarks | **bool** | True to look for byte order marks at the beginning of the file, otherwise - false |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&) constructor


Constructs an instance of [StreamReader](../) object that reads characters from the specified file using the specified encoding and a buffer with default size of 4096 bytes.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | The path of the file to read characters from |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | The encoding to use |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool) constructor


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

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool, int) constructor


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

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [Stream](../../stream/)
* Class [StreamReader](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)