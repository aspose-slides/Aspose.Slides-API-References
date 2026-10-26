---
title: GetCredential()
second_title: Aspose.Slides for C++ APIリファレンス
description: 指定された URI プレフィックスおよび認証タイプの資格情報を返します。
type: docs
weight: 66
url: /ja/system.net/credentialcache/getcredential/
---
## CredentialCache::GetCredential(System::SharedPtr\<Uri\>, String) メソッド

指定された URI プレフィックスおよび認証タイプの資格情報を返します。

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(System::SharedPtr<Uri> uriPrefix, String authenticationType) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI プレフィックス。 |
| authenticationType | [String](../../../system/string/) | 認証タイプ。 |

## CredentialCache::GetCredential(String, int32_t, String) メソッド

指定されたホスト名、ポート、および認証タイプの資格情報を返します。

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(String host, int32_t port, String authenticationType) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| host | [String](../../../system/string/) | 資格情報が関連付けられるホスト名。 |
| port | **int32_t** | ポート番号。 |
| authenticationType | [String](../../../system/string/) | 認証タイプ。 |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [NetworkCredential](../../networkcredential/)
* クラス [Uri](../../../system/uri/)
* クラス [String](../../../system/string/)
* クラス [CredentialCache](../)
* 名前空間 [System::Net](../../)
* Library [Aspose.Slides](../../../)