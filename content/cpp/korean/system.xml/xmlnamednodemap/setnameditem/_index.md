---
title: SetNamedItem()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "XmlNode::get_Name 값을 사용하여 XmlNode를 추가합니다."
type: docs
weight: 27
url: /ko/system.xml/xmlnamednodemap/setnameditem/
---
## XmlNamedNodeMap::SetNamedItem(SharedPtr\<XmlNode\>) 메서드

Adds an [XmlNode](../../xmlnode/) using its [XmlNode::get_Name](../../xmlnode/get_name/) value.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::SetNamedItem(SharedPtr<XmlNode> node)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | [XmlNode](../../xmlnode/)를 [XmlNamedNodeMap](../)에 저장합니다. 동일한 이름의 노드가 이미 맵에 존재하면 새 노드로 교체됩니다. |

### 반환값

**node**가 동일한 이름의 기존 노드를 교체하면 이전 노드가 반환됩니다; 그렇지 않으면 **nullptr**가 반환됩니다.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlNode](../../xmlnode/)
* 클래스 [XmlNamedNodeMap](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)