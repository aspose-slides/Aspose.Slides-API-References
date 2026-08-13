---
title: CloneNode()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이 노드의 복제본을 생성합니다.
type: docs
weight: 118
url: /ko/system.xml/xmldocumenttype/clonenode/
---
## XmlDocumentType::CloneNode(bool) 메서드

이 노드의 복제본을 생성합니다.

```cpp
SharedPtr<XmlNode> System::Xml::XmlDocumentType::CloneNode(bool deep) override
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| deep | **bool** | **true** : 지정된 노드 아래의 하위 트리를 재귀적으로 복제합니다; **false** : 노드 자체만 복제합니다. 문서 유형 노드의 경우, 매개변수 설정과 관계없이 복제된 노드에는 항상 하위 트리가 포함됩니다. |

### 반환값

복제된 노드.

## 참고

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlNode](../../xmlnode/)
* 클래스 [XmlDocumentType](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)