---
title: GetCredential()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された URI と認証タイプの資格情報を返します。
type: docs
weight: 1
url: /ja/system.net/icredentials/getcredential/
---
## ICredentials::GetCredential(System::SharedPtr\<Uri\>, String) メソッド

指定された URI と認証タイプの資格情報を返します。

```cpp
virtual System::SharedPtr<NetworkCredential> System::Net::ICredentials::GetCredential(System::SharedPtr<Uri> uri, String authType)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | クライアントが認証タイプを提供する URI。 |
| authType | [String](../../../system/string/) | 認証タイプ。 |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [NetworkCredential](../../networkcredential/)
* クラス [Uri](../../../system/uri/)
* クラス [String](../../../system/string/)
* クラス [ICredentials](../)
* 名前空間 [System::Net](../../)
* Library [Aspose.Slides](../../../)