---
title: VerifyData()
second_title: Aspose.Slides C++ API 參考
description: 檢查資料簽名。
type: docs
weight: 209
url: /zh-hant/system.security.cryptography/rsacryptoserviceprovider/verifydata/
---
## RSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const SharedPtr\<Object\>\&, const ByteArrayPtr\&) 方法

檢查資料簽名。

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyData(const ByteArrayPtr &buffer, const SharedPtr<Object> &halg, const ByteArrayPtr &signature)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) 用於檢查簽名。 |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 要使用的雜湊演算法。 |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 接收的簽名。 |

### 傳回值

若簽名有效則回傳 true，否則回傳 false。

## 另請參閱

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [Object](../../../system/object/)
* 類別 [RSACryptoServiceProvider](../)
* 命名空間 [System::Security::Cryptography](../../)
* 程式庫 [Aspose.Slides](../../../)