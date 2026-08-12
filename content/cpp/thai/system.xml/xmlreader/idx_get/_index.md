---
title: idx_get()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เมื่อถูกโอเวอร์ไรด์ในคลาสที่สืบทอด จะรับค่าของแอตทริบิวต์ด้วยดัชนีที่ระบุ
type: docs
weight: 612
url: /th/system.xml/xmlreader/idx_get/
---
## XmlReader::idx_get(int32_t) เมธอด

เมื่อถูกโอเวอร์ไรด์ในคลาสที่สืบทอด, จะรับค่าของแอตทริบิวต์ด้วยดัชนีที่ระบุ

```cpp
virtual String System::Xml::XmlReader::idx_get(int32_t i)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| i | **int32_t** | ดัชนีของแอตทริบิวต์ |

### ค่าที่คืนกลับ

ค่าของแอตทริบิวต์ที่ระบุ

## XmlReader::idx_get(String) เมธอด

เมื่อถูกโอเวอร์ไรด์ในคลาสที่สืบทอด, จะรับค่าของแอตทริบิวต์ด้วยค่า [XmlReader::get_Name](../get_name/) ที่ระบุ

```cpp
virtual String System::Xml::XmlReader::idx_get(String name)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | ชื่อที่ผ่านการระบุอย่างเต็มของแอตทริบิวต์ |

### ค่าที่คืนกลับ

ค่าของแอตทริบิวต์ที่ระบุ หากไม่พบแอตทริบิวต์จะคืนค่า **nullptr**

## XmlReader::idx_get(String, String) เมธอด

เมื่อถูกโอเวอร์ไรด์ในคลาสที่สืบทอด, จะรับค่าของแอตทริบิวต์ด้วยค่า [XmlReader::get_LocalName](../get_localname/) และ [XmlReader::get_NamespaceURI](../get_namespaceuri/) ที่ระบุ

```cpp
virtual String System::Xml::XmlReader::idx_get(String name, String namespaceURI)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | ชื่อโลคัลของแอตทริบิวต์ |
| namespaceURI | [String](../../../system/string/) | URI ของเนมสเปซของแอตทริบิวต์ |

### ค่าที่คืนกลับ

ค่าของแอตทริบิวต์ที่ระบุ หากไม่พบแอตทริบิวต์จะคืนค่า **nullptr**

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XmlReader](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)