---
title: ResolveUri()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แก้ไข URI ที่เป็นแบบสมบูรณ์จาก base URI และ relative URI
type: docs
weight: 40
url: /th/system.xml.resolvers/xmlpreloadedresolver/resolveuri/
---
## XmlPreloadedResolver::ResolveUri(SharedPtr\<Uri\>, String) method

แก้ไข URI ที่เป็นแบบสมบูรณ์จาก base URI และ relative URI

```cpp
SharedPtr<Uri> System::Xml::Resolvers::XmlPreloadedResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Base URI ที่ใช้ในการแก้ไข relative URI |
| relativeUri | [String](../../../system/string/) | URI ที่จะทำการแก้ไข URI นี้อาจเป็นแบบสมบูรณ์หรือแบบ relative หากเป็นแบบสมบูรณ์ ค่าจะทดแทนค่า **baseUri** หากเป็นแบบ relative จะรวมกับ **baseUri** เพื่อสร้าง URI ที่สมบูรณ์ |

## ค่าที่คืนกลับ

[Uri](../../../system/uri/) ที่แสดงถึง URI สมบูรณ์ หรือ **nullptr** หากไม่สามารถแก้ไข relative URI ได้

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Uri](../../../system/uri/)
* คลาส [String](../../../system/string/)
* คลาส [XmlPreloadedResolver](../)
* เนมสเปซ [System::Xml::Resolvers](../../)
* ไลบรารี [Aspose.Slides](../../../)