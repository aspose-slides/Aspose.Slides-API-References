---
title: get_OldParent()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "작업이 시작되기 전에 XmlNode::get_ParentNode의 값을 반환합니다."
type: docs
weight: 27
url: /ko/system.xml/xmlnodechangedeventargs/get_oldparent/
---
## XmlNodeChangedEventArgs::get_OldParent() 메서드


작업이 시작되기 전에 [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/)의 값을 반환합니다.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_OldParent()
```


### 반환 값

작업이 시작되기 전에 **ParentNode**의 값입니다. 노드에 부모가 없을 경우 이 메서드는 **nullptr**을 반환합니다. 속성 노드의 경우 이 메서드는 [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/) 값을 반환합니다.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlNode](../../xmlnode/)
* 클래스 [XmlNodeChangedEventArgs](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)