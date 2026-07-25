---
title: ReadElementContentAs()
second_title: Aspose.Slides for C++ API リファレンス
description: 要求された型として要素の内容を読み取ります。
type: docs
weight: 586
url: /ja/system.xml/xmlreader/readelementcontentas/
---
## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) メソッド

要求された型として要素の内容を読み取ります。

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | 返される値の型。 |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | 型変換に関連する名前空間プレフィックスを解決するために使用される [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) オブジェクト。 |

### 戻り値

要求された型のオブジェクトに変換された要素の内容。

## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>, String, String) メソッド

指定されたローカル名と名前空間 URI が現在の要素と一致するか確認し、次に要求された型として要素の内容を読み取ります。

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver, String localName, String namespaceURI)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | 返される値の型。 |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | 型変換に関連する名前空間プレフィックスを解決するために使用される [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) オブジェクト。 |
| localName | [String](../../../system/string/) | 要素のローカル名。 |
| namespaceURI | [String](../../../system/string/) | 要素の名前空間 URI。 |

### 戻り値

要求された型のオブジェクトに変換された要素の内容。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Object](../../../system/object/)
* クラス [TypeInfo](../../../system/typeinfo/)
* クラス [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* クラス [XmlReader](../)
* クラス [String](../../../system/string/)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)