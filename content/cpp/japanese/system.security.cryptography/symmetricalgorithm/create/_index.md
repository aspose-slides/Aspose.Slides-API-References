---
title: Create()
second_title: Aspose.Slides for C++ API リファレンス
description: アルゴリズムのインスタンスを作成します。
type: docs
weight: 248
url: /ja/system.security.cryptography/symmetricalgorithm/create/
---
## SymmetricAlgorithm::Create(const String\&) メソッド

アルゴリズムのインスタンスを作成します。

```cpp
static SharedPtr<SymmetricAlgorithm> System::Security::Cryptography::SymmetricAlgorithm::Create(const String &algName)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| algName | const [String](../../../system/string/)\& | \"Rijndael\", \"TripleDES\"、または \"RC2\"である必要があります。 |

### 戻り値

新しく作成されたアルゴリズム。

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [SymmetricAlgorithm](../)
* クラス [String](../../../system/string/)
* 名前空間 [System::Security::Cryptography](../../)
* ライブラリ [Aspose.Slides](../../../)