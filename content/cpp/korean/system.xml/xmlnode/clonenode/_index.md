---
title: CloneNode()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 파생 클래스에서 재정의될 경우 노드의 복제본을 생성합니다.
type: docs
weight: 456
url: /ko/system.xml/xmlnode/clonenode/
---
## XmlNode::CloneNode(bool) method

파생 클래스에서 재정의될 경우 노드의 복제본을 생성합니다.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNode::CloneNode(bool deep)=0
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| deep | **bool** | **true** : 지정된 노드 아래의 하위 트리를 재귀적으로 복제합니다; **false** : 노드 자체만 복제합니다. |

### Return Value

복제된 노드.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlNode](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)