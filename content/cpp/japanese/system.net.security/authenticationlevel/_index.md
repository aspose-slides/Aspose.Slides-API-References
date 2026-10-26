---
title: AuthenticationLevel
second_title: Aspose.Slides の C++ API リファレンス
description: WebRequest 固有の認証フラグ。
type: docs
weight: 27
url: /ja/system.net.security/authenticationlevel/
---
## AuthenticationLevel 列挙型

WebRequest 固有の認証フラグ。

```cpp
enum class AuthenticationLevel
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| None | 0 | クライアントとサーバーの両方で認証は必要ありません。 |
| MutualAuthRequested | 1 | サーバーが認証されていなくてもリクエストは失敗しません。 |
| MutualAuthRequired | 2 | サーバーが認証されていない場合、現在のアプリケーションは 'IOException' を受け取ります。 |

## 参照

* 名前空間 [System::Net::Security](../)
* ライブラリ [Aspose.Slides](../../)