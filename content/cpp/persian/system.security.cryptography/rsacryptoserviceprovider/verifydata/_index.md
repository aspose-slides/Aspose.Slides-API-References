---
title: VerifyData()
second_title: Aspose.Slides برای مرجع API C++
description: امضای داده را بررسی می‌کند.
type: docs
weight: 209
url: /fa/system.security.cryptography/rsacryptoserviceprovider/verifydata/
---
## RSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const SharedPtr\<Object\>\&, const ByteArrayPtr\&) متد

چک می‌کند امضای داده.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyData(const ByteArrayPtr &buffer, const SharedPtr<Object> &halg, const ByteArrayPtr &signature)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) برای بررسی امضا. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | الگوریتم هش برای استفاده. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | امضای دریافت شده. |

### مقدار بازگشتی

True اگر امضا معتبر باشد، false در غیر اینصورت.

## موارد مرتبط

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)