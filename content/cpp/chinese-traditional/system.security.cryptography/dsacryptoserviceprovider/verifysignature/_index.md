---
title: VerifySignature()
second_title: Aspose.Slides for C++ API 參考手冊
description: 驗證指定資料的 DSA 簽章。
type: docs
weight: 118
url: /zh-hant/system.security.cryptography/dsacryptoserviceprovider/verifysignature/
---
## DSACryptoServiceProvider::VerifySignature(ByteArrayPtr, ByteArrayPtr) 方法

驗證 [DSA](../../dsa/) 簽章於指定的資料。

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature) override
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| rgb_hash | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) 以 **rgb_signature** 簽署。 |
| rgb_signature | [ByteArrayPtr](../../../system/bytearrayptr/) | [DSA](../../dsa/) 簽章。 |

### 回傳值

true - 若 **rgb_signature** 與在 **rgb_hash** 上計算的 [DSA](../../dsa/) 簽章相符，否則為 false。

## 相關參考

* 類型定義 [ByteArrayPtr](../../../system/bytearrayptr/)
* 類別 [DSACryptoServiceProvider](../)
* 命名空間 [System::Security::Cryptography](../../)
* 函式庫 [Aspose.Slides](../../../)