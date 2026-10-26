---
title: VerifySignature()
second_title: Aspose.Slides for C++ API 參考
description: 驗證資料雜湊的簽章。
type: docs
weight: 40
url: /zh-hant/system.security.cryptography/rsapkcs1signaturedeformatter/verifysignature/
---
## RSAPKCS1SignatureDeformatter::VerifySignature(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) 方法

驗證資料雜湊的簽章。

```cpp
virtual bool System::Security::Cryptography::RSAPKCS1SignatureDeformatter::VerifySignature(System::ArrayPtr<uint8_t> rgbHash, System::ArrayPtr<uint8_t> rgbSignature) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 針對資料計算的雜湊。 |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 收到的資料簽章。 |

### 回傳值

若簽章有效則回傳 True，否則回傳 false。

## 參見

* 型別定義 [ArrayPtr](../../../system/arrayptr/)
* 類別 [RSAPKCS1SignatureDeformatter](../)
* 命名空間 [System::Security::Cryptography](../../)
* 程式庫 [Aspose.Slides](../../../)