---
title: Add()
second_title: Aspose.Slides for C++ API リファレンス
description: コレクションにクッキーを追加します。
type: docs
weight: 105
url: /ja/system.net/cookiecontainer/add/
---
## CookieContainer::Add(System::SharedPtr\<Cookie\>) メソッド

コレクションにクッキーを追加します。

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Cookie> cookie)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | 追加するクッキー。 |

## CookieContainer::Add(System::SharedPtr\<Cookie\>, bool) メソッド

コレクションにクッキーを追加します。

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Cookie> cookie, bool throwOnError)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | 追加するクッキー。 |
| throwOnError | **bool** | エラーが発生した際に例外がスローされるかどうかを示す値。 |

## CookieContainer::Add(System::SharedPtr\<CookieCollection\>) メソッド

指定されたコレクションから現在のコレクションへクッキーをコピーします。

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<CookieCollection> cookies)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../../cookiecollection/)\> | クッキーがコピーされるコレクション。 |

## CookieContainer::Add(System::SharedPtr\<Uri\>, System::SharedPtr\<Cookie\>) メソッド

指定された URI に対してクッキーを追加します。

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Uri> uri, System::SharedPtr<Cookie> cookie)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | クッキーの URI。 |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | 追加するクッキー。 |

## CookieContainer::Add(System::SharedPtr\<Uri\>, System::SharedPtr\<CookieCollection\>) メソッド

指定された URI 用の、指定されたコレクションから現在のコレクションへクッキーをコピーします。

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Uri> uri, System::SharedPtr<CookieCollection> cookies)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | クッキーの URI。 |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../../cookiecollection/)\> | クッキーをコピーするコレクション。 |

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Cookie](../../cookie/)
* クラス [CookieContainer](../)
* クラス [CookieCollection](../../cookiecollection/)
* クラス [Uri](../../../system/uri/)
* 名前空間 [System::Net](../../)
* ライブラリ [Aspose.Slides](../../../)