---
title: ResolveFunction()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เมื่อถูก override ในคลาสที่สืบทอด จะตรวจหาการอ้างอิงฟังก์ชันและคืนค่า IXsltContextFunction ที่เป็นตัวแทนของฟังก์ชัน IXsltContextFunction จะถูกใช้ในช่วงเวลาปฏิบัติการเพื่อดึงค่าที่ส่งคืนของฟังก์ชัน
type: docs
weight: 27
url: /th/system.xml.xsl/xsltcontext/resolvefunction/
---
## XsltContext::ResolveFunction(String, String, ArrayPtr\<System::Xml::XPath::XPathResultType\>) method


เมื่อถูก override ในคลาสที่สืบทอด จะตรวจหาการอ้างอิงฟังก์ชันและคืนค่า [IXsltContextFunction](../../ixsltcontextfunction/) ที่เป็นตัวแทนของฟังก์ชัน [IXsltContextFunction](../../ixsltcontextfunction/) จะถูกใช้ในช่วงเวลาปฏิบัติการเพื่อดึงค่าที่ส่งคืนของฟังก์ชัน

```cpp
virtual SharedPtr<IXsltContextFunction> System::Xml::Xsl::XsltContext::ResolveFunction(String prefix, String name, ArrayPtr<System::Xml::XPath::XPathResultType> ArgTypes)=0
```


### อากิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | คำนำหน้าของฟังก์ชันตามที่ปรากฏในนิพจน์ [XPath](../../../system.xml.xpath/) |
| name | [String](../../../system/string/) | ชื่อของฟังก์ชัน |
| ArgTypes | [ArrayPtr](../../../system/arrayptr/)\<[System::Xml::XPath::XPathResultType](../../../system.xml.xpath/xpathresulttype/)\> | อาเรย์ของประเภทอาร์กิวเมนต์สำหรับฟังก์ชันที่กำลังตรวจหา โดยสิ่งนี้ทำให้คุณเลือกได้ระหว่างเมธอดที่มีชื่อเดียวกัน (เช่น เมธอดที่มีการโอเวอร์โหลด) |

### ค่าที่ส่งคืน

อ็อบเจ็กต์ [IXsltContextFunction](../../ixsltcontextfunction/) ที่เป็นตัวแทนของฟังก์ชัน

## ดูเพิ่มเติม

* Enum [XPathResultType](../../../system.xml.xpath/xpathresulttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [IXsltContextFunction](../../ixsltcontextfunction/)
* คลาส [String](../../../system/string/)
* คลาส [XsltContext](../)
* เนมสเปซ [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)