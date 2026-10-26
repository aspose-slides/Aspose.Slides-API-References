---
title: ECDsaBotan()
second_title: Aspose.Slides C++ API 參考
description: 建構函式。使用預設參數。
type: docs
weight: 1
url: /zh-hant/system.security.cryptography/ecdsabotan/ecdsabotan/
---
## ECDsaBotan::ECDsaBotan() 建構函式

建構函式。使用預設參數。

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan()
```

## ECDsaBotan::ECDsaBotan(const ECParameters\&) 建構函式

建構函式。

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const ECParameters &parameters)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| parameters | const [ECParameters](../../ecparameters/)\& | 演算法參數。 |

## ECDsaBotan::ECDsaBotan(const ECCurve\&) 建構函式

建構函式。

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const ECCurve &curve)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| curve | const [ECCurve](../../eccurve/)\& | 用於建立公/私鑰對的曲線。 |

## ECDsaBotan::ECDsaBotan(int32_t) 建構函式

建構函式。

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(int32_t key_size)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| key_size | **int32_t** | 金鑰大小（位元）。 |

## ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PublicKey\&) 建構函式

建構函式。

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PublicKey &key)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| key | const Botan::ECDSA_PublicKey\& | Botan 公鑰。 |

## ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PrivateKey\&) 建構函式

建構函式。

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PrivateKey &key)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| key | const Botan::ECDSA_PrivateKey\& | Botan 私鑰。 |

## 另請參閱

* 類別 [ECDsaBotan](../)
* 結構 [ECParameters](../../ecparameters/)
* 結構 [ECCurve](../../eccurve/)
* 命名空間 [System::Security::Cryptography](../../)
* 函式庫 [Aspose.Slides](../../../)