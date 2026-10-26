---
title: InsertBefore()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 노드를 지정된 기준 노드 바로 앞에 삽입합니다.
type: docs
weight: 378
url: /ko/system.xml/xmlnode/insertbefore/
---
## XmlNode::InsertBefore(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) 메서드


지정된 노드를 지정된 기준 노드 바로 앞에 삽입합니다.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNode::InsertBefore(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../)\> | 삽입할 노드입니다. |
| refChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../)\> | 기준 노드입니다. **newChild**는 이 노드 앞에 배치됩니다. |

### 반환 값

삽입되는 노드입니다.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlNode](../)
* 네임스페이스 [System::Xml](../../)
* Library [Aspose.Slides](../../../)