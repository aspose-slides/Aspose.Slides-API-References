---
title: ComputeSignature()
second_title: Aspose.Slides の C++ 用 API リファレンス
description: 署名を作成します。
type: docs
weight: 14
url: /ja/system.security.cryptography.pkcs/signedcms/computesignature/
---
## SignedCms::ComputeSignature(const SharedPtr\<CmsSigner\>\&, bool) メソッド

Creates a signature.

```cpp
void System::Security::Cryptography::Pkcs::SignedCms::ComputeSignature(const SharedPtr<CmsSigner> &signer, bool silent)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| signer | const [SharedPtr](../../../system/sharedptr/)\<[CmsSigner](../../cmssigner/)\>\& | 使用する署名者。 |
| silent | **bool** | 証明書が無効な場合、**signer** に関連付けられた有効な証明書をユーザーに尋ねることを抑制するかどうか。 |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [CmsSigner](../../cmssigner/)
* クラス [SignedCms](../)
* 名前空間 [System::Security::Cryptography::Pkcs](../../)
* ライブラリ [Aspose.Slides](../../../)