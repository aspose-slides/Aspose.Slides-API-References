---
title: ChangeType()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 값을 변환합니다. 해당 값의 유형은 XmlSchemaDatatype가 나타내는 XML 스키마 유형의 유효한 표현 중 하나이며, 지정된 런타임 유형으로 변환됩니다.
type: docs
weight: 66
url: /ko/system.xml.schema/xmlschemadatatype/changetype/
---
## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&) 메서드

지정된 값을 변환합니다. 해당 값의 형식은 [XmlSchemaDatatype](../)가 나타내는 XML 스키마 유형의 유효한 표현 중 하나이며, 지정된 런타임 형식으로 변환됩니다.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 지정된 형식으로 변환할 입력 값입니다. |
| targetType | const [TypeInfo](../../../system/typeinfo/)\& | 입력 값을 변환할 대상 형식입니다. |

### 반환 값

변환된 입력 값.

## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) 메서드

[XmlSchemaDatatype](../)가 나타내는 XML 스키마 유형의 유효한 표현 중 하나인 지정된 값을, [XmlSchemaDatatype](../)가 **xs:QName** 유형 또는 그 파생 유형을 나타내는 경우 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)를 사용하여 지정된 런타임 유형으로 변환합니다.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 지정된 형식으로 변환할 입력 값입니다. |
| targetType | const [TypeInfo](../../../system/typeinfo/)\& | 입력 값을 변환할 대상 형식입니다. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)는 네임스페이스 접두사를 해결하는 데 사용됩니다. 이는 [XmlSchemaDatatype](../)가 **xs:QName** 유형 또는 그 파생 유형을 나타내는 경우에만 유용합니다. |

### 반환 값

변환된 입력 값.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Object](../../../system/object/)
* 클래스 [TypeInfo](../../../system/typeinfo/)
* 클래스 [XmlSchemaDatatype](../)
* 클래스 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* 네임스페이스 [System::Xml::Schema](../../)
* 라이브러리 [Aspose.Slides](../../../)