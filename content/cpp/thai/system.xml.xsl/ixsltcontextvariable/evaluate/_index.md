---
title: Evaluate()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: ประเมินค่าตัวแปรในระหว่างการทำงานและคืนอ็อบเจ็กต์ที่แสดงค่าของตัวแปร
type: docs
weight: 40
url: /th/system.xml.xsl/ixsltcontextvariable/evaluate/
---
## IXsltContextVariable::Evaluate(SharedPtr\<XsltContext\>) เมธอด


Evaluates the variable at runtime and returns an object that represents the value of the variable.

```cpp
virtual SharedPtr<Object> System::Xml::Xsl::IXsltContextVariable::Evaluate(SharedPtr<XsltContext> xsltContext)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xsltContext | [SharedPtr](../../../system/sharedptr/)\<[XsltContext](../../xsltcontext/)\> | อ็อบเจ็กต์ [XsltContext](../../xsltcontext/) ที่แสดงถึงบริบทการทำงานของตัวแปร. |

### ค่าที่ส่งคืน

อ็อบเจ็กต์ [Object](../../../system/object/) ที่แสดงถึงค่าของตัวแปร. ประเภทค่าที่อาจส่งกลับได้รวมถึง number, string, [Boolean](../../../system/boolean/), document fragment, หรือ node set.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Object](../../../system/object/)
* คลาส [XsltContext](../../xsltcontext/)
* คลาส [IXsltContextVariable](../)
* เนมสเปซ [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)