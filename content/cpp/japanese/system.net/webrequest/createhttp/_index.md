---
title: CreateHttp()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された URI を使用して WebRequest クラスの新しいインスタンスを作成します。
type: docs
weight: 79
url: /ja/system.net/webrequest/createhttp/
---
## WebRequest::CreateHttp(String) メソッド

[WebRequest](../) クラスの新しいインスタンスを、指定された URI を使用して作成します。

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(String requestUriString)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| requestUriString | [String](../../../system/string/) | 指定された URI を使用して [WebRequest](../) クラスの新しいインスタンスを作成するための URI です。 |

### 戻り値

新しく作成された WebRequest クラスのインスタンス。

## 備考

指定された URI が [http://](http://) または [https://](https://) 以外のスキームで始まる場合、NotSupportedException がスローされます。

## WebRequest::CreateHttp(System::SharedPtr\<Uri\>) メソッド

[WebRequest](../) クラスの新しいインスタンスを、指定された URI を使用して作成します。

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(System::SharedPtr<Uri> requestUri)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| requestUri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 指定された URI を使用して [WebRequest](../) クラスの新しいインスタンスを作成するための URI です。 |

### 戻り値

新しく作成された WebRequest クラスのインスタンス。

## 備考

指定された URI が [http://](http://) または [https://](https://) 以外のスキームで始まる場合、NotSupportedException がスローされます。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpWebRequest](../../httpwebrequest/)
* Class [String](../../../system/string/)
* Class [WebRequest](../)
* Class [Uri](../../../system/uri/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)