---
title: CloneNode()
second_title: Aspose.Slides용 C++ API 레퍼런스
description: 이 노드의 복제본을 생성합니다.
type: docs
weight: 196
url: /ko/system.xml/xmlattribute/clonenode/
---
## XmlAttribute::CloneNode(bool) 메서드

이 노드의 복제본을 생성합니다.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::CloneNode(bool deep) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| deep | **bool** | **true** 를 사용하면 지정된 노드 아래의 하위 트리를 재귀적으로 복제합니다; **false** 를 사용하면 노드 자체만 복제합니다. |

### 반환값

복제된 노드.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlNode](../../xmlnode/)
* 클래스 [XmlAttribute](../)
* 네임스페이스 [System::Xml](../../)
* Library [Aspose.Slides](../../../)