---
title: PreserveWhitespace()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 파생 클래스에서 재정의될 경우, 주어진 컨텍스트에 대해 공백 노드를 보존할지 제거할지를 평가합니다.
type: docs
weight: 40
url: /ko/system.xml.xsl/xsltcontext/preservewhitespace/
---
## XsltContext::PreserveWhitespace(SharedPtr\<System::Xml::XPath::XPathNavigator\>) 메서드


파생 클래스에서 재정의될 경우, 주어진 컨텍스트에 대해 공백 노드를 보존할지 제거할지를 평가합니다.

```cpp
virtual bool System::Xml::Xsl::XsltContext::PreserveWhitespace(SharedPtr<System::Xml::XPath::XPathNavigator> node)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | 현재 컨텍스트에서 보존되거나 제거될 공백 노드. |

### 반환값

**true** if the white space is to be preserved; **false** if the white space is to be stripped.

## 또 보기

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* 클래스 [XsltContext](../)
* 네임스페이스 [System::Xml::Xsl](../../)
* 라이브러리 [Aspose.Slides](../../../)