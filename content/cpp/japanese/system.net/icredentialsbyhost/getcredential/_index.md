---
title: GetCredential()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたホストおよび認証タイプの資格情報を返します。
type: docs
weight: 1
url: /ja/system.net/icredentialsbyhost/getcredential/
---
## ICredentialsByHost::GetCredential(String, int32_t, String) method

指定されたホストおよび認証タイプの資格情報を返します。

```cpp
virtual System::SharedPtr<NetworkCredential> System::Net::ICredentialsByHost::GetCredential(String host, int32_t port, String authenticationType)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| host | [String](../../../system/string/) | クライアントを認証するホスト。 |
| port | **int32_t** | ホストのポート番号。 |
| authenticationType | [String](../../../system/string/) | 認証タイプ。 |

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [NetworkCredential](../../networkcredential/)
* クラス [String](../../../system/string/)
* クラス [ICredentialsByHost](../)
* 名前空間 [System::Net](../../)
* ライブラリ [Aspose.Slides](../../../)