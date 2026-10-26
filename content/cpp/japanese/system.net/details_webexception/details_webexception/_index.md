---
title: Details_WebException()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しいインスタンスを作成します。
type: docs
weight: 40
url: /ja/system.net/details_webexception/details_webexception/
---
## Details_WebException::Details_WebException() コンストラクタ

新しいインスタンスを作成します。

```cpp
System::Net::Details_WebException::Details_WebException()
```

## Details_WebException::Details_WebException(String) コンストラクタ

新しいインスタンスを作成します。

```cpp
System::Net::Details_WebException::Details_WebException(String message)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| message | [String](../../../system/string/) | エラーの説明。 |

## Details_WebException::Details_WebException(String, Exception) コンストラクタ

新しいインスタンスを作成します。

```cpp
System::Net::Details_WebException::Details_WebException(String message, Exception innerException)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| message | [String](../../../system/string/) | 例外メッセージ。 |
| innerException | [Exception](../../../system/exception/) | 内部例外。 |

## Details_WebException::Details_WebException(String, WebExceptionStatus) コンストラクタ

新しいインスタンスを作成します。

```cpp
System::Net::Details_WebException::Details_WebException(String message, WebExceptionStatus status)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| message | [String](../../../system/string/) | 例外メッセージ。 |
| status | [WebExceptionStatus](../../webexceptionstatus/) | ステータスコード。 |

## Details_WebException::Details_WebException(String, Exception, WebExceptionStatus, System::SharedPtr\<WebResponse\>) コンストラクタ

新しいインスタンスを作成します。

```cpp
System::Net::Details_WebException::Details_WebException(String message, Exception innerException, WebExceptionStatus status, System::SharedPtr<WebResponse> response)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| message | [String](../../../system/string/) | 例外メッセージ。 |
| innerException | [Exception](../../../system/exception/) | 内部例外。 |
| status | [WebExceptionStatus](../../webexceptionstatus/) | ステータスコード。 |
| response | [System::SharedPtr](../../../system/sharedptr/)\<[WebResponse](../../webresponse/)\> | 現在の例外に関連付けられている Web 応答。 |

## 参照

* Enum [WebExceptionStatus](../../webexceptionstatus/)
* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Details_WebException](../)
* Class [String](../../../system/string/)
* Class [WebResponse](../../webresponse/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)