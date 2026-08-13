---
title: get_SchemaInfo()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 스키마 검증 결과 현재 노드에 할당된 스키마 정보를 반환합니다.
type: docs
weight: 196
url: /ko/system.xml/xmlreader/get_schemainfo/
---
## XmlReader::get_SchemaInfo() 메서드

스키마 유효성 검사의 결과로 현재 노드에 할당된 스키마 정보를 반환합니다.

```cpp
virtual SharedPtr<Schema::IXmlSchemaInfo> System::Xml::XmlReader::get_SchemaInfo()
```

### 반환 값

현재 노드에 대한 스키마 정보를 포함하는 IXmlSchemaInfo 객체입니다. [Schema](../../../system.xml.schema/) 정보는 요소, 속성 또는 null이 아닌 [XmlReader::get_ValueType](../get_valuetype/) 값을 가진 텍스트 노드에 설정할 수 있습니다. 현재 노드가 위의 노드 유형 중 하나가 아니거나 [XmlReader](../) 인스턴스가 스키마 정보를 보고하지 않으면 이 메서드는 **nullptr**을 반환합니다. 이 메서드가 [XmlTextReader](../../xmltextreader/) 또는 [XmlValidatingReader](../../xmlvalidatingreader/) 객체에서 호출되면 이 메서드는 항상 **nullptr**을 반환합니다. 이러한 [XmlReader](../) 구현은 get_SchemaInfo 메서드를 통해 스키마 정보를 노출하지 않습니다.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IXmlSchemaInfo](../../../system.xml.schema/ixmlschemainfo/)
* 클래스 [XmlReader](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)