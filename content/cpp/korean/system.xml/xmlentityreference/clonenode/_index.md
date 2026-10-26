---
title: CloneNode()
second_title: Aspose.Slides for C++ API 참조
description: 이 노드의 복제본을 생성합니다.
type: docs
weight: 92
url: /ko/system.xml/xmlentityreference/clonenode/
---
## XmlEntityReference::CloneNode(bool) 메서드

이 노드의 복제본을 생성합니다.

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntityReference::CloneNode(bool deep) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| deep | **bool** | **true**를 지정하면 지정된 노드 아래의 하위 트리를 재귀적으로 복제합니다; **false**를 지정하면 노드 자체만 복제합니다. [XmlEntityReference](../) 노드의 경우, 이 메서드는 자식이 없는 엔터티 참조 노드를 항상 반환합니다. 교체 텍스트는 노드가 부모에 삽입될 때 설정됩니다. |

### 반환값

복제된 노드.

## 참고

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlNode](../../xmlnode/)
* 클래스 [XmlEntityReference](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)