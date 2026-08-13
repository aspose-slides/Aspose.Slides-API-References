---
title: InsertAfter()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 속성을 지정된 기준 속성 바로 뒤에 삽입합니다.
type: docs
weight: 66
url: /ko/system.xml/xmlattributecollection/insertafter/
---
## XmlAttributeCollection::InsertAfter(const SharedPtr\<XmlAttribute\>\&, const SharedPtr\<XmlAttribute\>\&) 메서드

지정된 속성을 지정된 기준 속성 바로 뒤에 삽입합니다.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::InsertAfter(const SharedPtr<XmlAttribute> &newNode, const SharedPtr<XmlAttribute> &refNode)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>\& | 삽입할 속성. |
| refNode | const [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>\& | 기준 속성. **newNode**는 **refNode** 뒤에 배치됩니다. |

### 반환값

컬렉션에 삽입할 [XmlAttribute](../../xmlattribute/).

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlAttribute](../../xmlattribute/)
* 클래스 [XmlAttributeCollection](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)