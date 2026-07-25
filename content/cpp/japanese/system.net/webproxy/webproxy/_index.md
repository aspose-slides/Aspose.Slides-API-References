---
title: WebProxy()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しいインスタンスを作成します。
type: docs
weight: 131
url: /ja/system.net/webproxy/webproxy/
---
## WebProxy::WebProxy() コンストラクタ

新しいインスタンスを作成します。

```cpp
System::Net::WebProxy::WebProxy()
```

## WebProxy::WebProxy(System::SharedPtr\<Uri\>) コンストラクタ

新しいインスタンスを作成します。

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | プロキシサーバーのアドレス。 |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool) コンストラクタ

新しいインスタンスを作成します。

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | プロキシサーバーのアドレス。 |
| BypassOnLocal | **bool** | ローカルアドレスにプロキシサーバーを使用するかどうかを示す値。 |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>) コンストラクタ

新しいインスタンスを作成します。

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | プロキシサーバーのアドレス。 |
| BypassOnLocal | **bool** | ローカルアドレスにプロキシサーバーを使用するかどうかを示す値。 |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | プロキシサーバーを使用しないアドレスのリスト。 |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) コンストラクタ

新しいインスタンスを作成します。

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList, System::SharedPtr<ICredentials> Credentials)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | プロキシサーバーのアドレス。 |
| BypassOnLocal | **bool** | ローカルアドレスにプロキシサーバーを使用するかどうかを示す値。 |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | プロキシサーバーを使用しないアドレスのリスト。 |
| Credentials | [System::SharedPtr](../../../system/sharedptr/)\<[ICredentials](../../icredentials/)\> | 認証のためにプロキシサーバーへ送信される資格情報。 |

## WebProxy::WebProxy(String, int32_t) コンストラクタ

新しいインスタンスを作成します。

```cpp
System::Net::WebProxy::WebProxy(String Host, int32_t Port)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| Host | [String](../../../system/string/) | ホスト名。 |
| Port | **int32_t** | ポート番号。 |

## WebProxy::WebProxy(String) コンストラクタ

新しいインスタンスを作成します。

```cpp
System::Net::WebProxy::WebProxy(String Address)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| Address | [String](../../../system/string/) | プロキシサーバーのアドレス。 |

## WebProxy::WebProxy(String, bool) コンストラクタ

新しいインスタンスを作成します。

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| Address | [String](../../../system/string/) | プロキシサーバーのアドレス。 |
| BypassOnLocal | **bool** | ローカルアドレスにプロキシサーバーを使用するかどうかを示す値。 |

## WebProxy::WebProxy(String, bool, System::ArrayPtr\<String\>) コンストラクタ

新しいインスタンスを作成します。

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| Address | [String](../../../system/string/) | プロキシサーバーのアドレス。 |
| BypassOnLocal | **bool** | ローカルアドレスにプロキシサーバーを使用するかどうかを示す値。 |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | プロキシサーバーを使用しないアドレスのリスト。 |

## WebProxy::WebProxy(String, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) コンストラクタ

新しいインスタンスを作成します。

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList, System::SharedPtr<ICredentials> Credentials)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| Address | [String](../../../system/string/) | プロキシサーバーのアドレス。 |
| BypassOnLocal | **bool** | ローカルアドレスにプロキシサーバーを使用するかどうかを示す値。 |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | プロキシサーバーを使用しないアドレスのリスト。 |
| Credentials | [System::SharedPtr](../../../system/sharedptr/)\<[ICredentials](../../icredentials/)\> | 認証のためにプロキシサーバーへ送信される資格情報。 |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [WebProxy](../)
* クラス [Uri](../../../system/uri/)
* クラス [String](../../../system/string/)
* クラス [ICredentials](../../icredentials/)
* 名前空間 [System::Net](../../)
* Library [Aspose.Slides](../../../)