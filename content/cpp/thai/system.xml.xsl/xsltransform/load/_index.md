---
title: Load()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: โหลดแผ่นสไตล์ XSLT ที่อยู่ใน XmlReader.
type: docs
weight: 27
url: /th/system.xml.xsl/xsltransform/load/
---
## XslTransform::Load(const SharedPtr\<XmlReader\>\&) method

โหลดแผ่นสไตล์ XSLT ที่บรรจุอยู่ใน [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | อ็อบเจ็กต์ [XmlReader](../../../system.xml/xmlreader/) ที่บรรจุแผ่นสไตล์ XSLT |

## XslTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

โหลดแผ่นสไตล์ XSLT ที่บรรจุอยู่ใน [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | อ็อบเจ็กต์ [XmlReader](../../../system.xml/xmlreader/) ที่บรรจุแผ่นสไตล์ XSLT |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) ที่ใช้เพื่อโหลดแผ่นสไตล์ใด ๆ ที่อ้างอิงใน **xsl:import** และ **xsl:include**. หากเป็น **nullptr** จะไม่ทำการแก้ไขแหล่งข้อมูลภายนอก. [XmlResolver](../../../system.xml/xmlresolver/) จะไม่ถูกแคชหลังจากเมธอดนี้ทำงานเสร็จ |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) method

โหลดแผ่นสไตล์ XSLT ที่บรรจุอยู่ใน IXPathNavigable.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | อ็อบเจ็กต์ที่ทำการนำเข้าอินเทอร์เฟซ IXPathNavigable. อาจเป็น [XmlNode](../../../system.xml/xmlnode/) (โดยทั่วไปคือ [XmlDocument](../../../system.xml/xmldocument/)) หรือ XPathDocument ที่บรรจุแผ่นสไตล์ XSLT |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

โหลดแผ่นสไตล์ XSLT ที่บรรจุอยู่ใน IXPathNavigable.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | อ็อบเจ็กต์ที่ทำการนำเข้าอินเทอร์เฟซ IXPathNavigable. อาจเป็น [XmlNode](../../../system.xml/xmlnode/) (โดยทั่วไปคือ [XmlDocument](../../../system.xml/xmldocument/)) หรือ XPathDocument ที่บรรจุแผ่นสไตล์ XSLT |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) ที่ใช้เพื่อโหลดแผ่นสไตล์ใด ๆ ที่อ้างอิงใน **xsl:import** และ **xsl:include**. หากเป็น **nullptr** จะไม่ทำการแก้ไขแหล่งข้อมูลภายนอก. [XmlResolver](../../../system.xml/xmlresolver/) จะไม่ถูกแคชหลังจากเมธอดนี้ทำงานเสร็จ |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&) method

โหลดแผ่นสไตล์ XSLT ที่บรรจุอยู่ใน XPathNavigator.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | อ็อบเจ็กต์ XPathNavigator ที่บรรจุแผ่นสไตล์ XSLT |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

โหลดแผ่นสไตล์ XSLT ที่บรรจุอยู่ใน XPathNavigator.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | อ็อบเจ็กต์ XPathNavigator ที่บรรจุแผ่นสไตล์ XSLT |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) ที่ใช้เพื่อโหลดแผ่นสไตล์ใด ๆ ที่อ้างอิงใน **xsl:import** และ **xsl:include**. หากเป็น **nullptr** จะไม่ทำการแก้ไขแหล่งข้อมูลภายนอก. [XmlResolver](../../../system.xml/xmlresolver/) จะไม่ถูกแคชหลังจากเมธอดนี้ทำงานเสร็จ |

## XslTransform::Load(const String\&) method

โหลดแผ่นสไตล์ XSLT ที่ระบุโดย URL.

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL ที่ระบุแผ่นสไตล์ XSLT ที่จะโหลด |

## XslTransform::Load(const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

โหลดแผ่นสไตล์ XSLT ที่ระบุโดย URL.

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL ที่ระบุแผ่นสไตล์ XSLT ที่จะโหลด |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) ที่ใช้เพื่อโหลดแผ่นสไตล์และแผ่นสไตล์ใด ๆ ที่อ้างอิงใน **xsl:import** และ **xsl:include**. หากเป็น **nullptr** จะใช้ [XmlUrlResolver](../../../system.xml/xmlurlresolver/) ค่าเริ่มต้นโดยไม่มีข้อมูลประจำตัวผู้ใช้เพื่อเปิดแผ่นสไตล์. [XmlUrlResolver](../../../system.xml/xmlurlresolver/) ค่าเริ่มต้นจะไม่ถูกใช้เพื่อแก้ไขแหล่งข้อมูลภายนอกในแผ่นสไตล์, ดังนั้น **xsl:import** และ **xsl:include** จะไม่ถูกแก้ไข. [XmlResolver](../../../system.xml/xmlresolver/) จะไม่ถูกแคชหลังจากเมธอดนี้ทำงานเสร็จ |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlReader](../../../system.xml/xmlreader/)
* คลาส [XslTransform](../)
* คลาส [XmlResolver](../../../system.xml/xmlresolver/)
* คลาส [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* คลาส [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* คลาส [String](../../../system/string/)
* เนมส페ซ [System::Xml::Xsl](../../)
* ไลบรารี [Aspose.Slides](../../../)