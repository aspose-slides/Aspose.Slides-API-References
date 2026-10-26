---
title: Add()
second_title: Aspose.Slides の C++ API リファレンス
description: 派生クラスでオーバーライドされた場合、指定された文字列を原子化し、XmlNameTable に追加します。
type: docs
weight: 14
url: /ja/system.xml/xmlnametable/add/
---
## XmlNameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) メソッド

派生クラスでオーバーライドされた場合、指定された文字列を原子化し、[XmlNameTable](../)に追加します。

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | 追加する名前を含む文字配列。 |
| offset | **int32_t** | 名前の最初の文字を示す配列内のゼロベースインデックス。 |
| length | **int32_t** | 名前の文字数。 |

### 戻り値

新しい原子化文字列、または既に存在する場合は既存の文字列を返します。length が zero の場合、[String::Empty](../../../system/string/empty/) が返されます。

## XmlNameTable::Add(const String\&) メソッド

派生クラスでオーバーライドされた場合、指定された文字列を原子化し、[XmlNameTable](../)に追加します。

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const String &array)=0
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| array | const [String](../../../system/string/)\& | 追加する名前。 |

### 戻り値

新しい原子化文字列、または既に存在する場合は既存の文字列を返します。

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [String](../../../system/string/)
* クラス [XmlNameTable](../)
* 名前空間 [System::Xml](../../)
* Library [Aspose.Slides](../../../)