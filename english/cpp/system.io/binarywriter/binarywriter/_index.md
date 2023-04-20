---
title: BinaryWriter()
second_title: Aspose.Slides for C++ API Reference
description: Constructs an instance of BinaryWriter class that writes data to the specified stream using the specified encoding.
type: docs
weight: 1
url: /cpp/system.io/binarywriter/binarywriter/
---
## BinaryWriter::BinaryWriter(const StreamPtr\&, const EncodingPtr\&, bool) constructor


Constructs an instance of [BinaryWriter](../) class that writes data to the specified stream using the specified encoding.

```cpp
System::IO::BinaryWriter::BinaryWriter(const StreamPtr &stream, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked(), bool leaveopen=false)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | The output stream |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | The encoding to use |
| leaveopen | **bool** | Specifies whether the stream **stream** should be left open (true) after the current object has been disposed or not (false) |

## See Also

* Typedef [StreamPtr](../../../system/streamptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [BinaryWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)