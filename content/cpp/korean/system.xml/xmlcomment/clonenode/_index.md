---
title: CloneNode()
second_title: C++용 Aspose.Slides API 참조
description: 이 노드의 복제본을 생성합니다.
type: docs
weight: 40
url: /ko/system.xml/xmlcomment/clonenode/
---
## XmlComment::CloneNode(bool) 메서드


이 노드의 복제본을 생성합니다.

```cpp
SharedPtr<XmlNode> System::Xml::XmlComment::CloneNode(bool deep) override
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| deep | **bool** | **true**를 지정하면 지정된 노드 아래의 하위 트리를 재귀적으로 복제하고; **false**를 지정하면 노드 자체만 복제합니다. 주석 노드에는 자식이 없으므로 복제된 노드는 매개변수 설정에 관계없이 항상 텍스트 내용을 포함합니다. |

### 반환값

복제된 노드.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlNode](../../xmlnode/)
* 클래스 [XmlComment](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)