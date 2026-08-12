---
title: Transform()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ทำการแปลงข้อมูล XML ใน XPathNavigator โดยใช้ args ที่ระบุและส่งผลลัพธ์ไปยัง XmlReader.
type: docs
weight: 40
url: /th/system.xml.xsl/xsltransform/transform/
---
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

แปลงข้อมูล XML ใน XPathNavigator โดยใช้ **args** ที่ระบุและส่งผลลัพธ์ไปยัง [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | XPathNavigator ที่บรรจุข้อมูลที่จะถูกแปลง |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) ที่บรรจุอาร์กิวเมนต์ที่กำหนดด้วยเนมสเปซและใช้เป็นข้อมูลเข้าในการแปลง |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) ที่ใช้เพื่อแก้ไขฟังก์ชัน XSLT **document()**. หากเป็น **nullptr** ฟังก์ชัน **document()** จะไม่ได้รับการแก้ไข. [XmlResolver](../../../system.xml/xmlresolver/) จะไม่ถูกเก็บในแคชหลังจากเมธอดนี้เสร็จสิ้น |

### ค่าที่ส่งกลับ

[XmlReader](../../../system.xml/xmlreader/) ที่บรรจุผลลัพธ์ของการแปลง

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&) method

แปลงข้อมูล XML ใน XPathNavigator โดยใช้ **args** ที่ระบุและส่งผลลัพธ์ไปยัง [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | XPathNavigator ที่บรรจุข้อมูลที่จะถูกแปลง |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) ที่บรรจุอาร์กิวเมนต์ที่กำหนดด้วยเนมสเปซและใช้เป็นข้อมูลเข้าในการแปลง |

### ค่าที่ส่งกลับ

[XmlReader](../../../system.xml/xmlreader/) ที่บรรจุผลลัพธ์ของการแปลง

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

แปลงข้อมูล XML ใน XPathNavigator โดยใช้ args ที่ระบุและส่งผลลัพธ์ไปยัง [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | XPathNavigator ที่บรรจุข้อมูลที่จะถูกแปลง |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) ที่บรรจุอาร์กิวเมนต์ที่กำหนดด้วยเนมสเปซและใช้เป็นข้อมูลเข้าในการแปลง |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) ที่คุณต้องการส่งออก |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) ที่ใช้เพื่อแก้ไขฟังก์ชัน XSLT **document()**. หากเป็น **nullptr** ฟังก์ชัน **document()** จะไม่ได้รับการแก้ไข. [XmlResolver](../../../system.xml/xmlresolver/) จะไม่ถูกเก็บในแคชหลังจากเมธอดนี้เสร็จสิ้น |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method

แปลงข้อมูล XML ใน XPathNavigator โดยใช้ args ที่ระบุและส่งผลลัพธ์ไปยัง [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | XPathNavigator ที่บรรจุข้อมูลที่จะถูกแปลง |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) ที่บรรจุอาร์กิวเมนต์ที่กำหนดด้วยเนมสเปซและใช้เป็นข้อมูลเข้าในการแปลง |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) ที่คุณต้องการส่งออก |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

แปลงข้อมูล XML ใน XPathNavigator โดยใช้ **args** ที่ระบุและส่งผลลัพธ์ไปยัง Stream.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | XPathNavigator ที่บรรจุข้อมูลที่จะถูกแปลง |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) ที่บรรจุอาร์กิวเมนต์ที่กำหนดด้วยเนมสเปซและใช้เป็นข้อมูลเข้าในการแปลง |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Stream ที่คุณต้องการส่งออก |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) ที่ใช้เพื่อแก้ไขฟังก์ชัน XSLT **document()**. หากเป็น **nullptr** ฟังก์ชัน **document()** จะไม่ได้รับการแก้ไข. [XmlResolver](../../../system.xml/xmlresolver/) จะไม่ถูกเก็บในแคชหลังจากเมธอดนี้เสร็จสิ้น |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method

แปลงข้อมูล XML ใน XPathNavigator โดยใช้ **args** ที่ระบุและส่งผลลัพธ์ไปยัง Stream.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | XPathNavigator ที่บรรจุข้อมูลที่จะถูกแปลง |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) ที่บรรจุอาร์กิวเมนต์ที่กำหนดด้วยเนมสเปซและใช้เป็นข้อมูลเข้าในการแปลง |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Stream ที่คุณต้องการส่งออก |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

แปลงข้อมูล XML ใน XPathNavigator โดยใช้ **args** ที่ระบุและส่งผลลัพธ์ไปยัง TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | XPathNavigator ที่บรรจุข้อมูลที่จะถูกแปลง |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) ที่บรรจุอาร์กิวเมนต์ที่กำหนดด้วยเนมสเปซและใช้เป็นข้อมูลเข้าในการแปลง |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter ที่คุณต้องการส่งออก |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) ที่ใช้เพื่อแก้ไขฟังก์ชัน XSLT **document()**. หากเป็น **nullptr** ฟังก์ชัน **document()** จะไม่ได้รับการแก้ไข. [XmlResolver](../../../system.xml/xmlresolver/) จะไม่ถูกเก็บในแคชหลังจากเมธอดนี้เสร็จสิ้น |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method

แปลงข้อมูล XML ใน XPathNavigator โดยใช้ **args** ที่ระบุและส่งผลลัพธ์ไปยัง TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | XPathNavigator ที่บรรจุข้อมูลที่จะถูกแปลง |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) ที่บรรจุอาร์กิวเมนต์ที่กำหนดด้วยเนมสเปซและใช้เป็นข้อมูลเข้าในการแปลง |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter ที่คุณต้องการส่งออก |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

แปลงข้อมูล XML ใน IXPathNavigable โดยใช้ **args** ที่ระบุและส่งผลลัพธ์ไปยัง [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | วัตถุที่ทำตามอินเทอร์เฟซ IXPathNavigable. มันอาจเป็น [XmlNode](../../../system.xml/xmlnode/) (โดยทั่วไปคือ [XmlDocument](../../../system.xml/xmldocument/)) หรือ XPathDocument ที่บรรจุข้อมูลที่จะถูกแปลง |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) ที่บรรจุอาร์กิวเมนต์ที่กำหนดด้วยเนมสเปซและใช้เป็นข้อมูลเข้าในการแปลง |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) ที่ใช้เพื่อแก้ไขฟังก์ชัน XSLT **document()**. หากเป็น **nullptr** ฟังก์ชัน **document()** จะไม่ได้รับการแก้ไข. [XmlResolver](../../../system.xml/xmlresolver/) จะไม่ถูกเก็บในแคชหลังจากเมธอดนี้เสร็จสิ้น |

### ค่าที่ส่งกลับ

[XmlReader](../../../system.xml/xmlreader/) ที่บรรจุผลลัพธ์ของการแปลง

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&) method

แปลงข้อมูล XML ใน IXPathNavigable โดยใช้ **args** ที่ระบุและส่งผลลัพธ์ไปยัง [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | วัตถุที่ทำตามอินเทอร์เฟซ IXPathNavigable. มันอาจเป็น [XmlNode](../../../system.xml/xmlnode/) (โดยทั่วไปคือ [XmlDocument](../../../system.xml/xmldocument/)) หรือ XPathDocument ที่บรรจุข้อมูลที่จะถูกแปลง |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) ที่บรรจุอาร์กิวเมนต์ที่กำหนดด้วยเนมสเปซและใช้เป็นข้อมูลเข้าในการแปลง |

### ค่าที่ส่งกลับ

[XmlReader](../../../system.xml/xmlreader/) ที่บรรจุผลลัพธ์ของการแปลง

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

แปลงข้อมูล XML ใน IXPathNavigable โดยใช้ **args** ที่ระบุและส่งผลลัพธ์ไปยัง TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | วัตถุที่ทำตามอินเทอร์เฟซ IXPathNavigable. มันอาจเป็น [XmlNode](../../../system.xml/xmlnode/) (โดยทั่วไปคือ [XmlDocument](../../../system.xml/xmldocument/)) หรือ XPathDocument ที่บรรจุข้อมูลที่จะถูกแปลง |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) ที่บรรจุอาร์กิวเมนต์ที่กำหนดด้วยเนมสเปซและใช้เป็นข้อมูลเข้าในการแปลง |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter ที่คุณต้องการส่งออก |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) ที่ใช้เพื่อแก้ไขฟังก์ชัน XSLT **document()**. หากเป็น **nullptr** ฟังก์ชัน **document()** จะไม่ได้รับการแก้ไข. [XmlResolver](../../../system.xml/xmlresolver/) จะไม่ถูกเก็บในแคชหลังจากเมธอดนี้เสร็จสิ้น |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method

แปลงข้อมูล XML ใน IXPathNavigable โดยใช้ **args** ที่ระบุและส่งผลลัพธ์ไปยัง TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | วัตถุที่ทำตามอินเทอร์เฟซ IXPathNavigable. มันอาจเป็น [XmlNode](../../../system.xml/xmlnode/) (โดยทั่วไปคือ [XmlDocument](../../../system.xml/xmldocument/)) หรือ XPathDocument ที่บรรจุข้อมูลที่จะถูกแปลง |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) ที่บรรจุอาร์กิวเมนต์ที่กำหนดด้วยเนมสเปซและใช้เป็นข้อมูลเข้าในการแปลง |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter ที่คุณต้องการส่งออก |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

แปลงข้อมูล XML ใน IXPathNavigable โดยใช้ **args** ที่ระบุและส่งผลลัพธ์ไปยัง Stream.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | วัตถุที่ทำตามอินเทอร์เฟซ IXPathNavigable. มันอาจเป็น [XmlNode](../../../system.xml/xmlnode/) (โดยทั่วไปคือ [XmlDocument](../../../system.xml/xmldocument/)) หรือ XPathDocument ที่บรรจุข้อมูลที่จะถูกแปลง |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) ที่บรรจุอาร์กิวเมนต์ที่กำหนดด้วยเนมสเปซและใช้เป็นข้อมูลเข้าในการแปลง |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Stream ที่คุณต้องการส่งออก |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) ที่ใช้เพื่อแก้ไขฟังก์ชัน XSLT **document()**. หากเป็น **nullptr** ฟังก์ชัน **document()** จะไม่ได้รับการแก้ไข. [XmlResolver](../../../system.xml/xmlresolver/) จะไม่ถูกเก็บในแคชหลังจากเมธอด [XslTransform::Transform](./) เสร็จสิ้น |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method

แปลงข้อมูล XML ใน IXPathNavigable โดยใช้ **args** ที่ระบุและส่งผลลัพธ์ไปยัง Stream.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | วัตถุที่ทำตามอินเทอร์เฟซ IXPathNavigable. มันอาจเป็น [XmlNode](../../../system.xml/xmlnode/) (โดยทั่วไปคือ [XmlDocument](../../../system.xml/xmldocument/)) หรือ XPathDocument ที่บรรจุข้อมูลที่จะถูกแปลง |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) ที่บรรจุอาร์กิวเมนต์ที่กำหนดด้วยเนมสเปซและใช้เป็นข้อมูลเข้าในการแปลง |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Stream ที่คุณต้องการส่งออก |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

แปลงข้อมูล XML ใน IXPathNavigable โดยใช้ **args** ที่ระบุและส่งผลลัพธ์ไปยัง [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | วัตถุที่ทำตามอินเทอร์เฟซ IXPathNavigable. มันอาจเป็น [XmlNode](../../../system.xml/xmlnode/) (โดยทั่วไปคือ [XmlDocument](../../../system.xml/xmldocument/)) หรือ XPathDocument ที่บรรจุข้อมูลที่จะถูกแปลง |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) ที่บรรจุอาร์กิวเมนต์ที่กำหนดด้วยเนมสเปซและใช้เป็นข้อมูลเข้าในการแปลง |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) ที่คุณต้องการส่งออก |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) ที่ใช้เพื่อแก้ไขฟังก์ชัน XSLT **document()**. หากเป็น **nullptr** ฟังก์ชัน **document()** จะไม่ได้รับการแก้ไข. [XmlResolver](../../../system.xml/xmlresolver/) จะไม่ถูกเก็บในแคชหลังจากเมธอดนี้เสร็จสิ้น |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method

แปลงข้อมูล XML ใน IXPathNavigable โดยใช้ **args** ที่ระบุและส่งผลลัพธ์ไปยัง [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | วัตถุที่ทำตามอินเทอร์เฟซ IXPathNavigable. มันอาจเป็น [XmlNode](../../../system.xml/xmlnode/) (โดยทั่วไปคือ [XmlDocument](../../../system.xml/xmldocument/)) หรือ XPathDocument ที่บรรจุข้อมูลที่จะถูกแปลง |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) ที่บรรจุอาร์กิวเมนต์ที่กำหนดด้วยเนมสเปซและใช้เป็นข้อมูลเข้าในการแปลง |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) ที่คุณต้องการส่งออก |

## XslTransform::Transform(const String\&, const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

แปลงข้อมูล XML ในไฟล์อินพุตและส่งผลลัพธ์ไปยังไฟล์เอาต์พุต.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const String &inputfile, const String &outputfile, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| inputfile | const [String](../../../system/string/)\& | URL ของเอกสารต้นทางที่ต้องการแปลง |
| outputfile | const [String](../../../system/string/)\& | URL ของไฟล์เอาต์พุต |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) ที่ใช้เพื่อแก้ไขฟังก์ชัน XSLT **document()**. หากเป็น **nullptr** ฟังก์ชัน **document()** จะไม่ได้รับการแก้ไข. [XmlResolver](../../../system.xml/xmlresolver/) จะไม่ถูกเก็บในแคชหลังจากเมธอด [XslTransform::Transform](./) เสร็จสิ้น |

## XslTransform::Transform(const String\&, const String\&) method

แปลงข้อมูล XML ในไฟล์อินพุตและส่งผลลัพธ์ไปยังไฟล์เอาต์พุต.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const String &inputfile, const String &outputfile)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| inputfile | const [String](../../../system/string/)\& | URL ของเอกสารต้นทางที่ต้องการแปลง |
| outputfile | const [String](../../../system/string/)\& | URL ของไฟล์เอาต์พุต |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlReader](../../../system.xml/xmlreader/)
* คลาส [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* คลาส [XsltArgumentList](../../xsltargumentlist/)
* คลาส [XmlResolver](../../../system.xml/xmlresolver/)
* คลาส [XslTransform](../)
* คลาส [XmlWriter](../../../system.xml/xmlwriter/)
* คลาส [Stream](../../../system.io/stream/)
* คลาส [TextWriter](../../../system.io/textwriter/)
* คลาส [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* คลาส [String](../../../system/string/)
* เนมสเปซ [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)