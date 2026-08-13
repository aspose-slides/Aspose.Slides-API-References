---
title: Evaluate()
second_title: Aspose.Slides for C++ API 참조
description: 런타임에 변수를 평가하고 변수의 값을 나타내는 객체를 반환합니다.
type: docs
weight: 40
url: /ko/system.xml.xsl/ixsltcontextvariable/evaluate/
---
## IXsltContextVariable::Evaluate(SharedPtr\<XsltContext\>) 메서드

런타임에 변수를 평가하고 변수의 값을 나타내는 객체를 반환합니다.

```cpp
virtual SharedPtr<Object> System::Xml::Xsl::IXsltContextVariable::Evaluate(SharedPtr<XsltContext> xsltContext)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xsltContext | [SharedPtr](../../../system/sharedptr/)\<[XsltContext](../../xsltcontext/)\> | 변수의 실행 컨텍스트를 나타내는 [XsltContext](../../xsltcontext/). |

### 반환값

[Object](../../../system/object/)은 변수의 값을 나타냅니다. 가능한 반환 유형에는 숫자, 문자열, [Boolean](../../../system/boolean/), 문서 조각 또는 노드 세트가 포함됩니다.

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Object](../../../system/object/)
* 클래스 [XsltContext](../../xsltcontext/)
* 클래스 [IXsltContextVariable](../)
* 네임스페이스 [System::Xml::Xsl](../../)
* 라이브러리 [Aspose.Slides](../../../)