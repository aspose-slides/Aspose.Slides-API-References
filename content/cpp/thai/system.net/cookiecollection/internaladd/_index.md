---
title: InternalAdd()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เพิ่มคุกกี้ที่ระบุลงในคอลเลกชัน.
type: docs
weight: 118
url: /th/system.net/cookiecollection/internaladd/
---
## CookieCollection::InternalAdd(System::SharedPtr\<Cookie\>, bool) เมธอด

เพิ่มคุกกี้ที่ระบุลงในคอลเลกชัน

```cpp
int32_t System::Net::CookieCollection::InternalAdd(System::SharedPtr<Cookie> cookie, bool isStrict)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | คุกกี้ที่ต้องการเพิ่ม |
| isStrict | **bool** | จริงเมื่อคุกกี้ที่ระบุต้องแทนที่คุกกี้เก่า, มิฉะนั้นเป็นเท็จ |

### ค่าที่ส่งกลับ

0 เมื่อคุกกี้ที่ระบุแทนที่คุกกี้เก่า, มิฉะนั้นเป็น 1

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Cookie](../../cookie/)
* คลาส [CookieCollection](../)
* เนมสเปซ [System::Net](../../)
* ไลบรารี [Aspose.Slides](../../../)