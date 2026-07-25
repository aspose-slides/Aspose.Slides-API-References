---
title: ParseValue()
second_title: Aspose.Slides の C++ 用 API リファレンス
description: 派生クラスでオーバーライドされた場合、指定された文字列を組み込みまたはユーザー定義の単純型に対して検証します。
type: docs
weight: 53
url: /ja/system.xml.schema/xmlschemadatatype/parsevalue/
---
## XmlSchemaDatatype::ParseValue(String, SharedPtr\<XmlNameTable\>, SharedPtr\<IXmlNamespaceResolver\>) メソッド

派生クラスでオーバーライドされた場合、指定された **string** が組み込みまたはユーザー定義のシンプル型に対して検証されます。

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ParseValue(String s, SharedPtr<XmlNameTable> nameTable, SharedPtr<IXmlNamespaceResolver> nsmgr)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| s | [String](../../../system/string/) | シンプル型に対して検証する **string**。 |
| nameTable | [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../../system.xml/xmlnametable/)\> | [XmlNameTable](../../../system.xml/xmlnametable/) は、**string** を解析中に原子化に使用するもので、この [XmlSchemaDatatype](../) オブジェクトが **xs:NCName** 型を表す場合に使用します。 |
| nsmgr | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) オブジェクトは、**string** を解析中に使用し、この [XmlSchemaDatatype](../) オブジェクトが **xs:QName** 型を表す場合に使用します。 |

### 戻り値

[Object](../../../system/object/) は、[XmlSchemaDatatype::get_ValueType](../get_valuetype/) 呼び出しが返す型に安全にキャストできるオブジェクトです。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Object](../../../system/object/)
* クラス [String](../../../system/string/)
* クラス [XmlNameTable](../../../system.xml/xmlnametable/)
* クラス [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* クラス [XmlSchemaDatatype](../)
* 名前空間 [System::Xml::Schema](../../)
* ライブラリ [Aspose.Slides](../../../)