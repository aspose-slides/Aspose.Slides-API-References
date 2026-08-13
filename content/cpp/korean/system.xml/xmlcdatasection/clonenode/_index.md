---
title: CloneNode()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이 노드의 복제본을 생성합니다.
type: docs
weight: 53
url: /ko/system.xml/xmlcdatasection/clonenode/
---
## XmlCDataSection::CloneNode(bool) method


이 노드의 복제본을 생성합니다.

```cpp
SharedPtr<XmlNode> System::Xml::XmlCDataSection::CloneNode(bool deep) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| deep | **bool** | **true** – 지정된 노드 아래의 하위 트리를 재귀적으로 복제합니다; **false** – 노드 자체만 복제합니다. CDATA 노드는 자식이 없으므로 매개변수 설정과 관계없이 복제된 노드에는 항상 데이터 내용이 포함됩니다. |

### Return Value

복제된 노드.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlCDataSection](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)