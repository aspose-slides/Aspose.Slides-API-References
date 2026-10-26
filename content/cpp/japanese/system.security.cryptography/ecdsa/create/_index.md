---
title: Create()
second_title: Aspose.Slides for C++ API リファレンス
description: デフォルトの ECDSA アルゴリズム実装を作成します。
type: docs
weight: 131
url: /ja/system.security.cryptography/ecdsa/create/
---
## ECDsa::Create() メソッド

デフォルトの ECDSA アルゴリズム実装を作成します。

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create()
```

### 戻り値

ECDSA アルゴリズム オブジェクト。

## ECDsa::Create(const ECCurve\&) メソッド

指定された曲線上に新しく作成されたキーを使用して、デフォルトの ECDSA アルゴリズム実装を作成します。

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const ECCurve &curve)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| curve | const [ECCurve](../../eccurve/)\& | キー作成に使用する曲線。 |

### 戻り値

ECDSA アルゴリズム オブジェクト。

## ECDsa::Create(const ECParameters\&) メソッド

指定されたパラメータを使用して、デフォルトの ECDSA アルゴリズム実装を作成します。

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const ECParameters &parameters)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| parameters | const [ECParameters](../../ecparameters/)\& | キーを表すパラメータ。 |

### 戻り値

ECDSA アルゴリズム オブジェクト。

## ECDsa::Create(const String\&) メソッド

指定された ECDSA アルゴリズム実装を作成します。

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const String &algorithm)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| algorithm | const [String](../../../system/string/)\& | アルゴリズム名。 |

### 戻り値

ECDSA アルゴリズム オブジェクト。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [ECDsa](../)
* クラス [String](../../../system/string/)
* 構造体 [ECCurve](../../eccurve/)
* 構造体 [ECParameters](../../ecparameters/)
* 名前空間 [System::Security::Cryptography](../../)
* ライブラリ [Aspose.Slides](../../../)