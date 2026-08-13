---
title: Invoke()
second_title: Aspose.Slides for C++ API 참조
description: 주어진 컨텍스트에서 주어진 인수를 사용하여 함수를 호출하는 메서드를 제공합니다.
type: docs
weight: 53
url: /ko/system.xml.xsl/ixsltcontextfunction/invoke/
---
## IXsltContextFunction::Invoke(SharedPtr\<XsltContext\>, ArrayPtr\<SharedPtr\<Object\>\>, SharedPtr\<System::Xml::XPath::XPathNavigator\>) method

주어진 컨텍스트에서 주어진 인수를 사용하여 함수를 호출하는 메서드를 제공합니다.

```cpp
virtual SharedPtr<Object> System::Xml::Xsl::IXsltContextFunction::Invoke(SharedPtr<XsltContext> xsltContext, ArrayPtr<SharedPtr<Object>> args, SharedPtr<System::Xml::XPath::XPathNavigator> docContext)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xsltContext | [SharedPtr](../../../system/sharedptr/)\<[XsltContext](../../xsltcontext/)\> | 함수 호출을 위한 XSLT 컨텍스트입니다. |
| args | [ArrayPtr](../../../system/arrayptr/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | 함수 호출의 인수입니다. 각 인수는 배열의 요소입니다. |
| docContext | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | 함수 호출을 위한 컨텍스트 노드입니다. |

### 반환 값

함수의 반환 값을 나타내는 [Object](../../../system/object/).

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [Object](../../../system/object/)
* 클래스 [XsltContext](../../xsltcontext/)
* 클래스 [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* 클래스 [IXsltContextFunction](../)
* 네임스페이스 [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)