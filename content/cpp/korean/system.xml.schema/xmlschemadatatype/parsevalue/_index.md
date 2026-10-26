---
title: ParseValue()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 파생 클래스에서 재정의될 경우, 지정된 문자열을 내장 또는 사용자 정의 단순 형식에 대해 검증합니다.
type: docs
weight: 53
url: /ko/system.xml.schema/xmlschemadatatype/parsevalue/
---
## XmlSchemaDatatype::ParseValue(String, SharedPtr\<XmlNameTable\>, SharedPtr\<IXmlNamespaceResolver\>) 메서드

파생 클래스에서 재정의될 경우, 지정된 **string**을 내장 또는 사용자 정의 단순 형식에 대해 검증합니다.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ParseValue(String s, SharedPtr<XmlNameTable> nameTable, SharedPtr<IXmlNamespaceResolver> nsmgr)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| s | [String](../../../system/string/) | 단순 형식에 대해 검증할 **string**. |
| nameTable | [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../../system.xml/xmlnametable/)\> | [XmlNameTable](../../../system.xml/xmlnametable/)는 **string**을 구문 분석하는 동안 원자화에 사용되는 것으로, 이 [XmlSchemaDatatype](../) 객체가 **xs:NCName** 유형을 나타내는 경우에 사용됩니다. |
| nsmgr | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) 객체는 **string**을 구문 분석하는 동안 사용되며, 이 [XmlSchemaDatatype](../) 객체가 **xs:QName** 유형을 나타내는 경우에 해당합니다. |

### 반환값

[Object](../../../system/object/)는 [XmlSchemaDatatype::get_ValueType](../get_valuetype/) 호출에 의해 반환된 형식으로 안전하게 캐스팅할 수 있는 객체입니다.

## 관련 보기

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [XmlNameTable](../../../system.xml/xmlnametable/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XmlSchemaDatatype](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)