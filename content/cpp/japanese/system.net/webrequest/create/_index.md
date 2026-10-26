---
title: Create()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された URI を使用して WebRequest クラスの新しいインスタンスを作成します。
type: docs
weight: 53
url: /ja/system.net/webrequest/create/
---
## WebRequest::Create(String) メソッド


指定された URI を使用して [WebRequest](../) クラスの新しいインスタンスを作成します。

```cpp
static System::SharedPtr<WebRequest> System::Net::WebRequest::Create(String requestUriString)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| requestUriString | [String](../../../system/string/) | 指定された URI を使用して [WebRequest](../) クラスの新しいインスタンスを作成するための URI です。 |

### 戻り値

新しく作成された WebRequest クラスのインスタンス。

## WebRequest::Create(System::SharedPtr\<Uri\>) メソッド


指定された URI を使用して [WebRequest](../) クラスの新しいインスタンスを作成します。

```cpp
static System::SharedPtr<WebRequest> System::Net::WebRequest::Create(System::SharedPtr<Uri> requestUri)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| requestUri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 指定された URI を使用して [WebRequest](../) クラスの新しいインスタンスを作成するための URI です。 |

### 戻り値

新しく作成された WebRequest クラスのインスタンス。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [WebRequest](../)
* クラス [String](../../../system/string/)
* クラス [Uri](../../../system/uri/)
* 名前空間 [System::Net](../../)
* ライブラリ [Aspose.Slides](../../../)