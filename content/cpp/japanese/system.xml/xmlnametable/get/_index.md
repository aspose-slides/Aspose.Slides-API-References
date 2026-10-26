---
title: Get()
second_title: Aspose.Slides for C++ API リファレンス
description: 派生クラスでオーバーライドされた場合、指定された配列内の文字範囲と同じ文字を含むアトム化された文字列を取得します。
type: docs
weight: 1
url: /ja/system.xml/xmlnametable/get/
---
## XmlNameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) メソッド


派生クラスでオーバーライドされた場合、指定された配列内の文字範囲と同じ文字を含むアトム化された文字列を取得します。

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | 検索対象の名前を含む文字配列です。 |
| offset | **int32_t** | 名前の最初の文字を示す、配列内のゼロベースインデックスです。 |
| length | **int32_t** | 名前の文字数です。 |

### 戻り値

アトム化された文字列、または文字列がまだアトム化されていない場合は **nullptr** を返します。**length** がゼロの場合、[String::Empty](../../../system/string/empty/) が返されます。

## XmlNameTable::Get(const String\&) メソッド


派生クラスでオーバーライドされた場合、指定された文字列と同じ値を持つアトム化された文字列を取得します。

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const String &array)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| array | const [String](../../../system/string/)\& | 検索対象の名前です。 |

### 戻り値

アトム化された文字列、または文字列がまだアトム化されていない場合は **nullptr** を返します。

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [XmlNameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)