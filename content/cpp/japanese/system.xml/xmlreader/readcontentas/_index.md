---
title: ReadContentAs()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された型のオブジェクトとしてコンテンツを読み取ります。
type: docs
weight: 456
url: /ja/system.xml/xmlreader/readcontentas/
---
## XmlReader::ReadContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) メソッド

指定された型のオブジェクトとしてコンテンツを読み取ります。

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | 返される値の型です。 |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | 型変換に関連する名前空間プレフィックスを解決するために使用される [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) オブジェクトです。たとえば、[XmlQualifiedName](../../xmlqualifiedname/) オブジェクトを **xs:string** に変換する際に使用できます。この値は **nullptr** にすることができます。 |

### 戻り値

要求された型に変換された連結テキストコンテンツまたは属性値です。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Object](../../../system/object/)
* クラス [TypeInfo](../../../system/typeinfo/)
* クラス [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* クラス [XmlReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)