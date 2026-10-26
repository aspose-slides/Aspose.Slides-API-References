---
title: SetContext()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 파생 클래스에서 재정의될 경우, 네임스페이스 해석에 사용할 XmlNamespaceManager 개체를 지정합니다.
type: docs
weight: 53
url: /ko/system.xml.xpath/xpathexpression/setcontext/
---
## XPathExpression::SetContext(SharedPtr\<XmlNamespaceManager\>) 메서드

파생 클래스에서 재정의될 경우, [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/) 객체를 네임스페이스 해석에 사용하도록 지정합니다.

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<XmlNamespaceManager> nsManager)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| nsManager | [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)\> | 네임스페이스 해석에 사용할 [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/) 객체. |

## XPathExpression::SetContext(SharedPtr\<IXmlNamespaceResolver\>) 메서드

파생 클래스에서 재정의될 경우, [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) 객체를 네임스페이스 해석에 사용하도록 지정합니다.

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | 네임스페이스 해석에 사용할 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) 인터페이스를 구현하는 객체. |

## 참고

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)
* 클래스 [XPathExpression](../)
* 클래스 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* 네임스페이스 [System::Xml::XPath](../../)
* 라이브러리 [Aspose.Slides](../../../)