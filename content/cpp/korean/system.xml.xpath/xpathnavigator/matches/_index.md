---
title: Matches()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 노드가 지정된 XPathExpression과 일치하는지 확인합니다.
type: docs
weight: 820
url: /ko/system.xml.xpath/xpathnavigator/matches/
---
## XPathNavigator::Matches(SharedPtr\<XPathExpression\>) 메서드


현재 노드가 지정된 [XPathExpression](../../xpathexpression/)와 일치하는지 확인합니다.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::Matches(SharedPtr<XPathExpression> expr)
```


### 매개변수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | [XPathExpression](../../xpathexpression/) 객체이며 컴파일된 [XPath](../../) 식을 포함합니다. |

### 반환값

**true** 현재 노드가 [XPathExpression](../../xpathexpression/)와 일치하면; 그렇지 않으면 **false**.

## XPathNavigator::Matches(String) 메서드


현재 노드가 지정된 [XPath](../../) 식과 일치하는지 확인합니다.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::Matches(String xpath)
```


### 매개변수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | [XPath](../../) 식. |

### 반환값

**true** 현재 노드가 지정된 [XPath](../../) 식과 일치하면; 그렇지 않으면 **false**.

## 참고

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [XPathExpression](../../xpathexpression/)
* 클래스 [XPathNavigator](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [System::Xml::XPath](../../)
* 라이브러리 [Aspose.Slides](../../../)