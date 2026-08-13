---
title: CopyTo()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 컬렉션에 있는 모든 XmlSchemaObjects를 지정된 배열에 복사하며, 지정된 인덱스에서 시작합니다.
type: docs
weight: 118
url: /ko/system.xml.schema/xmlschemaobjectcollection/copyto/
---
## XmlSchemaObjectCollection::CopyTo(const ArrayPtr\<SharedPtr\<XmlSchemaObject\>\>\&, int32_t) method

컬렉션에 있는 모든 XmlSchemaObjects를 지정된 배열에 복사하며, 지정된 인덱스에서 시작합니다.

```cpp
void System::Xml::Schema::XmlSchemaObjectCollection::CopyTo(const ArrayPtr<SharedPtr<XmlSchemaObject>> &array, int32_t index)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<[SharedPtr](../../../system/sharedptr/)\<[XmlSchemaObject](../../xmlschemaobject/)\>\>\& | [XmlSchemaObjectCollection](../)에서 복사된 요소들의 대상이 되는 배열입니다. 배열은 0 기반 인덱싱이어야 합니다. |
| index | **int32_t** | 복사가 시작되는 배열 내의 0 기반 인덱스입니다. |

## 참조

* 타입 정의 [ArrayPtr](../../../system/arrayptr/)
* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlSchemaObject](../../xmlschemaobject/)
* 클래스 [XmlSchemaObjectCollection](../)
* 네임스페이스 [System::Xml::Schema](../../)
* 라이브러리 [Aspose.Slides](../../../)