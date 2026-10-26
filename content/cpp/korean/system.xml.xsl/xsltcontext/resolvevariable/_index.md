---
title: ResolveVariable()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 파생 클래스에서 재정의될 경우, 변수 참조를 해결하고 변수를 나타내는 IXsltContextVariable를 반환합니다.
type: docs
weight: 14
url: /ko/system.xml.xsl/xsltcontext/resolvevariable/
---
## XsltContext::ResolveVariable(String, String) 메서드

파생 클래스에서 재정의될 때, 변수 참조를 해결하고 변수를 나타내는 [IXsltContextVariable](../../ixsltcontextvariable/)를 반환합니다.

```cpp
virtual SharedPtr<IXsltContextVariable> System::Xml::Xsl::XsltContext::ResolveVariable(String prefix, String name)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | [XPath](../../../system.xml.xpath/) 식에서 나타나는 변수의 접두사입니다. |
| name | [String](../../../system/string/) | 변수의 이름입니다. |

### 반환 값

런타임에 변수를 나타내는 [IXsltContextVariable](../../ixsltcontextvariable/)입니다.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IXsltContextVariable](../../ixsltcontextvariable/)
* 클래스 [String](../../../system/string/)
* 클래스 [XsltContext](../)
* 네임스페이스 [System::Xml::Xsl](../../)
* 라이브러리 [Aspose.Slides](../../../)