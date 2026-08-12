---
title: ResolveUri()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แปลง URI แบบเต็มจาก URI ฐานและ URI ที่สัมพันธ์กัน
type: docs
weight: 66
url: /th/system.xml/xmlurlresolver/resolveuri/
---
## XmlUrlResolver::ResolveUri(SharedPtr\<Uri\>, String) เมธอด


ทำการแปลง URI แบบเต็มจาก URI ฐานและ URI ที่สัมพันธ์กัน.

```cpp
SharedPtr<Uri> System::Xml::XmlUrlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI ฐานที่ใช้เพื่อแปลง URI ที่สัมพันธ์กัน |
| relativeUri | [String](../../../system/string/) | URI ที่ต้องการแปลง URI สามารถเป็นแบบเต็มหรือแบบสัมพันธ์ หากเป็นแบบเต็ม ค่านี้จะทับค่า **baseUri** หากเป็นแบบสัมพันธ์ จะทำการรวมกับ **baseUri** เพื่อสร้าง URI แบบเต็ม |

### ค่าที่คืนกลับ

URI แบบเต็ม หรือ **nullptr** หากไม่สามารถแปลง URI ที่สัมพันธ์กันได้

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Uri](../../../system/uri/)
* คลาส [String](../../../system/string/)
* คลาส [XmlUrlResolver](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)