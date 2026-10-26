---
title: Create()
second_title: Aspose.Slides for C++ API 参考
description: 创建默认的 ECDSA 算法实现。
type: docs
weight: 131
url: /zh/system.security.cryptography/ecdsa/create/
---
## ECDsa::Create() 方法

创建默认的 ECDSA 算法实现。

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create()
```

### 返回值

ECDSA algorithm 对象。

## ECDsa::Create(const ECCurve\&) 方法

在指定曲线上使用新创建的密钥创建默认的 ECDSA 算法实现。

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const ECCurve &curve)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| curve | const [ECCurve](../../eccurve/)\& | 用于密钥创建的曲线。 |

### 返回值

ECDSA algorithm 对象。

## ECDsa::Create(const ECParameters\&) 方法

使用指定参数创建默认的 ECDSA 算法实现。

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const ECParameters &parameters)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| parameters | const [ECParameters](../../ecparameters/)\& | 表示密钥的参数。 |

### 返回值

ECDSA algorithm 对象。

## ECDsa::Create(const String\&) 方法

创建指定的 ECDSA 算法实现。

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const String &algorithm)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| algorithm | const [String](../../../system/string/)\& | 算法名称。 |

### 返回值

ECDSA algorithm 对象。

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [ECDsa](../)
* 类 [String](../../../system/string/)
* 结构体 [ECCurve](../../eccurve/)
* 结构体 [ECParameters](../../ecparameters/)
* 命名空间 [System::Security::Cryptography](../../)
* 库 [Aspose.Slides](../../../)