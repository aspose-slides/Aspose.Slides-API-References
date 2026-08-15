---
title: SetContext()
second_title: Aspose.Slides for C++ API 參考文件
description: 當在衍生類別中被覆寫時，指定用於命名空間解析的 XmlNamespaceManager 物件。
type: docs
weight: 53
url: /zh-hant/system.xml.xpath/xpathexpression/setcontext/
---
## XPathExpression::SetContext(SharedPtr\<XmlNamespaceManager\>) 方法

當在衍生類別中被覆寫時，指定要用於命名空間解析的 [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/) 物件。

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<XmlNamespaceManager> nsManager)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| nsManager | [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)\> | 用於命名空間解析的 [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/) 物件。 |

## XPathExpression::SetContext(SharedPtr\<IXmlNamespaceResolver\>) 方法

當在衍生類別中被覆寫時，指定要用於命名空間解析的 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) 物件。

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | 用於命名空間解析的、實作 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) 介面的物件。 |

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)
* 類別 [XPathExpression](../)
* 類別 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* 命名空間 [System::Xml::XPath](../../)
* 函式庫 [Aspose.Slides](../../../)