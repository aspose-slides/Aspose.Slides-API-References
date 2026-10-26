---
title: VerifyHash()
second_title: Aspose.Slides for C++ API 參考
description: 檢查資料簽章。
type: docs
weight: 118
url: /zh-hant/system.security.cryptography/ecdsa/verifyhash/
---
## ECDsa::VerifyHash(ByteArrayPtr, ByteArrayPtr) 方法

檢查資料簽章。

```cpp
virtual bool System::Security::Cryptography::ECDsa::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | 接收到的資料所計算的雜湊。 |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | 接收到的簽章。 |

### 傳回值

True 為簽章有效時回傳，否則回傳 false。

## 參見

* 型別別名 [ByteArrayPtr](../../../system/bytearrayptr/)
* 類別 [ECDsa](../)
* 命名空間 [System::Security::Cryptography](../../)
* 函式庫 [Aspose.Slides](../../../)