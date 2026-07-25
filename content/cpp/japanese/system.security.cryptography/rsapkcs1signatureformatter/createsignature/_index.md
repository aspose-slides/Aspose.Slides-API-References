---
title: CreateSignature()
second_title: Aspose.Slides for C++ API リファレンス
description: データに署名します。
type: docs
weight: 27
url: /ja/system.security.cryptography/rsapkcs1signatureformatter/createsignature/
---
## RSAPKCS1SignatureFormatter::CreateSignature(System::ArrayPtr\<uint8_t\>) method

データに署名します。

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::RSAPKCS1SignatureFormatter::CreateSignature(System::ArrayPtr<uint8_t> rgbHash) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 署名対象データのハッシュです。 |

### 戻り値

計算された署名。

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [RSAPKCS1SignatureFormatter](../)
* 名前空間 [System::Security::Cryptography](../../)
* ライブラリ [Aspose.Slides](../../../)