---
title: Transform()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ดำเนินการแปลงโดยใช้เอกสารอินพุตที่ระบุโดยอ็อบเจ็กต์ IXPathNavigable และส่งออกผลลัพธ์ไปยัง XmlWriter.
type: docs
weight: 40
url: /th/system.xml.xsl/xslcompiledtransform/transform/
---
## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XmlWriter\>\&) เมธอด

ดำเนินการแปลงโดยใช้เอกสารอินพุตที่ระบุโดยอ็อบเจ็กต์ IXPathNavigable และส่งออกผลลัพธ์ไปยัง [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XmlWriter> &results)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | วัตถุที่ทำตามอินเตอร์เฟซ IXPathNavigable ซึ่งอาจเป็น [XmlNode](../../../system.xml/xmlnode/) (โดยทั่วไปเป็น [XmlDocument](../../../system.xml/xmldocument/)) หรือ XPathDocument ที่มีข้อมูลที่ต้องแปลง |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) ที่คุณต้องการส่งออก หากแผ่นสไตล์มีองค์ประกอบ **xsl:output** คุณควรสร้าง [XmlWriter](../../../system.xml/xmlwriter/) ด้วยอ็อบเจ็กต์ [XmlWriterSettings](../../../system.xml/xmlwritersettings/) ที่ได้จากค่า [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) นี้ เพื่อให้ [XmlWriter](../../../system.xml/xmlwriter/) มีการตั้งค่าออกผลที่ถูกต้อง |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) เมธอด

ดำเนินการแปลงโดยใช้เอกสารอินพุตที่ระบุโดยอ็อบเจ็กต์ IXPathNavigable และส่งออกผลลัพธ์ไปยัง [XmlWriter](../../../system.xml/xmlwriter/). [XsltArgumentList](../../xsltargumentlist/) ให้ข้อมูลอาร์กิวเมนต์รันไทม์เพิ่มเติม

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | วัตถุที่ทำตามอินเตอร์เฟซ IXPathNavigable ซึ่งอาจเป็น [XmlNode](../../../system.xml/xmlnode/) (โดยทั่วไปเป็น [XmlDocument](../../../system.xml/xmldocument/)) หรือ XPathDocument ที่มีข้อมูลที่ต้องแปลง |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) ที่มีอาร์กิวเมนต์ที่กำหนดด้วยเนมสเปสใช้เป็นอินพุตให้กับการแปลง ค่าตัวนี้อาจเป็น **nullptr** |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) ที่คุณต้องการส่งออก หากแผ่นสไตล์มีองค์ประกอบ **xsl:output** คุณควรสร้าง [XmlWriter](../../../system.xml/xmlwriter/) ด้วยอ็อบเจ็กต์ [XmlWriterSettings](../../../system.xml/xmlwritersettings/) ที่ได้จากค่า [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) นี้ เพื่อให้ [XmlWriter](../../../system.xml/xmlwriter/) มีการตั้งค่าออกผลที่ถูกต้อง |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) เมธอด

ดำเนินการแปลงโดยใช้เอกสารอินพุตที่ระบุโดยอ็อบเจ็กต์ IXPathNavigable และส่งออกผลลัพธ์ไปยัง TextWriter. [XsltArgumentList](../../xsltargumentlist/) ให้ข้อมูลอาร์กิวเมนต์รันไทม์เพิ่มเติม

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | วัตถุที่ทำตามอินเตอร์เฟซ IXPathNavigable ซึ่งอาจเป็น [XmlNode](../../../system.xml/xmlnode/) (โดยทั่วไปเป็น [XmlDocument](../../../system.xml/xmldocument/)) หรือ XPathDocument ที่มีข้อมูลที่ต้องแปลง |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) ที่มีอาร์กิวเมนต์ที่กำหนดด้วยเนมสเปสใช้เป็นอินพุตให้กับการแปลง ค่าตัวนี้อาจเป็น **nullptr** |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter ที่คุณต้องการส่งออก |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) เมธอด

ดำเนินการแปลงโดยใช้เอกสารอินพุตที่ระบุโดยอ็อบเจ็กต์ IXPathNavigable และส่งออกผลลัพธ์ไปยังสตรีม. [XsltArgumentList](../../xsltargumentlist/) ให้ข้อมูลอาร์กิวเมนต์รันไทม์เพิ่มเติม

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | วัตถุที่ทำตามอินเตอร์เฟซ IXPathNavigable ซึ่งอาจเป็น [XmlNode](../../../system.xml/xmlnode/) (โดยทั่วไปเป็น [XmlDocument](../../../system.xml/xmldocument/)) หรือ XPathDocument ที่มีข้อมูลที่ต้องแปลง |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) ที่มีอาร์กิวเมนต์ที่กำหนดด้วยเนมสเปสใช้เป็นอินพุตให้กับการแปลง ค่าตัวนี้อาจเป็น **nullptr** |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | สตรีมที่คุณต้องการส่งออก |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XmlWriter\>\&) เมธอด

ดำเนินการแปลงโดยใช้เอกสารอินพุตที่ระบุโดยอ็อบเจ็กต์ [XmlReader](../../../system.xml/xmlreader/) และส่งออกผลลัพธ์ไปยัง [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XmlWriter> &results)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) ที่บรรจุเอกสารอินพุต |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) ที่คุณต้องการส่งออก หากแผ่นสไตล์มีองค์ประกอบ **xsl:output** คุณควรสร้าง [XmlWriter](../../../system.xml/xmlwriter/) ด้วยอ็อบเจ็กต์ [XmlWriterSettings](../../../system.xml/xmlwritersettings/) ที่ได้จากค่า [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) นี้ เพื่อให้ [XmlWriter](../../../system.xml/xmlwriter/) มีการตั้งค่าออกผลที่ถูกต้อง |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) เมธอด

ดำเนินการแปลงโดยใช้เอกสารอินพุตที่ระบุโดยอ็อบเจ็กต์ [XmlReader](../../../system.xml/xmlreader/) และส่งออกผลลัพธ์ไปยัง [XmlWriter](../../../system.xml/xmlwriter/). [XsltArgumentList](../../xsltargumentlist/) ให้ข้อมูลอาร์กิวเมนต์รันไทม์เพิ่มเติม

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) ที่บรรจุเอกสารอินพุต |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) ที่มีอาร์กิวเมนต์ที่กำหนดด้วยเนมสเปสใช้เป็นอินพุตให้กับการแปลง ค่าตัวนี้อาจเป็น **nullptr** |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) ที่คุณต้องการส่งออก หากแผ่นสไตล์มีองค์ประกอบ **xsl:output** คุณควรสร้าง [XmlWriter](../../../system.xml/xmlwriter/) ด้วยอ็อบเจ็กต์ [XmlWriterSettings](../../../system.xml/xmlwritersettings/) ที่ได้จากค่า [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) นี้ เพื่อให้ [XmlWriter](../../../system.xml/xmlwriter/) มีการตั้งค่าออกผลที่ถูกต้อง |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) เมธอด

ดำเนินการแปลงโดยใช้เอกสารอินพุตที่ระบุโดยอ็อบเจ็กต์ [XmlReader](../../../system.xml/xmlreader/) และส่งออกผลลัพธ์ไปยัง TextWriter. [XsltArgumentList](../../xsltargumentlist/) ให้ข้อมูลอาร์กิวเมนต์รันไทม์เพิ่มเติม

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) ที่บรรจุเอกสารอินพุต |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) ที่มีอาร์กิวเมนต์ที่กำหนดด้วยเนมสเปสใช้เป็นอินพุตให้กับการแปลง ค่าตัวนี้อาจเป็น **nullptr** |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter ที่คุณต้องการส่งออก |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) เมธอด

ดำเนินการแปลงโดยใช้เอกสารอินพุตที่ระบุโดยอ็อบเจ็กต์ [XmlReader](../../../system.xml/xmlreader/) และส่งออกผลลัพธ์ไปยังสตรีม. [XsltArgumentList](../../xsltargumentlist/) ให้ข้อมูลอาร์กิวเมนต์รันไทม์เพิ่มเติม

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) ที่บรรจุเอกสารอินพุต |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) ที่มีอาร์กิวเมนต์ที่กำหนดด้วยเนมสเปสใช้เป็นอินพุตให้กับการแปลง ค่าตัวนี้อาจเป็น **nullptr** |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | สตรีมที่คุณต้องการส่งออก |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XmlWriter\>\&) เมธอด

ดำเนินการแปลงโดยใช้เอกสารอินพุตที่ระบุด้วย URI และส่งออกผลลัพธ์ไปยัง [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XmlWriter> &results)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI ของเอกสารอินพุต |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) ที่คุณต้องการส่งออก หากแผ่นสไตล์มีองค์ประกอบ **xsl:output** คุณควรสร้าง [XmlWriter](../../../system.xml/xmlwriter/) ด้วยอ็อบเจ็กต์ [XmlWriterSettings](../../../system.xml/xmlwritersettings/) ที่ได้จากค่า [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) นี้ เพื่อให้ [XmlWriter](../../../system.xml/xmlwriter/) มีการตั้งค่าออกผลที่ถูกต้อง |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) เมธอด

ดำเนินการแปลงโดยใช้เอกสารอินพุตที่ระบุด้วย URI และส่งออกผลลัพธ์ไปยัง [XmlWriter](../../../system.xml/xmlwriter/). [XsltArgumentList](../../xsltargumentlist/) ให้ข้อมูลอาร์กิวเมนต์รันไทม์เพิ่มเติม

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI ของเอกสารอินพุต |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) ที่มีอาร์กิวเมนต์ที่กำหนดด้วยเนมสเปสใช้เป็นอินพุตให้กับการแปลง ค่าตัวนี้อาจเป็น **nullptr** |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) ที่คุณต้องการส่งออก หากแผ่นสไตล์มีองค์ประกอบ **xsl:output** คุณควรสร้าง [XmlWriter](../../../system.xml/xmlwriter/) ด้วยอ็อบเจ็กต์ [XmlWriterSettings](../../../system.xml/xmlwritersettings/) ที่ได้จากค่า [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) นี้ เพื่อให้ [XmlWriter](../../../system.xml/xmlwriter/) มีการตั้งค่าออกผลที่ถูกต้อง |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) เมธอด

ดำเนินการแปลงโดยใช้เอกสารอินพุตที่ระบุด้วย URI และส่งออกผลลัพธ์ไปยัง TextWriter.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI ของเอกสารอินพุต |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) ที่มีอาร์กิวเมนต์ที่กำหนดด้วยเนมสเปสใช้เป็นอินพุตให้กับการแปลง ค่าตัวนี้อาจเป็น **nullptr** |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter ที่คุณต้องการส่งออก |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) เมธอด

ดำเนินการแปลงโดยใช้เอกสารอินพุตที่ระบุด้วย URI และส่งออกผลลัพธ์ไปยังสตรีม. [XsltArgumentList](../../xsltargumentlist/) ให้ข้อมูลอาร์กิวเมนต์รันไทม์เพิ่มเติม

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI ของเอกสารอินพุต |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) ที่มีอาร์กิวเมนต์ที่กำหนดด้วยเนมสเปสใช้เป็นอินพุตให้กับการแปลง ค่าตัวนี้อาจเป็น **nullptr** |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | สตรีมที่คุณต้องการส่งออก |

## XslCompiledTransform::Transform(const String\&, const String\&) เมธอด

ดำเนินการแปลงโดยใช้เอกสารอินพุตที่ระบุด้วย URI และส่งออกผลลัพธ์ไปยังไฟล์.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const String &resultsFile)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI ของเอกสารอินพุต |
| resultsFile | const [String](../../../system/string/)\& | URI ของไฟล์ผลลัพธ์ |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) เมธอด

ดำเนินการแปลงโดยใช้เอกสารอินพุตที่ระบุโดยอ็อบเจ็กต์ [XmlReader](../../../system.xml/xmlreader/) และส่งออกผลลัพธ์ไปยัง [XmlWriter](../../../system.xml/xmlwriter/). [XsltArgumentList](../../xsltargumentlist/) ให้ข้อมูลอาร์กิวเมนต์รันไทม์เพิ่มเติม และ [XmlResolver](../../../system.xml/xmlresolver/) แก้ไขฟังก์ชัน XSLT **document()**.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) ที่บรรจุเอกสารอินพุต |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) ที่มีอาร์กิวเมนต์ที่กำหนดด้วยเนมสเปสใช้เป็นอินพุตให้กับการแปลง ค่าตัวนี้อาจเป็น **nullptr** |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) ที่คุณต้องการส่งออก หากแผ่นสไตล์มีองค์ประกอบ **xsl:output** คุณควรสร้าง [XmlWriter](../../../system.xml/xmlwriter/) ด้วยอ็อบเจ็กต์ [XmlWriterSettings](../../../system.xml/xmlwritersettings/) ที่ได้จากค่า [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) นี้ เพื่อให้ [XmlWriter](../../../system.xml/xmlwriter/) มีการตั้งค่าออกผลที่ถูกต้อง |
| documentResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) ที่ใช้แก้ไขฟังก์ชัน XSLT **document()** หากเป็น **nullptr** ฟังก์ชัน **document()** จะไม่ถูกแก้ไข |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) เมธอด

ดำเนินการแปลงโดยใช้เอกสารอินพุตที่ระบุโดยอ็อบเจ็กต์ IXPathNavigable และส่งออกผลลัพธ์ไปยัง [XmlWriter](../../../system.xml/xmlwriter/). [XsltArgumentList](../../xsltargumentlist/) ให้ข้อมูลอาร์กิวเมนต์รันไทม์เพิ่มเติม และ [XmlResolver](../../../system.xml/xmlresolver/) แก้ไขฟังก์ชัน XSLT **document()**.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | เอกสารที่ต้องแปลงที่ระบุโดยอ็อบเจ็กต์ IXPathNavigable |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | รายการอาร์กิวเมนต์ตาม [XsltArgumentList](../../xsltargumentlist/) |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) ที่คุณต้องการส่งออก หากแผ่นสไตล์มีองค์ประกอบ **xsl:output** คุณควรสร้าง [XmlWriter](../../../system.xml/xmlwriter/) ด้วยอ็อบเจ็กต์ [XmlWriterSettings](../../../system.xml/xmlwritersettings/) ที่ได้จากค่า [XslCompiledTransform::get_OutputSettings](../get_outputsettings/) นี้ เพื่อให้ [XmlWriter](../../../system.xml/xmlwriter/) มีการตั้งค่าออกผลที่ถูกต้อง |
| documentResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) ที่ใช้แก้ไขฟังก์ชัน XSLT **document()** หากเป็น **nullptr** ฟังก์ชัน **document()** จะไม่ถูกแก้ไข |

## ดูเพิ่มเติม

* ชนิดนิยาม [SharedPtr](../../../system/sharedptr/)
* คลาส [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* คลาส [XmlWriter](../../../system.xml/xmlwriter/)
* คลาส [XslCompiledTransform](../)
* คลาส [XsltArgumentList](../../xsltargumentlist/)
* คลาส [TextWriter](../../../system.io/textwriter/)
* คลาส [Stream](../../../system.io/stream/)
* คลาส [XmlReader](../../../system.xml/xmlreader/)
* คลาส [String](../../../system/string/)
* คลาส [XmlResolver](../../../system.xml/xmlresolver/)
* เนมสเปส [System::Xml::Xsl](../../)
* ไลบรารี [Aspose.Slides](../../../)