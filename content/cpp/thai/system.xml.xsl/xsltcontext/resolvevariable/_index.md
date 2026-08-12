---
title: ResolveVariable()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เมื่อทำการ override ในคลาสที่สืบทอด แก้ไขการอ้างอิงตัวแปรและคืนค่า IXsltContextVariable ที่เป็นตัวแทนของตัวแปร
type: docs
weight: 14
url: /th/system.xml.xsl/xsltcontext/resolvevariable/
---
## XsltContext::ResolveVariable(String, String) เมธอด

เมื่อทำการ override ในคลาสที่สืบทอด แก้ไขการอ้างอิงตัวแปรและคืนค่า [IXsltContextVariable](../../ixsltcontextvariable/) ที่เป็นตัวแทนของตัวแปรนั้น

```cpp
virtual SharedPtr<IXsltContextVariable> System::Xml::Xsl::XsltContext::ResolveVariable(String prefix, String name)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | คำนำหน้าของตัวแปรตามที่ปรากฏในนิพจน์ [XPath](../../../system.xml.xpath/) |
| name | [String](../../../system/string/) | ชื่อของตัวแปร |

### ค่าที่คืน

[IXsltContextVariable](../../ixsltcontextvariable/) ที่เป็นตัวแทนของตัวแปรในเวลารัน

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IXsltContextVariable](../../ixsltcontextvariable/)
* คลาส [String](../../../system/string/)
* คลาส [XsltContext](../)
* เนมสเปซ [System::Xml::Xsl](../../)
* ไลบรารี [Aspose.Slides](../../../)