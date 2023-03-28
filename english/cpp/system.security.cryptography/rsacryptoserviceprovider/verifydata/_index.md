---
title: VerifyData()
second_title: Aspose.Slides for C++ API Reference
description: Checks data signature.
type: docs
weight: 209
url: /cpp/system.security.cryptography/rsacryptoserviceprovider/verifydata/
---
## RSACryptoServiceProvider::VerifyData(const [ByteArrayPtr](../../../system/bytearrayptr/)\&, const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\&, const [ByteArrayPtr](../../../system/bytearrayptr/)\&) method


Checks data signature.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyData(const ByteArrayPtr &buffer, const SharedPtr<Object> &halg, const ByteArrayPtr &signature)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) to check signature for. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Hash algorithm to use. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signature as received. |

### Return Value

True if signature is valid, false otherwise.

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)
