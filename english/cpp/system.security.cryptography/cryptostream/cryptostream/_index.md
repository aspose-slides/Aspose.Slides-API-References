---
title: CryptoStream()
second_title: Aspose.Slides for C++ API Reference
description: Constructor.
type: docs
weight: 1
url: /cpp/system.security.cryptography/cryptostream/cryptostream/
---
## CryptoStream::CryptoStream(const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\&, const [SharedPtr](../../../system/sharedptr/)\<[ICryptoTransform](../../icryptotransform/)\>\&, [CryptoStreamMode](../../cryptostreammode/)) constructor


Constructor.

```cpp
System::Security::Cryptography::CryptoStream::CryptoStream(const SharedPtr<System::IO::Stream> &stream, const SharedPtr<ICryptoTransform> &transform, CryptoStreamMode mode)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Stream to wrap. |
| transform | const [SharedPtr](../../../system/sharedptr/)\<[ICryptoTransform](../../icryptotransform/)\>\& | Transformation function to process data with when sending/reading it to/from stream. |
| mode | [CryptoStreamMode](../../cryptostreammode/) | Stream direction. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [ICryptoTransform](../../icryptotransform/)
* Enum [CryptoStreamMode](../../cryptostreammode/)
* Class [CryptoStream](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)
