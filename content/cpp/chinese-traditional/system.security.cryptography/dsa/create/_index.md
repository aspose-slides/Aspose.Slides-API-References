---
title: Create()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立預設 DSA 演算法實作。
type: docs
weight: 105
url: /zh-hant/system.security.cryptography/dsa/create/
---
## DSA::Create() 方法

建立預設 [DSA](../) 演算法實作。

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create()
```

### 返回值

[DSA](../) 演算法物件。

## DSA::Create(const String\&) 方法

建立預設 [DSA](../) 演算法實作。

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(const String &alg_name)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| alg_name | const [String](../../../system/string/)\& | 必須為 "System.Security.Cryptography.DSACryptoServiceProvider". |

### 返回值

[DSA](../) 演算法物件。

## DSA::Create(int32_t) 方法

建立預設 [DSA](../) 演算法實作，使用指定的金鑰大小。

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(int32_t key_size_in_bits)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| key_size_in_bits | **int32_t** | 金鑰大小（位元）。 |

## DSA::Create(const DSAParameters\&) 方法

建立預設 [DSA](../) 演算法實作，使用指定的參數。

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(const DSAParameters &parameters)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| parameters | const [DSAParameters](../../dsaparameters/)\& | [DSA](../) 演算法的參數。 |

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [DSA](../)
* 類別 [String](../../../system/string/)
* Struct [DSAParameters](../../dsaparameters/)
* 命名空間 [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)