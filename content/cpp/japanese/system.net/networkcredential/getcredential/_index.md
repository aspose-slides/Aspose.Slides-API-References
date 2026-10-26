---
title: GetCredential()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された URI と認証タイプの資格情報を返します。
type: docs
weight: 92
url: /ja/system.net/networkcredential/getcredential/
---
## NetworkCredential::GetCredential(System::SharedPtr\<Uri\>, String) メソッド

指定された URI と認証タイプの資格情報を返します。

```cpp
System::SharedPtr<NetworkCredential> System::Net::NetworkCredential::GetCredential(System::SharedPtr<Uri> uri, String authenticationType) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI です。 |
| authenticationType | [String](../../../system/string/) | 認証タイプです。 |

## NetworkCredential::GetCredential(String, int32_t, String) メソッド

指定されたホスト名、ポート、および認証タイプの資格情報を返します。

```cpp
System::SharedPtr<NetworkCredential> System::Net::NetworkCredential::GetCredential(String host, int32_t port, String authenticationType) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| host | [String](../../../system/string/) | ホスト名です。 |
| port | **int32_t** | ポート番号です。 |
| authenticationType | [String](../../../system/string/) | 認証タイプです。 |

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [NetworkCredential](../)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)