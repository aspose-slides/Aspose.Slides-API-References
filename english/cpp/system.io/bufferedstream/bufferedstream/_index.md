---
title: BufferedStream()
second_title: Aspose.Slides for C++ API Reference
description: Constructs an BufferedStream object that wraps the specified stream and uses a 4096 bytes long buffer.
type: docs
weight: 1
url: /cpp/system.io/bufferedstream/bufferedstream/
---
## BufferedStream::BufferedStream(const SharedPtr\<Stream\>\&) constructor


Constructs an [BufferedStream](../) object that wraps the specified stream and uses a 4096 bytes long buffer.

```cpp
System::IO::BufferedStream::BufferedStream(const SharedPtr<Stream> &stream)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | The underlying [Stream](../../stream/) object |

## BufferedStream::BufferedStream(const SharedPtr\<Stream\>\&, int) constructor


Constructs an [BufferedStream](../) object that wraps the specified stream and uses a buffer of the specified size.

```cpp
System::IO::BufferedStream::BufferedStream(const SharedPtr<Stream> &stream, int bufferSize)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | The underlying [Stream](../../stream/) object |
| bufferSize | int | The size of the buffer in bytes |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Class [BufferedStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)