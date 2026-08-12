---
title: ResolveUri()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: แก้ไข URI สมบูรณ์จาก URI ฐานและ URI สัมพัทธ์โดยการเรียก ResolveUri บน XmlResolver ที่อยู่ภายใต้
type: docs
weight: 40
url: /th/system.xml/xmlsecureresolver/resolveuri/
---
## XmlSecureResolver::ResolveUri(SharedPtr\<Uri\>, String) เมธอด

แก้ไข URI สมบูรณ์จาก URI ฐานและ URI สัมพัทธ์โดยเรียก **ResolveUri** บน [XmlResolver](../../xmlresolver/) ที่อยู่ภายใต้

```cpp
SharedPtr<Uri> System::Xml::XmlSecureResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI ฐานที่ใช้เพื่อแก้ไข URI สัมพัทธ์ |
| relativeUri | [String](../../../system/string/) | URI ที่จะทำการแก้ไข. URI สามารถเป็นแบบสมบูรณ์หรือสัมพัทธ์. หากเป็นแบบสมบูรณ์ ค่าดังกล่าวจะทดแทนค่า **baseUri** อย่างมีประสิทธิภาพ. หากเป็นแบบสัมพัทธ์ จะผสานกับ **baseUri** เพื่อสร้าง URI แบบสมบูณ์ |

### ค่าที่ส่งกลับ

URI สมบูรณ์หรือ **nullptr** หากไม่สามารถแก้ไข URI สัมพัทธ์ได้ (ส่งกลับโดยการเรียก **ResolveUri** บน [XmlResolver](../../xmlresolver/) ที่อยู่ภายใต้)

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Uri](../../../system/uri/)
* คลาส [String](../../../system/string/)
* คลาส [XmlSecureResolver](../)
* เนมสเปซ [System::Xml](../../)
* Library [Aspose.Slides](../../../)