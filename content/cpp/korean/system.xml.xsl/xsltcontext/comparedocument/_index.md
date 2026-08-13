---
title: CompareDocument()
second_title: Aspose.Slides for C++ API 참조
description: 파생 클래스에서 재정의될 경우, XSLT 프로세서에 의해 문서가 로드된 순서를 기준으로 두 문서의 기본 Uniform Resource Identifiers (URIs)를 비교합니다(즉, XslTransform 클래스).
type: docs
weight: 53
url: /ko/system.xml.xsl/xsltcontext/comparedocument/
---
## XsltContext::CompareDocument(String, String) 메서드

파생 클래스에서 재정의될 때, XSLT 프로세서에 의해 문서가 로드된 순서를 기반으로 두 문서의 기본 Uniform Resource Identifiers(URIs)를 비교합니다(즉, [XslTransform](../../xsltransform/) 클래스).

```cpp
virtual int32_t System::Xml::Xsl::XsltContext::CompareDocument(String baseUri, String nextbaseUri)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| baseUri | [String](../../../system/string/) | 비교할 첫 번째 문서의 기본 URI. |
| nextbaseUri | [String](../../../system/string/) | 비교할 두 번째 문서의 기본 URI. |

### 반환값

두 기본 URI의 상대 순서를 나타내는 정수 값입니다: -1은 **baseUri**가 **nextbaseUri**보다 먼저 나타나는 경우, 0은 두 기본 URI가 동일한 경우, 1은 **baseUri**가 **nextbaseUri**보다 나중에 나타나는 경우입니다.

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [XsltContext](../)
* 네임스페이스 [System::Xml::Xsl](../../)
* 라이브러리 [Aspose.Slides](../../../)