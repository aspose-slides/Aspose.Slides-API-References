---
title: SecurityPermissionFlag
second_title: Aspose.Slides for C++ API リファレンス
description: セキュリティ許可のフラグ。
type: docs
weight: 27
url: /ja/system.security.permissions/securitypermissionflag/
---
## SecurityPermissionFlag 列挙体

セキュリティ許可のフラグ。

```cpp
enum class SecurityPermissionFlag
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| NoFlags | 0 | アクセスなし。 |
| Assertion | 1 | 許可が付与されていることを主張します。 |
| UnmanagedCode | 2 | アンマネージドコードを呼び出します。 |
| SkipVerification | 4 | コード検証をスキップします。 |
| Execution | 8 | コードを実行します。 |
| ControlThread | 16 | スレッド上で操作を実行します。 |
| ControlEvidence | 32 | CLR エビデンスを制御または変更します。 |
| ControlPolicy | 64 | ポリシーを表示および変更します。 |
| SerializationFormatter | 128 | シリアライズします。 |
| ControlDomainPolicy | 256 | ドメインポリシーを設定します。 |
| ControlPrincipal | 512 | プリンシパルオブジェクトを制御します。 |
| ControlAppDomain | 1024 | アプリケーションドメインを制御します。 |
| RemotingConfiguration | 2048 | リモーティングを構成します。 |
| Infrastructure | 4096 | CLR インフラストラクチャに組み込みます。 |
| BindingRedirects | 8192 | 明示的なバインディングリダイレクトを実行します。 |
| AllFlags | 16383 | 無制限です。 |

## 関連項目

* 名前空間 [System::Security::Permissions](../)
* ライブラリ [Aspose.Slides](../../)