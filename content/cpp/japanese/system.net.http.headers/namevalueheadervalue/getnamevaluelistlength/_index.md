---
title: GetNameValueListLength()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたインデックスから渡された文字列を NameValueHeaderValue クラスのインスタンスのコレクションに変換し、解析された部分文字列の長さを返します。
type: docs
weight: 131
url: /ja/system.net.http.headers/namevalueheadervalue/getnamevaluelistlength/
---
## NameValueHeaderValue::GetNameValueListLength(String, int32_t, char16_t, System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>) メソッド


指定されたインデックスから渡された文字列を NameValueHeaderValue クラスのインスタンスのコレクションに変換し、解析された部分文字列の長さを返します。

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueListLength(String input, int32_t startIndex, char16_t delimiter, System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> nameValueCollection)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 解析対象の文字列。 |
| startIndex | **int32_t** | 解析の開始位置。 |
| delimiter | char16_t | 指定された文字列内の項目を区切るために使用される文字列。 |
| nameValueCollection | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | 解析されたコレクションが割り当てられる出力パラメータ。 |

### 戻り値

解析された部分文字列の長さ。

## 参照

* typedef [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [ObjectCollection](../../objectcollection/)
* クラス [NameValueHeaderValue](../)
* 名前空間 [System::Net::Http::Headers](../../)
* ライブラリ [Aspose.Slides](../../../)