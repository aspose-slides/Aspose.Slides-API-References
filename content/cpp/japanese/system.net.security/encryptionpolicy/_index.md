---
title: EncryptionPolicy
second_title: Aspose.Slides for C++ API リファレンス
description: 暗号化ポリシーを列挙します。
type: docs
weight: 53
url: /ja/system.net.security/encryptionpolicy/
---
## EncryptionPolicy 列挙型

暗号化ポリシーを列挙します。

```cpp
enum class EncryptionPolicy
```

### Values

| 名前 | 値 | 説明 |
| --- | --- | --- |
| RequireEncryption | 0 | 暗号化を必須とし、'Null' 暗号は許可しません。 |
| AllowNoEncryption | 1 | 完全な暗号化の使用を優先しますが、サーバーが同意すれば 'Null' 暗号を使用できます。 |
| NoEncryption | 2 | 暗号化なしを許可し、相手側が 'Null' 暗号を処理できる場合は 'Null' 暗号の使用を要求します。 |

## 参照

* 名前空間 [System::Net::Security](../)
* ライブラリ [Aspose.Slides](../../)