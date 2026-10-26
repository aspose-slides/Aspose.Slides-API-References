---
title: Create()
second_title: Aspose.Slides for C++ API リファレンス
description: 名前に基づいてハッシュアルゴリズムを作成します。
type: docs
weight: 118
url: /ja/system.security.cryptography/hashalgorithm/create/
---
## HashAlgorithm::Create(const String\&) メソッド

名前に基づいてハッシュアルゴリズムを作成します。

```cpp
static SharedPtr<HashAlgorithm> System::Security::Cryptography::HashAlgorithm::Create(const String &hashName)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| hashName | const [String](../../../system/string/)\& | 次のいずれかの値: "MD5", "SHA1", "SHA256", "SHA384", "SHA512", "RIPEMD160"、またはそれらに "System.Security.Cryptography." プレフィックスが付いたもの。 |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [HashAlgorithm](../)
* クラス [String](../../../system/string/)
* 名前空間 [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)