---
title: Encrypt()
second_title: Aspose.Slides for C++ API 參考文件
description: 加密訊息。未實作。
type: docs
weight: 118
url: /zh-hant/system.security.cryptography/rsacryptoserviceprovider/encrypt/
---
## RSACryptoServiceProvider::Encrypt(const ByteArrayPtr\&, bool) 方法

加密訊息。未實作。

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(const ByteArrayPtr &rgb, bool use_oaep)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| rgb | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) 要加密。 |
| use_oaep | **bool** | True 代表使用 OAEP 填充，false 代表使用 PKCS#1 v1.5 填充。 |

### 返回值

加密的資料陣列。

## RSACryptoServiceProvider::Encrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) 方法

使用指定的填充模式加密輸入資料。

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) 陣列用於加密。 |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | 填充模式。 |

### 返回值

以位元組陣列格式的加密資料。

## 另請參閱

* 類型定義 [ByteArrayPtr](../../../system/bytearrayptr/)
* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [RSACryptoServiceProvider](../)
* 類別 [RSAEncryptionPadding](../../rsaencryptionpadding/)
* 命名空間 [System::Security::Cryptography](../../)
* 函式庫 [Aspose.Slides](../../../)