---
title: Evaluate()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 XPath 식을 평가하고 유형화된 결과를 반환합니다.
type: docs
weight: 807
url: /ko/system.xml.xpath/xpathnavigator/evaluate/
---
## XPathNavigator::Evaluate(String) 메서드


지정된 [XPath](../../) 식을 평가하고 유형화된 결과를 반환합니다.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | 평가할 수 있는 [XPath](../../) 식을 나타내는 문자열입니다. |

### 반환값

식의 결과는 ([Boolean](../../../system/boolean/), 숫자, 문자열, 또는 노드 집합)이며, 이는 각각 [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/), 또는 [XPathNodeIterator](../../xpathnodeiterator/) 객체에 해당합니다.

## XPathNavigator::Evaluate(String, SharedPtr\<IXmlNamespaceResolver\>) 메서드


지정된 [XPath](../../) 식을 평가하고 유형화된 결과를 반환합니다. 이때 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) 객체를 사용하여 [XPath](../../) 식의 네임스페이스 접두사를 해석합니다.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | 평가할 수 있는 [XPath](../../) 식을 나타내는 문자열입니다. |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | [XPath](../../) 식의 네임스페이스 접두사를 해석하는 데 사용되는 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) 객체입니다. |

### 반환값

식의 결과는 ([Boolean](../../../system/boolean/), 숫자, 문자열, 또는 노드 집합)이며, 이는 각각 [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/), 또는 [XPathNodeIterator](../../xpathnodeiterator/) 객체에 해당합니다.

## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>) 메서드


[XPathExpression](../../xpathexpression/)을 평가하고 유형화된 결과를 반환합니다.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | 평가할 수 있는 [XPathExpression](../../xpathexpression/)입니다. |

### 반환값

식의 결과는 ([Boolean](../../../system/boolean/), 숫자, 문자열, 또는 노드 집합)이며, 이는 각각 [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/), 또는 [XPathNodeIterator](../../xpathnodeiterator/) 객체에 해당합니다.

## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>, SharedPtr\<XPathNodeIterator\>) 메서드


제공된 컨텍스트를 사용하여 [XPathExpression](../../xpathexpression/)을 평가하고, 유형화된 결과를 반환합니다.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr, SharedPtr<XPathNodeIterator> context)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | 평가할 수 있는 [XPathExpression](../../xpathexpression/)입니다. |
| context | [SharedPtr](../../../system/sharedptr/)\<[XPathNodeIterator](../../xpathnodeiterator/)\> | 평가를 수행할 선택된 노드 집합을 가리키는 [XPathNodeIterator](../../xpathnodeiterator/)입니다. |

### 반환값

식의 결과는 ([Boolean](../../../system/boolean/), 숫자, 문자열, 또는 노드 집합)이며, 이는 각각 [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/), 또는 [XPathNodeIterator](../../xpathnodeiterator/) 객체에 해당합니다.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Object](../../../system/object/)
* 클래스 [String](../../../system/string/)
* 클래스 [XPathNavigator](../)
* 클래스 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* 클래스 [XPathExpression](../../xpathexpression/)
* 클래스 [XPathNodeIterator](../../xpathnodeiterator/)
* 네임스페이스 [System::Xml::XPath](../../)
* 라이브러리 [Aspose.Slides](../../../)