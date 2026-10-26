---
title: CloneNode()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이 노드의 복제본을 생성합니다. 표기 노드는 복제할 수 없습니다. 이 메서드를 XmlNotation 객체에 호출하면 예외가 발생합니다.
type: docs
weight: 118
url: /ko/system.xml/xmlnotation/clonenode/
---
## XmlNotation::CloneNode(bool) 메서드

이 노드의 복제본을 생성합니다. 표기 노드는 복제할 수 없습니다. 이 메서드를 [XmlNotation](../) 객체에 호출하면 예외가 발생합니다.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNotation::CloneNode(bool deep) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| deep | **bool** | **true**는 지정된 노드 아래의 하위 트리를 재귀적으로 복제합니다; **false**는 노드 자체만 복제합니다. |

### 반환값

메서드가 호출된 노드의 [XmlNode](../../xmlnode/) 복사본을 반환합니다.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlNode](../../xmlnode/)
* 클래스 [XmlNotation](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)