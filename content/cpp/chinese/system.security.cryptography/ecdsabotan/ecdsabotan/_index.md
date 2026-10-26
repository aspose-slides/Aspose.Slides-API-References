---
title: ECDsaBotan()
second_title: Aspose.Slides C++ API 参考
description: 构造函数。使用默认参数。
type: docs
weight: 1
url: /zh/system.security.cryptography/ecdsabotan/ecdsabotan/
---
## ECDsaBotan::ECDsaBotan() constructor

构造函数。使用默认参数。

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan()
```

## ECDsaBotan::ECDsaBotan(const ECParameters\&) constructor

构造函数。

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const ECParameters &parameters)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| parameters | const [ECParameters](../../ecparameters/)\& | 算法参数。 |

## ECDsaBotan::ECDsaBotan(const ECCurve\&) constructor

构造函数。

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const ECCurve &curve)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| curve | const [ECCurve](../../eccurve/)\& | 用于创建公/私钥对的曲线。 |

## ECDsaBotan::ECDsaBotan(int32_t) constructor

构造函数。

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(int32_t key_size)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| key_size | **int32_t** | 密钥大小（位）。 |

## ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PublicKey\&) constructor

构造函数。

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PublicKey &key)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| key | const Botan::ECDSA_PublicKey\& | Botan 公钥。 |

## ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PrivateKey\&) constructor

构造函数。

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PrivateKey &key)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| key | const Botan::ECDSA_PrivateKey\& | Botan 私钥。 |

## 另请参见

* 类 [ECDsaBotan](../)
* 结构体 [ECParameters](../../ecparameters/)
* 结构体 [ECCurve](../../eccurve/)
* 命名空间 [System::Security::Cryptography](../../)
* 库 [Aspose.Slides](../../../)