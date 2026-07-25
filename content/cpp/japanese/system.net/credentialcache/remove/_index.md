---
title: Remove()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された URI プレフィックスと認証タイプのネットワーク資格情報を削除します。
type: docs
weight: 53
url: /ja/system.net/credentialcache/remove/
---
## CredentialCache::Remove(System::SharedPtr\<Uri\>, String) メソッド

指定された URI プレフィックスと認証タイプのネットワーク資格情報を削除します。

```cpp
void System::Net::CredentialCache::Remove(System::SharedPtr<Uri> uriPrefix, String authenticationType)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI プレフィックス。 |
| authenticationType | [String](../../../system/string/) | 認証タイプ。 |

## CredentialCache::Remove(String, int32_t, String) メソッド

指定されたホスト名、ポート、および認証タイプのネットワーク資格情報を削除します。

```cpp
void System::Net::CredentialCache::Remove(String host, int32_t port, String authenticationType)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| host | [String](../../../system/string/) | 資格情報が関連付けられているホスト名。 |
| port | **int32_t** | ポート番号。 |
| authenticationType | [String](../../../system/string/) | 認証タイプ。 |

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Uri](../../../system/uri/)
* クラス [String](../../../system/string/)
* クラス [CredentialCache](../)
* 名前空間 [System::Net](../../)
* ライブラリ [Aspose.Slides](../../../)