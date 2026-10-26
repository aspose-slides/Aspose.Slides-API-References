---
title: ValueAs()
second_title: Aspose.Slides for C++ API リファレンス
description: アイテムの値を指定された型として返します。
type: docs
weight: 131
url: /ja/system.xml.xpath/xpathitem/valueas/
---
## XPathItem::ValueAs(const TypeInfo\&) メソッド

指定された型としてアイテムの値を返します。

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | アイテムの値を返す型。 |

### 戻り値

要求された型としてアイテムの値を返します。

## XPathItem::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) メソッド

派生クラスでオーバーライドされた場合、名前空間プレフィックスを解決するために指定された [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) オブジェクトを使用して指定された型としてアイテムの値を返します。

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | アイテムの値を返す型。 |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | 名前空間プレフィックスを解決するために使用される [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) オブジェクト。 |

### 戻り値

要求された型としてアイテムの値を返します。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [Object](../../../system/object/)
* クラス [TypeInfo](../../../system/typeinfo/)
* クラス [XPathItem](../)
* クラス [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* 名前空間 [System::Xml::XPath](../../)
* ライブラリ [Aspose.Slides](../../../)