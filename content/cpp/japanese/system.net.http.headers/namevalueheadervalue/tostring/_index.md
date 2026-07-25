---
title: ToString()
second_title: Aspose.Slides for C++ API リファレンス
description: C# Object.ToString() メソッドの類似です。カスタムオブジェクトを文字列に変換できます。
type: docs
weight: 79
url: /ja/system.net.http.headers/namevalueheadervalue/tostring/
---
## NameValueHeaderValue::ToString() const メソッド


Analog of C# [Object.ToString()](../../../system/object/tostring/) method. Enables converting custom objects to string.

```cpp
String System::Net::Http::Headers::NameValueHeaderValue::ToString() const override
```


### 戻り値

[String](../../../system/string/) representation as provided by final class.

## NameValueHeaderValue::ToString(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool, System::SharedPtr\<Text::StringBuilder\>) メソッド


Returns a string representation of the collection of the NameValueHeaderValue-class instances.

```cpp
static void System::Net::Http::Headers::NameValueHeaderValue::ToString(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, char16_t separator, bool leadingSeparator, System::SharedPtr<Text::StringBuilder> destination)
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | NameValueHeaderValueクラスのインスタンスのコレクション。 |
| separator | char16_t | 文字列の区切り文字。 |
| leadingSeparator | **bool** | 文字列区切り文字を最初のコレクション項目の前に追加するかどうかを示す値。 |
| destination | [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\> | 文字列表現が割り当てられるインスタンス。 |

## NameValueHeaderValue::ToString(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool) メソッド


Returns a string representation of the collection of the NameValueHeaderValue-class instances.

```cpp
static String System::Net::Http::Headers::NameValueHeaderValue::ToString(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, char16_t separator, bool leadingSeparator)
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | NameValueHeaderValueクラスのインスタンスのコレクション。 |
| separator | char16_t | 文字列の区切り文字。 |
| leadingSeparator | **bool** | 文字列区切り文字を最初のコレクション項目の前に追加するかどうかを示す値。 |

### 戻り値

NameValueHeaderValueクラスのインスタンスのコレクションの文字列表現。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [NameValueHeaderValue](../)
* Class [ObjectCollection](../../objectcollection/)
* Class [StringBuilder](../../../system.text/stringbuilder/)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)