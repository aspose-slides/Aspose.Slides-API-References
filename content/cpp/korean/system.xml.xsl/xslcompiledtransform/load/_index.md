---
title: Load()
second_title: Aspose.Slides for C++ API 레퍼런스
description: XmlReader에 포함된 스타일 시트를 컴파일합니다.
type: docs
weight: 27
url: /ko/system.xml.xsl/xslcompiledtransform/load/
---
## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&) 메서드


[XmlReader](../../../system.xml/xmlreader/)에 포함된 스타일 시트를 컴파일합니다.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | 스타일 시트를 포함하는 [XmlReader](../../../system.xml/xmlreader/)입니다. |

## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) 메서드


[XmlReader](../../../system.xml/xmlreader/)에 포함된 XSLT 스타일 시트를 컴파일합니다. [XmlResolver](../../../system.xml/xmlresolver/)는 XSLT **import** 또는 **include** 요소를 해결하고 XSLT 설정은 스타일 시트에 대한 권한을 결정합니다.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | 스타일 시트를 포함하는 [XmlReader](../../../system.xml/xmlreader/)입니다. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\>\& | 스타일 시트에 적용할 [XsltSettings](../../xsltsettings/)입니다. **nullptr**인 경우 [XsltSettings::get_Default](../../xsltsettings/get_default/) 설정이 적용됩니다. |
| stylesheetResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | XSLT **import** 및 **include** 요소에서 참조되는 모든 스타일 시트를 해결하는 데 사용되는 [XmlResolver](../../../system.xml/xmlresolver/)입니다. **nullptr**인 경우 외부 리소스가 해결되지 않습니다. |

## XslCompiledTransform::Load(const String\&) 메서드


지정된 URI에 위치한 스타일 시트를 로드하고 컴파일합니다.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stylesheetUri | const [String](../../../system/string/)\& | 스타일 시트의 URI입니다. |

## XslCompiledTransform::Load(const String\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) 메서드


URI로 지정된 XSLT 스타일 시트를 로드하고 컴파일합니다. [XmlResolver](../../../system.xml/xmlresolver/)는 XSLT **import** 또는 **include** 요소를 해결하고 XSLT 설정은 스타일 시트에 대한 권한을 결정합니다.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stylesheetUri | const [String](../../../system/string/)\& | 스타일 시트의 URI입니다. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\>\& | 스타일 시트에 적용할 [XsltSettings](../../xsltsettings/)입니다. **nullptr**인 경우 [XsltSettings::get_Default](../../xsltsettings/get_default/) 설정이 적용됩니다. |
| stylesheetResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | 스타일 시트 URI와 XSLT **import** 및 **include** 요소에서 참조되는 모든 스타일 시트를 해결하는 데 사용되는 [XmlResolver](../../../system.xml/xmlresolver/)입니다. |

## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) 메서드


IXPathNavigable 객체에 포함된 스타일 시트를 컴파일합니다.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable 인터페이스를 구현하는 객체입니다. 이는 [XmlNode](../../../system.xml/xmlnode/)(일반적으로 [XmlDocument](../../../system.xml/xmldocument/))이거나 스타일 시트를 포함하는 XPathDocument일 수 있습니다. |

## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, SharedPtr\<XsltSettings\>, SharedPtr\<XmlResolver\>) 메서드


IXPathNavigable에 포함된 XSLT 스타일 시트를 컴파일합니다. [XmlResolver](../../../system.xml/xmlresolver/)는 XSLT **import** 또는 **include** 요소를 해결하고 XSLT 설정은 스타일 시트에 대한 권한을 결정합니다.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, SharedPtr<XsltSettings> settings, SharedPtr<XmlResolver> stylesheetResolver)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable 인터페이스를 구현하는 객체입니다. 이는 [XmlNode](../../../system.xml/xmlnode/)(일반적으로 [XmlDocument](../../../system.xml/xmldocument/))이거나 스타일 시트를 포함하는 XPathDocument일 수 있습니다. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\> | 스타일 시트에 적용할 [XsltSettings](../../xsltsettings/)입니다. **nullptr**인 경우 [XsltSettings::get_Default](../../xsltsettings/get_default/) 설정이 적용됩니다. |
| stylesheetResolver | [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\> | XSLT **import** 및 **include** 요소에서 참조되는 모든 스타일 시트를 해결하는 데 사용되는 [XmlResolver](../../../system.xml/xmlresolver/)입니다. **nullptr**인 경우 외부 리소스가 해결되지 않습니다. |

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XslCompiledTransform](../)
* Class [XsltSettings](../../xsltsettings/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [String](../../../system/string/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)