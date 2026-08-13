---
title: SetNamedItem()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "XmlNode::get_Name 결과를 사용하여 XmlNode를 추가합니다."
type: docs
weight: 14
url: /ko/system.xml/xmlattributecollection/setnameditem/
---
## XmlAttributeCollection::SetNamedItem(SharedPtr\<XmlNode\>) method


[XmlNode](../../xmlnode/)를 [XmlNode::get_Name](../../xmlnode/get_name/) 결과를 사용하여 추가합니다.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttributeCollection::SetNamedItem(SharedPtr<XmlNode> node) override
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | 이 컬렉션에 저장할 특성 노드입니다. 이 노드는 이후 노드 이름을 통해 접근할 수 있습니다. 동일한 이름을 가진 노드가 컬렉션에 이미 존재하면 새 노드로 교체되고, 그렇지 않으면 컬렉션 끝에 추가됩니다. |

### 반환 값

**node**가 동일한 이름의 기존 노드를 교체하면 이전 노드가 반환되고, 그렇지 않으면 추가된 노드가 반환됩니다.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlNode](../../xmlnode/)
* 클래스 [XmlAttributeCollection](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)