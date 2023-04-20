---
title: BinaryReader()
second_title: Aspose.Slides for C++ API Reference
description: Constructs an instance of BinaryReader class that reads data from the specified stream using UTF-8 encoding.
type: docs
weight: 1
url: /cpp/system.io/binaryreader/binaryreader/
---
## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&) constructor


Constructs an instance of [BinaryReader](../) class that reads data from the specified stream using UTF-8 encoding.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | The input stream |

## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&) constructor


Constructs an instance of [BinaryReader](../) class that reads data from the specified stream using the specified encoding.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | The input stream |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | The encoding to use |

## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&, bool) constructor


Constructs an instance of [BinaryReader](../) class that reads data from the specified stream using the specified encoding.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding, bool leaveOpen)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | The input stream |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | The encoding to use |
| leaveOpen | **bool** | Specifies whether the stream **input** should be left open (true) after the current object has been disposed or not (false) |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Class [BinaryReader](../)
* Class [Encoding](../../../system.text/encoding/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)