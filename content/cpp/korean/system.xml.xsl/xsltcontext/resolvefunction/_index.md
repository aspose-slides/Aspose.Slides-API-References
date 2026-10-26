---
title: ResolveFunction()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 파생 클래스에서 재정의될 경우, 함수 참조를 해결하고 해당 함수를 나타내는 IXsltContextFunction을 반환합니다. IXsltContextFunction은 실행 시 함수의 반환 값을 얻는 데 사용됩니다.
type: docs
weight: 27
url: /ko/system.xml.xsl/xsltcontext/resolvefunction/
---
## XsltContext::ResolveFunction(String, String, ArrayPtr\<System::Xml::XPath::XPathResultType\>) 메서드

파생 클래스에서 재정의될 경우, 함수 참조를 해결하고 해당 함수를 나타내는 [IXsltContextFunction](../../ixsltcontextfunction/)를 반환합니다. [IXsltContextFunction](../../ixsltcontextfunction/)는 실행 시 함수의 반환 값을 가져오는 데 사용됩니다.

```cpp
virtual SharedPtr<IXsltContextFunction> System::Xml::Xsl::XsltContext::ResolveFunction(String prefix, String name, ArrayPtr<System::Xml::XPath::XPathResultType> ArgTypes)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | 함수가 [XPath](../../../system.xml.xpath/) 식에 나타나는 접두사입니다. |
| name | [String](../../../system/string/) | 함수의 이름입니다. |
| ArgTypes | [ArrayPtr](../../../system/arrayptr/)\<[System::Xml::XPath::XPathResultType](../../../system.xml.xpath/xpathresulttype/)\> | 해결되는 함수의 인수 유형 배열입니다. 이를 통해 동일한 이름을 가진 메서드(예: 오버로드된 메서드) 중에서 선택할 수 있습니다. |

### 반환값

함수를 나타내는 [IXsltContextFunction](../../ixsltcontextfunction/)입니다.

## 참조

* Enum [XPathResultType](../../../system.xml.xpath/xpathresulttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IXsltContextFunction](../../ixsltcontextfunction/)
* Class [String](../../../system/string/)
* Class [XsltContext](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)