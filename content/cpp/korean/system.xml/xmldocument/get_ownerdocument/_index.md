---
title: get_OwnerDocument()
second_title: Aspose.Slides for C++ API 참조
description: 현재 노드가 속한 XmlDocument를 반환합니다.
type: docs
weight: 79
url: /ko/system.xml/xmldocument/get_ownerdocument/
---
## XmlDocument::get_OwnerDocument() 메서드


현재 노드가 속한 [XmlDocument](../)를 반환합니다.

```cpp
SharedPtr<XmlDocument> System::Xml::XmlDocument::get_OwnerDocument() override
```


### 반환값

[XmlDocument](../) 노드에 대해 ([XmlDocument::get_NodeType](../get_nodetype/)가 [XmlNodeType::Document](../../xmlnodetype/)와 같을 때), 이 메서드는 항상 **nullptr**를 반환합니다.

## 참고

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlDocument](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)