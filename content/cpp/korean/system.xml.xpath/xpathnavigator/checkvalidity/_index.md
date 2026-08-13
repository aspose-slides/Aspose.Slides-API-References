---
title: CheckValidity()
second_title: Aspose.Slides for C++ API 레퍼런스
description: XPathNavigator에 있는 XML 데이터가 제공된 XML 스키마 정의 언어 (XSD) 스키마와 일치하는지 확인합니다.
type: docs
weight: 755
url: /ko/system.xml.xpath/xpathnavigator/checkvalidity/
---
## XPathNavigator::CheckValidity(SharedPtr\<System::Xml::Schema::XmlSchemaSet\>, System::Xml::Schema::ValidationEventHandler) method

제공된 XML [Schema](../../../system.xml.schema/) 정의 언어 (XSD) 스키마에 [XPathNavigator](../)의 XML 데이터가 일치하는지 확인합니다.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::CheckValidity(SharedPtr<System::Xml::Schema::XmlSchemaSet> schemas, System::Xml::Schema::ValidationEventHandler validationEventHandler)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| schemas | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)\> | [XPathNavigator](../)에 포함된 XML 데이터를 검증하는 데 사용되는 스키마를 포함하는 XmlSchemaSet입니다. |
| validationEventHandler | [System::Xml::Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | 스키마 검증 경고 및 오류에 대한 정보를 받는 ValidationEventHandler입니다. |

### 반환값

스키마 검증 오류가 발생하지 않으면 **true**, 그렇지 않으면 **false**.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* 클래스 [XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)
* 클래스 [XPathNavigator](../)
* 네임스페이스 [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)