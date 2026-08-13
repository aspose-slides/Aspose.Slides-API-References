---
title: XmlSchemaValidator()
second_title: Aspose.Slides for C++ API 참조
description: XmlSchemaValidator 클래스의 새 인스턴스를 초기화합니다.
type: docs
weight: 92
url: /ko/system.xml.schema/xmlschemavalidator/xmlschemavalidator/
---
## XmlSchemaValidator::XmlSchemaValidator(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlSchemaSet\>\&, const SharedPtr\<IXmlNamespaceResolver\>\&, XmlSchemaValidationFlags) 생성자

[XmlSchemaValidator](../) 클래스의 새 인스턴스를 초기화합니다.

```cpp
System::Xml::Schema::XmlSchemaValidator::XmlSchemaValidator(const SharedPtr<XmlNameTable> &nameTable, const SharedPtr<XmlSchemaSet> &schemas, const SharedPtr<IXmlNamespaceResolver> &namespaceResolver, XmlSchemaValidationFlags validationFlags)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| nameTable | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../../system.xml/xmlnametable/)\>\& | 요소와 속성 이름을 원자화된 문자열로 포함하는 [XmlNameTable](../../../system.xml/xmlnametable/) 객체. |
| schemas | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../../xmlschemaset/)\>\& | 검증에 사용되는 XML [Schema](../../) 정의 언어 (XSD) 스키마를 포함하는 [XmlSchemaSet](../../xmlschemaset/) 객체. |
| namespaceResolver | const [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\>\& | 검증 중에 발견되는 네임스페이스를 해결하는 데 사용되는 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) 객체. |
| validationFlags | [XmlSchemaValidationFlags](../../xmlschemavalidationflags/) | 스키마 검증 옵션을 지정하는 XmlSchemaValidationFlags 값. |

## 관련 항목

* Enum [XmlSchemaValidationFlags](../../xmlschemavalidationflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlNameTable](../../../system.xml/xmlnametable/)
* 클래스 [XmlSchemaSet](../../xmlschemaset/)
* 클래스 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* 클래스 [XmlSchemaValidator](../)
* 네임스페이스 [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)