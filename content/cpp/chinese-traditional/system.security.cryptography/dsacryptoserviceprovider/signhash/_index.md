---
title: SignHash()
second_title: Aspose.Slides for C++ API 參考
description: 計算指定輸入值的簽名。
type: docs
weight: 196
url: /zh-hant/system.security.cryptography/dsacryptoserviceprovider/signhash/
---
## DSACryptoServiceProvider::SignHash(const ByteArrayPtr\&, const String\&) 方法

計算指定輸入值的簽名。

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignHash(const ByteArrayPtr &rgb_hash, const String &str)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 待簽名資料的雜湊值。 |
| str | const [String](../../../system/string/)\& | 用於產生雜湊的雜湊演算法標識符。 |

### 返回值

[DSA](../../dsa/) 指定資料的簽名。

## 參見

* 類型別名 [ByteArrayPtr](../../../system/bytearrayptr/)
* 類別 [String](../../../system/string/)
* 類別 [DSACryptoServiceProvider](../)
* 命名空間 [System::Security::Cryptography](../../)
* 函式庫 [Aspose.Slides](../../../)