---
title: RemoveAttributeAt()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 인덱스를 가진 속성 노드를 요소에서 제거합니다. (제거된 속성에 기본값이 있는 경우 즉시 대체됩니다.)
type: docs
weight: 339
url: /ko/system.xml/xmlelement/removeattributeat/
---
## XmlElement::RemoveAttributeAt(int32_t) 메서드


지정된 인덱스를 가진 속성 노드를 요소에서 제거합니다. (제거된 속성에 기본값이 있는 경우 즉시 대체됩니다).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlElement::RemoveAttributeAt(int32_t i)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| i | **int32_t** | 제거할 노드의 인덱스입니다. 첫 번째 노드의 인덱스는 0입니다. |

### 반환 값

제거된 속성 노드이며, 주어진 인덱스에 노드가 없으면 **nullptr**를 반환합니다.

## 또 보기

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlNode](../../xmlnode/)
* 클래스 [XmlElement](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)