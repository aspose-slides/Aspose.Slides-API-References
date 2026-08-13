---
title: CloneNode()
second_title: Aspose.Slides for C++ API 참조
description: 이 노드의 복제본을 생성합니다.
type: docs
weight: 157
url: /ko/system.xml/xmldeclaration/clonenode/
---
## XmlDeclaration::CloneNode(bool) 메서드

이 노드의 복제본을 생성합니다.

```cpp
SharedPtr<XmlNode> System::Xml::XmlDeclaration::CloneNode(bool deep) override
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| deep | **bool** | **true** : 지정된 노드 아래의 하위 트리를 재귀적으로 복제합니다; **false** : 노드 자체만 복제합니다. [XmlDeclaration](../) 노드는 자식이 없으므로, 복제된 노드는 매개변수 설정과 관계없이 항상 데이터 값을 포함합니다. |

### 반환값

복제된 노드.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlDeclaration](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)