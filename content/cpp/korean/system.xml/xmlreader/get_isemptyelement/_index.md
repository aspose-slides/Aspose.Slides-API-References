---
title: get_IsEmptyElement()
second_title: Aspose.Slides for C++ API 참조
description: 파생 클래스에서 재정의될 경우, 현재 노드가 빈 요소인지 여부를 나타내는 값을 반환합니다(예: <MyElement/>).
type: docs
weight: 131
url: /ko/system.xml/xmlreader/get_isemptyelement/
---
## XmlReader::get_IsEmptyElement() 메서드

파생 클래스에서 재정의될 때, 현재 노드가 빈 요소인지 여부를 나타내는 값을 반환합니다 (예: **<MyElement/>**).

```cpp
virtual bool System::Xml::XmlReader::get_IsEmptyElement()=0
```

### 반환 값

현재 노드가 **/>** 로 끝나는 요소([XmlReader::get_NodeType](../get_nodetype/)가 [XmlNodeType::Element](../../xmlnodetype/)와 같은 경우)인 경우 **true**; 그렇지 않으면 **false**.

## 참고

* 클래스 [XmlReader](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)