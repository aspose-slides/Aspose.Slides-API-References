---
title: Add()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたネットワーク認証情報をキャッシュに追加します。
type: docs
weight: 40
url: /ja/system.net/credentialcache/add/
---
## CredentialCache::Add(System::SharedPtr\<Uri\>, String, System::SharedPtr\<NetworkCredential\>) メソッド

指定されたネットワーク認証情報をキャッシュに追加します。

```cpp
void System::Net::CredentialCache::Add(System::SharedPtr<Uri> uriPrefix, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 認証情報が関連付けられるリソースの URI プレフィックス。 |
| authenticationType | [String](../../../system/string/) | 認証スキーム。 |
| credential | [System::SharedPtr](../../../system/sharedptr/)\<[NetworkCredential](../../networkcredential/)\> | 追加する認証情報。 |

## CredentialCache::Add(String, int32_t, String, System::SharedPtr\<NetworkCredential\>) メソッド

指定されたネットワーク認証情報をキャッシュに追加します。

```cpp
void System::Net::CredentialCache::Add(String host, int32_t port, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| host | [String](../../../system/string/) | 認証情報が関連付けられるホスト名。 |
| port | **int32_t** | ポート番号。 |
| authenticationType | [String](../../../system/string/) | 認証スキーム。 |
| credential | [System::SharedPtr](../../../system/sharedptr/)\<[NetworkCredential](../../networkcredential/)\> | 追加する認証情報。 |

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Uri](../../../system/uri/)
* クラス [String](../../../system/string/)
* クラス [NetworkCredential](../../networkcredential/)
* クラス [CredentialCache](../)
* 名前空間 [System::Net](../../)
* ライブラリ [Aspose.Slides](../../../)