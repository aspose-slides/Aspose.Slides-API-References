---
title: RemoveAttributeNode()
second_title: Aspose.Slides C++ API 參考
description: 移除指定的 XmlAttribute。
type: docs
weight: 274
url: /zh-hant/system.xml/xmlelement/removeattributenode/
---
## XmlElement::RemoveAttributeNode(SharedPtr\<XmlAttribute\>) method

移除指定的 [XmlAttribute](../../xmlattribute/)。

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(SharedPtr<XmlAttribute> oldAttr)
```

### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| oldAttr | [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\> | 要移除的 [XmlAttribute](../../xmlattribute/) 節點。如果已移除的屬性具有預設值，將立即被取代。 |

### Return Value

已移除的 [XmlAttribute](../../xmlattribute/)，如果 **oldAttr** 不是 [XmlElement](../) 的屬性節點，則返回 **nullptr**。

## XmlElement::RemoveAttributeNode(String, String) method

移除由本地名稱和命名空間 URI 指定的 [XmlAttribute](../../xmlattribute/)。（如果已移除的屬性具有預設值，將立即被取代）。

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(String localName, String namespaceURI)
```

### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 屬性的本地名稱。 |
| namespaceURI | [String](../../../system/string/) | 屬性的命名空間 URI。 |

### Return Value

已移除的 [XmlAttribute](../../xmlattribute/)，如果 [XmlElement](../) 沒有匹配的屬性節點，則返回 **nullptr**。

## See Also

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlAttribute](../../xmlattribute/)
* 類別 [XmlElement](../)
* 類別 [String](../../../system/string/)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)