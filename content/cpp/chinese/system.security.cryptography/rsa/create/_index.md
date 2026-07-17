---
title: Create()
second_title: Aspose.Slides for C++ API 参考
description: 创建默认 RSA 算法实现。
type: docs
weight: 183
url: /zh/system.security.cryptography/rsa/create/
---
## RSA::Create() 方法

创建默认的 [RSA](../) 算法实现。

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create()
```

## RSA::Create(const String\&) 方法

创建默认的 [RSA](../) 算法实现。

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(const String &alg_name)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| alg_name | const [String](../../../system/string/)\& | Must be "System.Security.Cryptography.RSACryptoServiceProvider". |

## RSA::Create(int32_t) 方法

创建默认的 [RSA](../) 算法实现，使用指定的密钥大小。

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(int32_t key_size_in_bits)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| key_size_in_bits | **int32_t** | 以位为单位的密钥大小。 |

## RSA::Create(const RSAParameters\&) 方法

创建默认的 [RSA](../) 算法实现，使用指定的参数。

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(const RSAParameters &parameters)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| parameters | const [RSAParameters](../../rsaparameters/)\& | 用于 [RSA](../) 算法的参数。 |

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [RSA](../)
* 类 [String](../../../system/string/)
* 结构体 [RSAParameters](../../rsaparameters/)
* 命名空间 [System::Security::Cryptography](../../)
* 库 [Aspose.Slides](../../../)