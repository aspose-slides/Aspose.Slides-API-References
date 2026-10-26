---
title: AddSort()
second_title: Aspose.Slides สำหรับ C++: เอกสารอ้างอิง API
description: เมื่อทำการเขียนทับในคลาสที่สืบทอด จะทำการเรียงลำดับโหนดที่เลือกโดยนิพจน์ XPath ตามวัตถุ IComparer ที่ระบุ
type: docs
weight: 27
url: /th/system.xml.xpath/xpathexpression/addsort/
---
## XPathExpression::AddSort(SharedPtr\<Object\>, SharedPtr\<Collections::Generic::IComparer\<SharedPtr\<Object\>\>\>) เมธอด


เมื่อทำการเขียนทับในคลาสที่สืบทอด จะทำการเรียงลำดับโหนดที่เลือกโดยนิพจน์ [XPath](../../) ตามวัตถุ IComparer ที่ระบุ

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, SharedPtr<Collections::Generic::IComparer<SharedPtr<Object>>> comparer)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | วัตถุที่เป็นตัวแทนคีย์การเรียงลำดับ ซึ่งอาจเป็นค่า **string** ของโหนดหรือวัตถุ [XPathExpression](../) ที่มีนิพจน์ [XPath](../../) ที่คอมไพล์แล้ว |
| comparer | [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IComparer](../../../system.collections.generic/icomparer/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\> | วัตถุ IComparer ที่ให้การเปรียบเทียบประเภทข้อมูลเฉพาะสำหรับการเปรียบเทียบวัตถุสองตัวเพื่อความเท่ากัน |

## XPathExpression::AddSort(SharedPtr\<Object\>, XmlSortOrder, XmlCaseOrder, String, XmlDataType) เมธอด


เมื่อทำการเขียนทับในคลาสที่สืบทอด จะทำการเรียงลำดับโหนดที่เลือกโดยนิพจน์ [XPath](../../) ตามพารามิเตอร์ที่ระบุ

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, XmlSortOrder order, XmlCaseOrder caseOrder, String lang, XmlDataType dataType)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | วัตถุที่เป็นตัวแทนคีย์การเรียงลำดับ ซึ่งอาจเป็นค่า **string** ของโหนดหรือวัตถุ [XPathExpression](../) ที่มีนิพจน์ [XPath](../../) ที่คอมไพล์แล้ว |
| order | [XmlSortOrder](../../xmlsortorder/) | ค่า XmlSortOrder ที่ระบุลำดับการเรียง |
| caseOrder | [XmlCaseOrder](../../xmlcaseorder/) | ค่า XmlCaseOrder ที่ระบุวิธีการเรียงลำดับตัวอักษรตัวพิมพ์ใหญ่และตัวพิมพ์เล็ก |
| lang | [String](../../../system/string/) | ภาษาที่ใช้ในการเปรียบเทียบ ใช้คลาส [Globalization::CultureInfo](../../../system.globalization/cultureinfo/) ที่สามารถส่งต่อไปยังเมธอด [String::Compare](../../../system/string/compare/) สำหรับประเภทภาษาต่าง ๆ เช่น \"us-en\" สำหรับภาษาอังกฤษสหรัฐ หากระบุสตริงว่าง ระบบจะใช้สภาพแวดล้อมเพื่อกำหนด [Globalization::CultureInfo](../../../system.globalization/cultureinfo/) |
| dataType | [XmlDataType](../../xmldatatype/) | ค่า XmlDataType ที่ระบุลำดับการเรียงสำหรับประเภทข้อมูล |

## ดูเพิ่มเติม

* Enum [XmlSortOrder](../../xmlsortorder/)
* Enum [XmlCaseOrder](../../xmlcaseorder/)
* Enum [XmlDataType](../../xmldatatype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Object](../../../system/object/)
* คลาส [IComparer](../../../system.collections.generic/icomparer/)
* คลาส [XPathExpression](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [System::Xml::XPath](../../)
* ไลบรารี [Aspose.Slides](../../../)