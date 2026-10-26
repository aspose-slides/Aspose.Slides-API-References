---
title: get_IsEmptyElement()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 노드가 빈 요소인지 여부를 나타내는 값을 반환합니다 (예: <MyElement/>).
type: docs
weight: 118
url: /ko/system.xml/xmlvalidatingreader/get_isemptyelement/
---
## XmlValidatingReader::get_IsEmptyElement() 메서드


현재 노드가 빈 요소인지 여부를 나타내는 값을 반환합니다 (예: **<MyElement/>**).

```cpp
bool System::Xml::XmlValidatingReader::get_IsEmptyElement() override
```


### 반환 값

현재 노드가 요소이며 ([XmlValidatingReader::get_NodeType](../get_nodetype/) 값이 [XmlNodeType::Element](../../xmlnodetype/)와 같고) **/>** 로 끝나는 경우 **true**를 반환하고, 그렇지 않으면 **false**를 반환합니다.

## 참고

* 클래스 [XmlValidatingReader](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)