---
title: InsertBefore()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 속성을 지정된 참조 속성 바로 앞에 삽입합니다.
type: docs
weight: 53
url: /ko/system.xml/xmlattributecollection/insertbefore/
---
## XmlAttributeCollection::InsertBefore(const SharedPtr\<XmlAttribute\>\&, const SharedPtr\<XmlAttribute\>\&) method


지정된 속성을 지정된 참조 속성 바로 앞에 삽입합니다.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::InsertBefore(const SharedPtr<XmlAttribute> &newNode, const SharedPtr<XmlAttribute> &refNode)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>\& | 삽입할 속성. |
| refNode | const [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>\& | 참조 속성. **newNode**는 **refNode** 앞에 배치됩니다. |

### 반환 값

컬렉션에 삽입할 [XmlAttribute](../../xmlattribute/).

## 관련 항목

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlAttribute](../../xmlattribute/)
* 클래스 [XmlAttributeCollection](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)