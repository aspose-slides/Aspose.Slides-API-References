---
title: Add()
second_title: Aspose.Slides for C++ API リファレンス
description: コレクションにクッキーを追加します。
type: docs
weight: 53
url: /ja/system.net/cookiecollection/add/
---
## CookieCollection::Add(const System::SharedPtr\<Cookie\>\&) method

コレクションにクッキーを追加します。

```cpp
void System::Net::CookieCollection::Add(const System::SharedPtr<Cookie> &cookie) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| cookie | const [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\>\& | 追加するクッキー。 |

## CookieCollection::Add(System::SharedPtr\<CookieCollection\>) method

指定されたコレクションから現在のコレクションにクッキーを追加します。

```cpp
void System::Net::CookieCollection::Add(System::SharedPtr<CookieCollection> cookies)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../)\> | 現在のコレクションにクッキーがコピーされる元のコレクション。 |

## 参照

* typedef [SharedPtr](../../../system/sharedptr/)
* クラス [Cookie](../../cookie/)
* クラス [CookieCollection](../)
* 名前空間 [System::Net](../../)
* ライブラリ [Aspose.Slides](../../../)