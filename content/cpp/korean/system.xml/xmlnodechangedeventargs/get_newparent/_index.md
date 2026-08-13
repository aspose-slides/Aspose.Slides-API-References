---
title: get_NewParent()
second_title: Aspose.Slides for C++ API 참조
description: "작업이 완료된 후 XmlNode::get_ParentNode의 값을 반환합니다."
type: docs
weight: 40
url: /ko/system.xml/xmlnodechangedeventargs/get_newparent/
---
## XmlNodeChangedEventArgs::get_NewParent() 메서드


작업이 완료된 후 [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/)의 값을 반환합니다.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_NewParent()
```


### 반환 값

작업이 완료된 후 **ParentNode**의 값입니다. 이 메서드는 노드가 제거되는 경우 **nullptr**를 반환합니다. 속성 노드의 경우 이 메서드는 [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/) 값을 반환합니다.

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlNode](../../xmlnode/)
* 클래스 [XmlNodeChangedEventArgs](../)
* 네임스페이스 [System::Xml](../../)
* Library [Aspose.Slides](../../../)