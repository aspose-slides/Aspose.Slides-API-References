---
title: X509KeyStorageFlags
second_title: Aspose.Slides for C++ API リファレンス
description: キーの保存方法を定義します。
type: docs
weight: 261
url: /ja/system.security.cryptography.x509certificates/x509keystorageflags/
---
## X509KeyStorageFlags 列挙型

キーの保存方法を定義します。

```cpp
enum class X509KeyStorageFlags : int32_t
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| DefaultKeySet | 0 | 既定のキーセットを使用します。 |
| UserKeySet | 1 | マシンローカルのストアの代わりにユーザー関連ストアを使用します。 |
| MachineKeySet | 2 | ユーザーのストアの代わりにローカルマシンストアを使用します。 |
| Exportable | 4 | インポートされたキーをエクスポート可能としてマークします。 |
| UserProtected | 8 | キーが使用されていることをユーザーに通知します。 |
| PersistKeySet | 16 | 証明書をインポートする際にキーが永続化されます。 |

## 参照

* 名前空間 [System::Security::Cryptography::X509Certificates](../)
* ライブラリ [Aspose.Slides](../../)