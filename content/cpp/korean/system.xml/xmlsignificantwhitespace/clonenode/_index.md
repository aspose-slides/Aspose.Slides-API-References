---
title: CloneNode()
second_title: Aspose.Slides for C++ API 참조
description: 이 노드의 복제본을 생성합니다.
type: docs
weight: 79
url: /ko/system.xml/xmlsignificantwhitespace/clonenode/
---
## XmlSignificantWhitespace::CloneNode(bool) 메서드

이 노드의 복제본을 생성합니다.

```cpp
SharedPtr<XmlNode> System::Xml::XmlSignificantWhitespace::CloneNode(bool deep) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| deep | **bool** | **true**는 지정된 노드 아래의 서브트리를 재귀적으로 복제합니다; **false**는 노드 자체만 복제합니다. 의미 있는 공백 노드의 경우, 복제된 노드는 매개변수 설정과 관계없이 항상 데이터 값을 포함합니다. |

### 반환값

복제된 노드입니다.

## 관련 항목

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlNode](../../xmlnode/)
* 클래스 [XmlSignificantWhitespace](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)