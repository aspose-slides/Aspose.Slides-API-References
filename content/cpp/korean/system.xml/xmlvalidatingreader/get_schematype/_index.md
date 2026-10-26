---
title: get_SchemaType()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 스키마 유형 객체를 반환합니다.
type: docs
weight: 287
url: /ko/system.xml/xmlvalidatingreader/get_schematype/
---
## XmlValidatingReader::get_SchemaType() 메서드


스키마 유형 객체를 반환합니다.

```cpp
SharedPtr<Object> System::Xml::XmlValidatingReader::get_SchemaType()
```


### 반환 값

XmlSchemaDatatype, XmlSchemaSimpleType 또는 XmlSchemaComplexType은 노드 값이 내장 XML [Schema](../../../system.xml.schema/) 정의 언어(XSD) 유형이거나 사용자 정의 simpleType 또는 complexType인지에 따라 결정됩니다; 현재 노드에 스키마 유형이 없으면 **nullptr**.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Object](../../../system/object/)
* 클래스 [XmlValidatingReader](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)