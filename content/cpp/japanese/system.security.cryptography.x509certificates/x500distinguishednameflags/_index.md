---
title: X500DistinguishedNameFlags
second_title: Aspose.Slides for C++ API リファレンス
description: X509 証明書の識別名の書式設定規則です。
type: docs
weight: 209
url: /ja/system.security.cryptography.x509certificates/x500distinguishednameflags/
---
## X500DistinguishedNameFlags 列挙体

X509 証明書の識別名の書式設定規則です。

```cpp
enum class X500DistinguishedNameFlags
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| None | 0 | 特別な特性はありません。 |
| Reversed | 1 | 名前は予約されています。 |
| UseSemicolons | 16 | セミコロンを使用します。 |
| DoNotUsePlusSign | 32 | 名前はプラス記号を使用しません。 |
| DoNotUseQuotes | 64 | 名前で引用符を無効にします。 |
| UseCommas | 128 | コンマの使用を有効にします。 |
| UseNewLines | 256 | 改行の使用を有効にします。 |
| UseUTF8Encoding | 4096 | Unicode から UTF-8 エンコーディングへの切り替えを行います。 |
| UseT61Encoding | 8192 | T61 エンコーディングに切り替えます。 |
| ForceUTF8Encoding | 16384 | 特定の X500 キーをエンコードする際に UTF-8 の使用を強制します。 |

## 参照

* 名前空間 [System::Security::Cryptography::X509Certificates](../)
* ライブラリ [Aspose.Slides](../../)