---
title: VerifyHash()
second_title: Aspose.Slides for C++ API 參考
description: 檢查資料簽章。
type: docs
weight: 183
url: /zh-hant/system.security.cryptography/ecdsabotan/verifyhash/
---
## ECDsaBotan::VerifyHash(ByteArrayPtr, ByteArrayPtr) 方法


檢查資料簽章。

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | 接收資料的雜湊。 |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | 接收的簽章。 |

### 返回值

如果簽章有效則為 true，否則為 false。

## 另見

* 類型別名 [ByteArrayPtr](../../../system/bytearrayptr/)
* 類別 [ECDsaBotan](../)
* 命名空間 [System::Security::Cryptography](../../)
* 函式庫 [Aspose.Slides](../../../)