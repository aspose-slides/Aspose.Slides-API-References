---
title: CloneNode()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이 노드의 복제본을 생성합니다.
type: docs
weight: 196
url: /ko/system.xml/xmlelement/clonenode/
---
## XmlElement::CloneNode(bool) 메서드

이 노드의 복제본을 생성합니다.

```cpp
SharedPtr<XmlNode> System::Xml::XmlElement::CloneNode(bool deep) override
```

### 인수

| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| deep | **bool** | **true**는 지정된 노드 아래의 하위 트리를 재귀적으로 복제하고; **false**는 노드 자체만 복제합니다(노드가 [XmlElement](../)인 경우 해당 속성도 복제합니다). |

### 반환 값

복제된 노드입니다.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlNode](../../xmlnode/)
* 클래스 [XmlElement](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)