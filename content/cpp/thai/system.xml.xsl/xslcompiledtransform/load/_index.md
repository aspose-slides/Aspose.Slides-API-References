---
title: Load()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: คอมไพล์สไตล์ชีทที่บรรจุอยู่ใน XmlReader.
type: docs
weight: 27
url: /th/system.xml.xsl/xslcompiledtransform/load/
---
## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&) เมธอด

คอมไพล์สไตล์ชีทที่บรรจุอยู่ใน [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | อ็อบเจ็กต์ [XmlReader](../../../system.xml/xmlreader/) ที่บรรจุสไตล์ชีท |

## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) เมธอด

คอมไพล์สไตล์ชีท XSLT ที่บรรจุอยู่ใน [XmlReader](../../../system.xml/xmlreader/). [XmlResolver](../../../system.xml/xmlresolver/) จะทำการแก้ไข any XSLT **import** หรือ **include** elements และการตั้งค่า XSLT กำหนดสิทธิ์สำหรับสไตล์ชีท

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | อ็อบเจ็กต์ [XmlReader](../../../system.xml/xmlreader/) ที่บรรจุสไตล์ชีท |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\>\& | การตั้งค่า [XsltSettings](../../xsltsettings/) ที่ใช้กับสไตล์ชีท หากเป็น **nullptr** การตั้งค่า [XsltSettings::get_Default](../../xsltsettings/get_default/) จะถูกนำมาใช้ |
| stylesheetResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | อ็อบเจ็กต์ [XmlResolver](../../../system.xml/xmlresolver/) ที่ใช้เพื่อแก้ไขสไตล์ชีทใด ๆ ที่อ้างอิงใน XSLT **import** และ **include** หากเป็น **nullptr** จะไม่แก้ไขแหล่งข้อมูลภายนอก |

## XslCompiledTransform::Load(const String\&) เมธอด

โหลดและคอมไพล์สไตล์ชีทที่อยู่ตาม URI ที่ระบุ

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stylesheetUri | const [String](../../../system/string/)\& | URI ของสไตล์ชีท |

## XslCompiledTransform::Load(const String\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) เมธอด

โหลดและคอมไพล์สไตล์ชีท XSLT ที่กำหนดโดย URI. [XmlResolver](../../../system.xml/xmlresolver/) จะทำการแก้ไข any XSLT **import** หรือ **include** elements และการตั้งค่า XSLT กำหนดสิทธิ์สำหรับสไตล์ชีท

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stylesheetUri | const [String](../../../system/string/)\& | URI ของสไตล์ชีท |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\>\& | การตั้งค่า [XsltSettings](../../xsltsettings/) ที่ใช้กับสไตล์ชีท หากเป็น **nullptr** การตั้งค่า [XsltSettings::get_Default](../../xsltsettings/get_default/) จะถูกนำมาใช้ |
| stylesheetResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | อ็อบเจ็กต์ [XmlResolver](../../../system.xml/xmlresolver/) ที่ใช้เพื่อแก้ไข URI ของสไตล์ชีทและสไตล์ชีทใด ๆ ที่อ้างอิงใน XSLT **import** และ **include** |

## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) เมธอด

คอมไพล์สไตล์ชีทที่บรรจุอยู่ในอ็อบเจ็กต์ IXPathNavigable

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | อ็อบเจ็กต์ที่ทำตามอินเทอร์เฟส IXPathNavigable. สามารถเป็น [XmlNode](../../../system.xml/xmlnode/) (โดยทั่วไปเป็น [XmlDocument](../../../system.xml/xmldocument/)) หรือ XPathDocument ที่บรรจุสไตล์ชีท |

## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, SharedPtr\<XsltSettings\>, SharedPtr\<XmlResolver\>) เมธอด

คอมไพล์สไตล์ชีท XSLT ที่บรรจุอยู่ใน IXPathNavigable. [XmlResolver](../../../system.xml/xmlresolver/) จะทำการแก้ไข any XSLT **import** หรือ **include** elements และการตั้งค่า XSLT กำหนดสิทธิ์สำหรับสไตล์ชีท

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, SharedPtr<XsltSettings> settings, SharedPtr<XmlResolver> stylesheetResolver)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | อ็อบเจ็กต์ที่ทำตามอินเทอร์เฟส IXPathNavigable. สามารถเป็น [XmlNode](../../../system.xml/xmlnode/) (โดยทั่วไปเป็น [XmlDocument](../../../system.xml/xmldocument/)) หรือ XPathDocument ที่บรรจุสไตล์ชีท |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\> | การตั้งค่า [XsltSettings](../../xsltsettings/) ที่ใช้กับสไตล์ชีท หากเป็น **nullptr** การตั้งค่า [XsltSettings::get_Default](../../xsltsettings/get_default/) จะถูกนำมาใช้ |
| stylesheetResolver | [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\> | อ็อบเจ็กต์ [XmlResolver](../../../system.xml/xmlresolver/) ที่ใช้เพื่อแก้ไขสไตล์ชีทใด ๆ ที่อ้างอิงใน XSLT **import** และ **include** หากเป็น **nullptr** จะไม่แก้ไขแหล่งข้อมูลภายนอก |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XslCompiledTransform](../)
* Class [XsltSettings](../../xsltsettings/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [String](../../../system/string/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)