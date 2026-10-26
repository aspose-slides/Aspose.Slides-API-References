---
title: Compile()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 XPath 식을 컴파일하고 XPath 식을 나타내는 XPathExpression 객체를 반환합니다.
type: docs
weight: 66
url: /ko/system.xml.xpath/xpathexpression/compile/
---
## XPathExpression::Compile(const String\&) method

지정된 [XPath](../../) 식을 컴파일하고 [XPath](../../) 식을 나타내는 [XPathExpression](../) 객체를 반환합니다.

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | [XPath](../../) 식 |

### 반환 값

[XPathExpression](../) 객체.

## XPathExpression::Compile(const String\&, const SharedPtr\<IXmlNamespaceResolver\>\&) method

지정된 [XPath](../../) 식을 컴파일하고, 네임스페이스 해결을 위해 지정된 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) 객체를 사용하여 [XPath](../../) 식을 나타내는 [XPathExpression](../) 객체를 반환합니다.

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath, const SharedPtr<IXmlNamespaceResolver> &nsResolver)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | [XPath](../../) 식 |
| nsResolver | const [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\>\& | 네임스페이스 해결을 위한 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) 인터페이스를 구현하는 객체 |

### 반환 값

[XPathExpression](../) 객체.

## 추가 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [XPathExpression](../)
* 클래스 [String](../../../system/string/)
* 클래스 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* 네임스페이스 [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)