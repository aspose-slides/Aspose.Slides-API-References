---
title: CloneNode()
second_title: Aspose.Slides for C++ API 참조
description: 이 노드의 복제본을 생성합니다. 엔터티 노드는 복제될 수 없습니다. XmlEntity 객체에서 이 메서드를 호출하면 예외가 발생합니다.
type: docs
weight: 170
url: /ko/system.xml/xmlentity/clonenode/
---
## XmlEntity::CloneNode(bool) 메서드

이 노드의 복제본을 생성합니다. 엔터티 노드는 복제될 수 없습니다. [XmlEntity](../) 객체에서 이 메서드를 호출하면 예외가 발생합니다.

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntity::CloneNode(bool deep) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| deep | **bool** | **true**를 지정하면 지정된 노드 아래의 하위 트리를 재귀적으로 복제하고; **false**를 지정하면 노드 자체만 복제합니다. |

### 반환값

메서드가 호출된 [XmlNode](../../xmlnode/)의 복사본입니다.

## 또 다른 보기

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlNode](../../xmlnode/)
* 클래스 [XmlEntity](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)