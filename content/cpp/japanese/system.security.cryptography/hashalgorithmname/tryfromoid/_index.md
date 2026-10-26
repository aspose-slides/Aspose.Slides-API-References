---
title: TryFromOid()
second_title: Aspose.Slides for C++ API リファレンス
description: OID 値から HashAlgorithmName を作成しようとします。
type: docs
weight: 66
url: /ja/system.security.cryptography/hashalgorithmname/tryfromoid/
---
## HashAlgorithmName::TryFromOid(const String\&, HashAlgorithmName\&) メソッド

OID 値から [HashAlgorithmName](../) を作成しようとします。

```cpp
static bool System::Security::Cryptography::HashAlgorithmName::TryFromOid(const String &oid_value, HashAlgorithmName &value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| oid_value | const [String](../../../system/string/)\& | OID 値。 |
| value | [HashAlgorithmName](../)\& | 出力 [HashAlgorithmName](../)。 |

### 戻り値

指定された OID が有効なハッシュアルゴリズムである場合は true、そうでない場合は false。

## 参照

* クラス [String](../../../system/string/)
* 構造体 [HashAlgorithmName](../)
* 名前空間 [System::Security::Cryptography](../../)
* ライブラリ [Aspose.Slides](../../../)