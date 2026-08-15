---
title: VerifySignature()
second_title: Aspose.Slides for C++ API 參考文件
description: 驗證指定資料的 DSA 簽章。
type: docs
weight: 14
url: /zh-hant/system.security.cryptography/dsa/verifysignature/
---
## DSA::VerifySignature(ByteArrayPtr, ByteArrayPtr) 方法

驗證指定資料的 [DSA](../) 簽章。

```cpp
virtual bool System::Security::Cryptography::DSA::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| rgb_hash | [ByteArrayPtr](../../../system/bytearrayptr/) | 使用 **rgb_signature** 簽署的 [Data](../../../system.data/)。 |
| rgb_signature | [ByteArrayPtr](../../../system/bytearrayptr/) | [DSA](../) 簽章。 |

### 返回值

true - 如果 **rgb_signature** 與在 **rgb_hash** 上計算的 [DSA](../) 簽章相匹配，否則為 false。

## 另見

* 類型別名 [ByteArrayPtr](../../../system/bytearrayptr/)
* 類別 [DSA](../)
* 命名空間 [System::Security::Cryptography](../../)
* 函式庫 [Aspose.Slides](../../../)