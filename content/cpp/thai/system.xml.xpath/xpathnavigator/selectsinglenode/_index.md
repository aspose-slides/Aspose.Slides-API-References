---
title: SelectSingleNode()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: เลือกโหนดเดี่ยวหนึ่งโหนดใน XPathNavigator โดยใช้การค้นหา XPath ที่ระบุ.
type: docs
weight: 781
url: /th/system.xml.xpath/xpathnavigator/selectsinglenode/
---
## XPathNavigator::SelectSingleNode(String) เมธอด

เลือกโหนดเดี่ยวหนึ่งโหนดใน [XPathNavigator](../) โดยใช้การค้นหา [XPath](../../) ที่ระบุ

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | วัตถุ [String](../../../system/string/) ที่เป็นตัวแทนของนิพจน์ [XPath](../../) |

### ค่าที่ส่งคืน

อ็อบเจ็กต์ [XPathNavigator](../) ที่มีโหนดที่ตรงกันเป็นอันดับแรกสำหรับการค้นหา [XPath](../../) ที่ระบุ; มิฉะนั้น **nullptr** หากไม่มีผลลัพธ์การค้นหา

## XPathNavigator::SelectSingleNode(String, SharedPtr\<IXmlNamespaceResolver\>) เมธอด

เลือกโหนดเดี่ยวหนึ่งโหนดใน [XPathNavigator](../) โดยใช้การค้นหา [XPath](../../) ที่ระบุพร้อมกับอ็อบเจ็กต์ [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) เพื่อแก้ไขคำนำหน้าชื่อเนมสเปซ

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | วัตถุ [String](../../../system/string/) ที่เป็นตัวแทนของนิพจน์ [XPath](../../) |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | อ็อบเจ็กต์ [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) ที่ใช้เพื่อแก้ไขคำนำหน้าชื่อเนมสเปซในการค้นหา [XPath](../../) |

### ค่าที่ส่งคืน

อ็อบเจ็กต์ [XPathNavigator](../) ที่มีโหนดที่ตรงกันเป็นอันดับแรกสำหรับการค้นหา [XPath](../../) ที่ระบุ; มิฉะนั้น **nullptr** หากไม่มีผลลัพธ์การค้นหา

## XPathNavigator::SelectSingleNode(SharedPtr\<XPathExpression\>) เมธอด

เลือกโหนดเดี่ยวหนึ่งโหนดใน [XPathNavigator](../) โดยใช้วัตถุ [XPathExpression](../../xpathexpression/) ที่ระบุ

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(SharedPtr<XPathExpression> expression)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| expression | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | วัตถุ [XPathExpression](../../xpathexpression/) ที่บรรจุนิพจน์ [XPath](../../) ที่คอมไพล์แล้ว |

### ค่าที่ส่งคืน

อ็อบเจ็กต์ [XPathNavigator](../) ที่มีโหนดที่ตรงกันเป็นอันดับแรกสำหรับการค้นหา [XPath](../../) ที่ระบุ; มิฉะนั้น **nullptr** หากไม่มีผลลัพธ์การค้นหา

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [XPathNavigator](../)
* คลาส [String](../../../system/string/)
* คลาส [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* คลาส [XPathExpression](../../xpathexpression/)
* เนมสเปซ [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)