---
title: InternalAdd()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたクッキーをコレクションに追加します。
type: docs
weight: 118
url: /ja/system.net/cookiecollection/internaladd/
---
## CookieCollection::InternalAdd(System::SharedPtr\<Cookie\>, bool) メソッド

指定されたクッキーをコレクションに追加します。

```cpp
int32_t System::Net::CookieCollection::InternalAdd(System::SharedPtr<Cookie> cookie, bool isStrict)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | 追加するクッキー。 |
| isStrict | **bool** | 指定されたクッキーが古いものと置き換える必要がある場合は true、そうでない場合は false。 |

### 戻り値

指定されたクッキーが古いものと置き換えられた場合は 0、そうでない場合は 1。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Cookie](../../cookie/)
* クラス [CookieCollection](../)
* 名前空間 [System::Net](../../)
* ライブラリ [Aspose.Slides](../../../)