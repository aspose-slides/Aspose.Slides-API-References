---
title: SetContext()
second_title: Aspose.Slides for C++ API リファレンス
description: 派生クラスでオーバーライドされた場合、名前空間の解決に使用する XmlNamespaceManager オブジェクトを指定します。
type: docs
weight: 53
url: /ja/system.xml.xpath/xpathexpression/setcontext/
---
## XPathExpression::SetContext(SharedPtr\<XmlNamespaceManager\>) メソッド

派生クラスでオーバーライドされたとき、名前空間の解決に使用する [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/) オブジェクトを指定します。

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<XmlNamespaceManager> nsManager)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| nsManager | [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)\> | [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/) オブジェクトを名前空間の解決に使用します。 |

## XPathExpression::SetContext(SharedPtr\<IXmlNamespaceResolver\>) メソッド

派生クラスでオーバーライドされたとき、名前空間の解決に使用する [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) オブジェクトを指定します。

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) インターフェイスを実装するオブジェクトを名前空間の解決に使用します。 |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)
* クラス [XPathExpression](../)
* クラス [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* 名前空間 [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)