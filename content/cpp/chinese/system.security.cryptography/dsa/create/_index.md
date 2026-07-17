---
title: Create()
second_title: Aspose.Slides for C++ API 参考
description: 创建默认 DSA 算法实现。
type: docs
weight: 105
url: /zh/system.security.cryptography/dsa/create/
---
## DSA::Create() 方法

创建默认[DSA](../)算法实现。

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create()
```

### 返回值

[DSA](../)算法对象。

## DSA::Create(const String\&) 方法

创建默认[DSA](../)算法实现。

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(const String &alg_name)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| alg_name | const [String](../../../system/string/)\& | 必须为 "System.Security.Cryptography.DSACryptoServiceProvider". |

### 返回值

[DSA](../)算法对象。

## DSA::Create(int32_t) 方法

创建默认[DSA](../)算法实现，并指定密钥大小。

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(int32_t key_size_in_bits)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| key_size_in_bits | **int32_t** | 密钥大小，单位为位。 |

## DSA::Create(const DSAParameters\&) 方法

创建默认[DSA](../)算法实现，并指定参数。

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(const DSAParameters &parameters)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| parameters | const [DSAParameters](../../dsaparameters/)\& | [DSA](../)算法的参数。 |

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [DSA](../)
* 类 [String](../../../system/string/)
* 结构体 [DSAParameters](../../dsaparameters/)
* 命名空间 [System::Security::Cryptography](../../)
* 库 [Aspose.Slides](../../../)