---
title: get_Attributes()
second_title: C++용 Aspose.Slides API 참조
description: 이 노드의 속성을 포함하는 XmlAttributeCollection을 반환합니다.
type: docs
weight: 105
url: /ko/system.xml/xmlnode/get_attributes/
---
## XmlNode::get_Attributes() 메서드


이 노드의 속성을 포함하는 [XmlAttributeCollection](../../xmlattributecollection/)를 반환합니다.

```cpp
virtual SharedPtr<XmlAttributeCollection> System::Xml::XmlNode::get_Attributes() final
```


### 반환값

[XmlAttributeCollection](../../xmlattributecollection/)는 노드의 속성을 포함합니다. 노드가 [XmlNodeType::Element](../../xmlnodetype/) 유형인 경우 해당 노드의 속성이 반환됩니다. 그렇지 않으면 이 메서드는 **nullptr**를 반환합니다.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlAttributeCollection](../../xmlattributecollection/)
* 클래스 [XmlNode](../)
* 네임스페이스 [System::Xml](../../)
* Library [Aspose.Slides](../../../)