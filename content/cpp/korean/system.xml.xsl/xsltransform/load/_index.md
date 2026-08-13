---
title: Load()
second_title: Aspose.Slides for C++ API 레퍼런스
description: XmlReader에 포함된 XSLT 스타일 시트를 로드합니다.
type: docs
weight: 27
url: /ko/system.xml.xsl/xsltransform/load/
---
## XslTransform::Load(const SharedPtr\<XmlReader\>\&) method


[XmlReader](../../../system.xml/xmlreader/)에 포함된 XSLT 스타일 시트를 로드합니다.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | XSLT 스타일 시트를 포함하는 [XmlReader](../../../system.xml/xmlreader/) 객체. |

## XslTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


[XmlReader](../../../system.xml/xmlreader/)에 포함된 XSLT 스타일 시트를 로드합니다.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | XSLT 스타일 시트를 포함하는 [XmlReader](../../../system.xml/xmlreader/) 객체. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | **xsl:import** 및 **xsl:include** 요소에서 참조되는 모든 스타일 시트를 로드하는 데 사용되는 [XmlResolver](../../../system.xml/xmlresolver/). 이 값이 **nullptr**인 경우 외부 리소스가 해석되지 않습니다. [XmlResolver](../../../system.xml/xmlresolver/)는 이 메서드가 완료된 후 캐시되지 않습니다. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) method


IXPathNavigable에 포함된 XSLT 스타일 시트를 로드합니다.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable 인터페이스를 구현하는 객체입니다. 이는 [XmlNode](../../../system.xml/xmlnode/)(일반적으로 [XmlDocument](../../../system.xml/xmldocument/))이거나 XSLT 스타일 시트를 포함하는 XPathDocument일 수 있습니다. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


IXPathNavigable에 포함된 XSLT 스타일 시트를 로드합니다.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable 인터페이스를 구현하는 객체입니다. 이는 [XmlNode](../../../system.xml/xmlnode/)(일반적으로 [XmlDocument](../../../system.xml/xmldocument/))이거나 XSLT 스타일 시트를 포함하는 XPathDocument일 수 있습니다. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | **xsl:import** 및 **xsl:include** 요소에서 참조되는 모든 스타일 시트를 로드하는 데 사용되는 [XmlResolver](../../../system.xml/xmlresolver/). 이 값이 **nullptr**인 경우 외부 리소스가 해석되지 않습니다. [XmlResolver](../../../system.xml/xmlresolver/)는 이 메서드가 완료된 후 캐시되지 않습니다. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&) method


XPathNavigator에 포함된 XSLT 스타일 시트를 로드합니다.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | XSLT 스타일 시트를 포함하는 XPathNavigator 객체. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


XPathNavigator에 포함된 XSLT 스타일 시트를 로드합니다.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | XSLT 스타일 시트를 포함하는 XPathNavigator 객체. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | **xsl:import** 및 **xsl:include** 요소에서 참조되는 모든 스타일 시트를 로드하는 데 사용되는 [XmlResolver](../../../system.xml/xmlresolver/). 이 값이 **nullptr**인 경우 외부 리소스가 해석되지 않습니다. [XmlResolver](../../../system.xml/xmlresolver/)는 이 메서드가 완료된 후 캐시되지 않습니다. |

## XslTransform::Load(const String\&) method


URL로 지정된 XSLT 스타일 시트를 로드합니다.

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | 로드할 XSLT 스타일 시트를 지정하는 URL. |

## XslTransform::Load(const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


URL로 지정된 XSLT 스타일 시트를 로드합니다.

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | 로드할 XSLT 스타일 시트를 지정하는 URL. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | **xsl:import** 및 **xsl:include** 요소에서 참조되는 스타일 시트와 모든 스타일 시트를 로드하는 데 사용되는 [XmlResolver](../../../system.xml/xmlresolver/). 이 값이 **nullptr**인 경우 사용자 자격 증명이 없는 기본 [XmlUrlResolver](../../../system.xml/xmlurlresolver/)가 사용되어 스타일 시트를 엽니다. 기본 [XmlUrlResolver](../../../system.xml/xmlurlresolver/)는 스타일 시트의 외부 리소스를 해석하는 데 사용되지 않으므로 **xsl:import** 및 **xsl:include** 요소가 해석되지 않습니다. [XmlResolver](../../../system.xml/xmlresolver/)는 이 메서드가 완료된 후 캐시되지 않습니다. |

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XslTransform](../)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [String](../../../system/string/)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)