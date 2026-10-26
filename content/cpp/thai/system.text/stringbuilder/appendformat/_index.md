---
title: AppendFormat()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เพิ่มสตริงที่จัดรูปแบบแล้วลงในตัวสร้าง
type: docs
weight: 131
url: /th/system.text/stringbuilder/appendformat/
---
## StringBuilder::AppendFormat(const String\&, const TArgs\&...) method


เพิ่มสตริงที่จัดรูปแบบแล้วลงในตัวสร้าง

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const String &format, const TArgs &... args)
```


### พารามิเตอร์เทมเพลต

| Parameter | Description |
| --- | --- |
| TArgs | ประเภทของอาร์กิวเมนต์ |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| format | const [String](../../../system/string/)\& | สตริงรูปแบบ |
| args | const TArgs\&... | อาร์กิวเมนต์ที่จะใส่ในตำแหน่งของสตริงรูปแบบ |

### ค่าที่คืน

พอยน์เตอร์นี้

## StringBuilder::AppendFormat(const SharedPtr\<IFormatProvider\>\&, const String\&, const TArgs\&...) method


เพิ่มสตริงที่จัดรูปแบบแล้วลงในตัวสร้าง

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const SharedPtr<IFormatProvider> &fp, const String &format, const TArgs &... args)
```


### พารามิเตอร์เทมเพลต

| Parameter | Description |
| --- | --- |
| TArgs | ประเภทของอาร์กิวเมนต์ |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| fp | const [SharedPtr](../../../system/sharedptr/)\<[IFormatProvider](../../../system/iformatprovider/)\>\& | ผู้ให้บริการรูปแบบ; ถูกละเลย |
| format | const [String](../../../system/string/)\& | สตริงรูปแบบ |
| args | const TArgs\&... | อาร์กิวเมนต์ที่จะใส่ในตำแหน่งของสตริงรูปแบบ |

### ค่าที่คืน

พอยน์เตอร์นี้

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [StringBuilder](../)
* Class [String](../../../system/string/)
* Class [IFormatProvider](../../../system/iformatprovider/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)