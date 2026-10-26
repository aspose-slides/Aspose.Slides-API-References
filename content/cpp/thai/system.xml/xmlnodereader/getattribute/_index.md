---
title: GetAttribute()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: คืนค่าของแอตทริบิวต์ที่มีชื่อที่ระบุ
type: docs
weight: 287
url: /th/system.xml/xmlnodereader/getattribute/
---
## XmlNodeReader::GetAttribute(String) เมธอด

คืนค่าของแอตทริบิวต์ที่มีชื่อที่กำหนด

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | ชื่อที่สมบูรณ์ของแอตทริบิวต์ |

### ค่าที่ส่งคืน

ค่าของแอตทริบิวต์ที่ระบุ หากไม่พบแอตทริบิวต์ จะคืนค่า **nullptr**.

## XmlNodeReader::GetAttribute(String, String) เมธอด

คืนค่าของแอตทริบิวต์ที่มีชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุ

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name, String namespaceURI) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | ชื่อท้องถิ่นของแอตทริบิวต์ |
| namespaceURI | [String](../../../system/string/) | URI ของเนมสเปซของแอตทริบิวต์ |

### ค่าที่ส่งคืน

ค่าของแอตทริบิวต์ที่ระบุ หากไม่พบแอตทริบิวต์ จะคืนค่า **nullptr**.

## XmlNodeReader::GetAttribute(int32_t) เมธอด

คืนค่าของแอตทริบิวต์ที่มีดัชนีที่ระบุ

```cpp
String System::Xml::XmlNodeReader::GetAttribute(int32_t attributeIndex) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| attributeIndex | **int32_t** | ดัชนีของแอตทริบิวต์ ดัชนีเริ่มจากศูนย์ (แอตทริบิวต์แรกมีดัชนี 0) |

### ค่าที่ส่งคืน

ค่าของแอตทริบิวต์ที่ระบุ

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XmlNodeReader](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)