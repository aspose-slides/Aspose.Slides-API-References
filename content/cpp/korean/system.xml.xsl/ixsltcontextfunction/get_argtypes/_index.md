---
title: get_ArgTypes()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 함수 인수 목록에 대한 제공된 XML Path Language (XPath) 유형을 반환합니다. 이 정보를 사용하여 함수 서명을 찾아볼 수 있으며, 이를 통해 오버로드된 함수를 구분할 수 있습니다.
type: docs
weight: 40
url: /ko/system.xml.xsl/ixsltcontextfunction/get_argtypes/
---
## IXsltContextFunction::get_ArgTypes() 메서드

함수의 인수 목록에 대한 제공된 XML Path Language ([XPath](../../../system.xml.xpath/)) 유형을 반환합니다. 이 정보는 함수의 서명을 찾아서 오버로드된 함수들을 구분할 수 있도록 사용할 수 있습니다.

```cpp
virtual ArrayPtr<System::Xml::XPath::XPathResultType> System::Xml::Xsl::IXsltContextFunction::get_ArgTypes()=0
```

### 반환 값

함수의 인수 목록에 대한 유형을 나타내는 XPathResultType 배열입니다.

## 참고

* Enum [XPathResultType](../../../system.xml.xpath/xpathresulttype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IXsltContextFunction](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)