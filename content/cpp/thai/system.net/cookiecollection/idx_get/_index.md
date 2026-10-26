---
title: idx_get()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ส่งคืนคุ้กกี้จากคอลเลกชันคุ้กกี้ที่ตำแหน่งที่ระบุ
type: docs
weight: 40
url: /th/system.net/cookiecollection/idx_get/
---
## CookieCollection::idx_get(int32_t) เมธอด

ส่งคืนคุ้กกี้จากคอลเลกชันคุ้กกี้ที่ตำแหน่งที่ระบุ

```cpp
System::SharedPtr<Cookie> System::Net::CookieCollection::idx_get(int32_t index)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีของคุ้กกี้ที่ต้องการส่งคืน |

### ค่าที่ส่งคืน

คุ้กกี้ที่ตำแหน่งที่ระบุ

## CookieCollection::idx_get(String) เมธอด

ส่งคืนคุ้กกี้จากคอลเลกชันคุ้กกี้โดยชื่อที่ระบุ

```cpp
System::SharedPtr<Cookie> System::Net::CookieCollection::idx_get(String name)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | [String](../../../system/string/) | ชื่อของคุ้กกี้ที่ต้องการส่งคืน |

### ค่าที่ส่งคืน

คุ้กกี้จากคอลเลกชันคุ้กกี้โดยชื่อที่ระบุเมื่อพบ, หากไม่พบจะเป็น nullptr

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Cookie](../../cookie/)
* คลาส [CookieCollection](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [System::Net](../../)
* Library [Aspose.Slides](../../../)