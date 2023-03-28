---
title: SignHash()
second_title: Aspose.Slides for C++ API Reference
description: Computes the signature of specified input value.
type: docs
weight: 196
url: /cpp/system.security.cryptography/dsacryptoserviceprovider/signhash/
---
## DSACryptoServiceProvider::SignHash(const [ByteArrayPtr](../../../system/bytearrayptr/)\&, const [String](../../../system/string/)\&) method


Computes the signature of specified input value.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignHash(const ByteArrayPtr &rgb_hash, const String &str)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Hash value of data to be signed. |
| str | const [String](../../../system/string/)\& | Hash algorithm identifier used to create the hash. |

### Return Value

[DSA](../../dsa/) signature for specified data.

## See Also

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [String](../../../system/string/)
* Class [DSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)
