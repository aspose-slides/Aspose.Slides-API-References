---
title: idx_get()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたインデックスの cookie コレクションから cookie を返します。
type: docs
weight: 40
url: /ja/system.net/cookiecollection/idx_get/
---
## CookieCollection::idx_get(int32_t) メソッド


指定したインデックスの CookieCollection から cookie を返します。

```cpp
System::SharedPtr<Cookie> System::Net::CookieCollection::idx_get(int32_t index)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | 返すべき cookie のインデックス。 |

### 戻り値

指定したインデックスの cookie。

## CookieCollection::idx_get(String) メソッド


指定された名前で CookieCollection から cookie を返します。

```cpp
System::SharedPtr<Cookie> System::Net::CookieCollection::idx_get(String name)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 返すべき cookie の名前。 |

### 戻り値

指定された名前で CookieCollection から見つかった場合は cookie を返し、見つからない場合は nullptr を返します。

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [Cookie](../../cookie/)
* クラス [CookieCollection](../)
* クラス [String](../../../system/string/)
* 名前空間 [System::Net](../../)
* ライブラリ [Aspose.Slides](../../../)