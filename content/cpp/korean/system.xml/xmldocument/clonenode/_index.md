---
title: CloneNode()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이 노드의 복제본을 생성합니다.
type: docs
weight: 261
url: /ko/system.xml/xmldocument/clonenode/
---
## XmlDocument::CloneNode(bool) 메서드

이 노드의 복제본을 생성합니다.

```cpp
SharedPtr<XmlNode> System::Xml::XmlDocument::CloneNode(bool deep) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| deep | **bool** | **true**를 사용하면 지정된 노드 아래의 서브트리를 재귀적으로 복제합니다; **false**를 사용하면 노드 자체만 복제합니다. |

### 반환값

복제된 [XmlDocument](../) 노드.

## 관련 항목

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlNode](../../xmlnode/)
* 클래스 [XmlDocument](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)