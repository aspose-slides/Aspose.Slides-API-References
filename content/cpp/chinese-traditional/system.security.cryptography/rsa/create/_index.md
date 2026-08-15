---
title: Create()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立預設的 RSA 演算法實作。
type: docs
weight: 183
url: /zh-hant/system.security.cryptography/rsa/create/
---
## RSA::Create() 方法

建立預設的 [RSA](../) 演算法實作。

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create()
```

## RSA::Create(const String\&) 方法

建立預設的 [RSA](../) 演算法實作。

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(const String &alg_name)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| alg_name | const [String](../../../system/string/)\& | 必須是 "System.Security.Cryptography.RSACryptoServiceProvider". |

## RSA::Create(int32_t) 方法

建立預設的 [RSA](../) 演_algo_實作，具備指定的金鑰大小。

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(int32_t key_size_in_bits)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| key_size_in_bits | **int32_t** | 金鑰大小（位元為單位）。 |

## RSA::Create(const RSAParameters\&) 方法

建立預設的 [RSA](../) 演算法實作，具備指定的參數。

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(const RSAParameters &parameters)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| parameters | const [RSAParameters](../../rsaparameters/)\& | 用於 [RSA](../) 演算法的參數。 |

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [RSA](../)
* 類別 [String](../../../system/string/)
* 結構 [RSAParameters](../../rsaparameters/)
* 命名空間 [System::Security::Cryptography](../../)
* 函式庫 [Aspose.Slides](../../../)