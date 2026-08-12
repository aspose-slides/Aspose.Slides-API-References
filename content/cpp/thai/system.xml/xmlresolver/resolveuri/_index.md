---
title: ResolveUri()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เมื่อทำการ override ในคลาสที่สืบทอด จะทำการแปลง URI ให้เป็นแบบสมบูรณ์จาก base URI และ relative URI.
type: docs
weight: 27
url: /th/system.xml/xmlresolver/resolveuri/
---
## XmlResolver::ResolveUri(SharedPtr\<Uri\>, String) เมธอด

เมื่อทำการ override ในคลาสที่สืบทอด ทำการแปลง URI ให้เป็นแบบสมบูรณ์จาก base URI และ relative URI.

```cpp
virtual SharedPtr<Uri> System::Xml::XmlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI base ที่ใช้ในการ resolve relative URI. |
| relativeUri | [String](../../../system/string/) | URI ที่ต้อง resolve. URI สามารถเป็นแบบ absolute หรือ relative. หากเป็น absolute ค่าดังกล่าวจะทำหน้าที่แทนค่า **baseUri**. หากเป็น relative จะทำการรวมกับ **baseUri** เพื่อสร้าง URI ที่เป็น absolute. |

### ค่าที่คืน

URI ที่เป็น absolute หรือ **nullptr** หาก relative URI ไม่สามารถ resolve ได้.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [XmlResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)