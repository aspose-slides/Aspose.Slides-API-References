---
title: Create()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立預設的 ECDSA 演算法實作。
type: docs
weight: 131
url: /zh-hant/system.security.cryptography/ecdsa/create/
---
## ECDsa::Create() 方法


建立預設的 ECDSA 演算法實作。

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create()
```


### 回傳值

ECDSA 演算法物件。

## ECDsa::Create(const ECCurve\&) 方法


建立預設的 ECDSA 演算法實作，使用在指定曲線上新建立的金鑰。

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const ECCurve &curve)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| curve | const [ECCurve](../../eccurve/)\& | 用於金鑰建立的曲線。 |

### 回傳值

ECDSA 演算法物件。

## ECDsa::Create(const ECParameters\&) 方法


建立預設的 ECDSA 演算法實作，使用指定的參數。

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const ECParameters &parameters)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| parameters | const [ECParameters](../../ecparameters/)\& | 代表金鑰的參數。 |

### 回傳值

ECDSA 演算法物件。

## ECDsa::Create(const String\&) 方法


建立指定的 ECDSA 演算法實作。

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const String &algorithm)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| algorithm | const [String](../../../system/string/)\& | 演算法名稱。 |

### 回傳值

ECDSA 演算法物件。

## 參見

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [ECDsa](../)
* 類別 [String](../../../system/string/)
* 結構 [ECCurve](../../eccurve/)
* 結構 [ECParameters](../../ecparameters/)
* 命名空間 [System::Security::Cryptography](../../)
* 函式庫 [Aspose.Slides](../../../)