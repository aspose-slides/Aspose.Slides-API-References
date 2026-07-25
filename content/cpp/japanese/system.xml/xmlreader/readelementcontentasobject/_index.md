---
title: ReadElementContentAsObject()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在の要素を読み取り、内容を Object として返します。
type: docs
weight: 469
url: /ja/system.xml/xmlreader/readelementcontentasobject/
---
## XmlReader::ReadElementContentAsObject() メソッド


現在の要素を読み取り、内容を [Object](../../../system/object/) として返します。

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject()
```


### 戻り値

最も適切な型のボックス化されたオブジェクト。[XmlReader::get_ValueType](../get_valuetype/) の値が適切な型を決定します。コンテンツがリスト型として型付けされている場合、このメソッドは適切な型のボックス化されたオブジェクトの配列を返します。

## XmlReader::ReadElementContentAsObject(String, String) メソッド


指定されたローカル名と名前空間 URI が現在の要素と一致することを確認し、現在の要素を読み取り、内容を [Object](../../../system/object/) として返します。

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject(String localName, String namespaceURI)
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 要素のローカル名。 |
| namespaceURI | [String](../../../system/string/) | 要素の名前空間 URI。 |

### 戻り値

最も適切な型のボックス化されたオブジェクト。[XmlReader::get_ValueType](../get_valuetype/) の値が適切な型を決定します。コンテンツがリスト型として型付けされている場合、このメソッドは適切な型のボックス化されたオブジェクトの配列を返します。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [XmlReader](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)