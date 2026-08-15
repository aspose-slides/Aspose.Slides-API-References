---
title: get_Attributes()
second_title: Aspose.Slides for C++ API 參考
description: 傳回包含此節點屬性的 XmlAttributeCollection。
type: docs
weight: 105
url: /zh-hant/system.xml/xmlnode/get_attributes/
---
## XmlNode::get_Attributes() method


傳回一個包含此節點屬性的 [XmlAttributeCollection](../../xmlattributecollection/)。

```cpp
virtual SharedPtr<XmlAttributeCollection> System::Xml::XmlNode::get_Attributes() final
```


### 返回值

一個包含該節點屬性的 [XmlAttributeCollection](../../xmlattributecollection/)。如果節點的類型為 [XmlNodeType::Element](../../xmlnodetype/)，則返回該節點的屬性。否則，此方法傳回 **nullptr**。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlAttributeCollection](../../xmlattributecollection/)
* 類別 [XmlNode](../)
* 命名空間 [System::Xml](../../)
* Library [Aspose.Slides](../../../)