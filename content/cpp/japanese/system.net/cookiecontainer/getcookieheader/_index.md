---
title: GetCookieHeader()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたURIに関連付けられたクッキーを含むHTTPヘッダーを返します。
type: docs
weight: 170
url: /ja/system.net/cookiecontainer/getcookieheader/
---
## CookieContainer::GetCookieHeader(System::SharedPtr\<Uri\>) メソッド

指定されたURIに関連付けられたクッキーを含むHTTPヘッダーを返します。

```cpp
String System::Net::CookieContainer::GetCookieHeader(System::SharedPtr<Uri> uri)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | ヘッダー名が作成されるURI。 |

### 戻り値

指定されたURIに関連付けられたクッキーを含むHTTPヘッダー。

## CookieContainer::GetCookieHeader(System::SharedPtr\<Uri\>, String\&) メソッド

指定されたURIに関連付けられたクッキーを含むHTTPヘッダーを返します。

```cpp
String System::Net::CookieContainer::GetCookieHeader(System::SharedPtr<Uri> uri, String &optCookie2)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | ヘッダー名が作成されるURI。 |
| optCookie2 | [String](../../../system/string/)\& | 最大サポートバージョンのクッキーが割り当てられる出力パラメーター。 |

### 戻り値

指定されたURIに関連付けられたクッキーを含むHTTPヘッダー。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [Uri](../../../system/uri/)
* クラス [CookieContainer](../)
* 名前空間 [System::Net](../../)
* Library [Aspose.Slides](../../../)