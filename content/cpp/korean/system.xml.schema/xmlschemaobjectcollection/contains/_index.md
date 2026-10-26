---
title: Contains()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 XmlSchemaObject가 XmlSchemaObjectCollection에 포함되어 있는지 나타냅니다.
type: docs
weight: 92
url: /ko/system.xml.schema/xmlschemaobjectcollection/contains/
---
## XmlSchemaObjectCollection::Contains(const SharedPtr\<XmlSchemaObject\>\&) 메서드


지정된 [XmlSchemaObject](../../xmlschemaobject/)가 [XmlSchemaObjectCollection](../)에 포함되어 있는지 나타냅니다.

```cpp
bool System::Xml::Schema::XmlSchemaObjectCollection::Contains(const SharedPtr<XmlSchemaObject> &item)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaObject](../../xmlschemaobject/)\>\& | 해당 [XmlSchemaObject](../../xmlschemaobject/). |

### 반환 값

**true** 지정된 qualified name이 컬렉션에 있는 경우; 그렇지 않으면 **false**를 반환합니다. **nullptr**가 제공되면 null 이름을 가진 qualified name이 없으므로 **false**가 반환됩니다.

## 참조

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlSchemaObject](../../xmlschemaobject/)
* 클래스 [XmlSchemaObjectCollection](../)
* 네임스페이스 [System::Xml::Schema](../../)
* 라이브러리 [Aspose.Slides](../../../)