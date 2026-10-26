---
title: Find()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された名前でコレクション内の NameValueHeaderValue-class インスタンスを検索します。
type: docs
weight: 144
url: /ja/system.net.http.headers/namevalueheadervalue/find/
---
## NameValueHeaderValue::Find(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, String) method


指定された名前で、コレクション内の NameValueHeaderValue-class インスタンスを検索します。

```cpp
static System::SharedPtr<NameValueHeaderValue> System::Net::Http::Headers::NameValueHeaderValue::Find(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, String name)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | NameValueHeaderValue-class インスタンスのコレクション。 |
| name | [String](../../../system/string/) | 検索する名前。 |

### 戻り値

見つかった場合の NameValueHeaderValue-class インスタンス、見つからない場合は nullptr。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [NameValueHeaderValue](../)
* クラス [ObjectCollection](../../objectcollection/)
* クラス [String](../../../system/string/)
* 名前空間 [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)