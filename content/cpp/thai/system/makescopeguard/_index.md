---
title: MakeScopeGuard()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: ฟังก์ชันแฟคทอรีที่สร้างอินสแตนซ์ของคลาส ScopedGuard.
type: docs
weight: 2809
url: /th/system/makescopeguard/
---
## ฟังก์ชัน System::MakeScopeGuard(F)


ฟังก์ชันแฟคทอรีที่สร้างอินสแตนซ์ของคลาส ScopedGuard.

```cpp
template<typename F> ScopeGuard<F> System::MakeScopeGuard(F f)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| The | ประเภทของอ็อบเจกต์ฟังก์ชันที่จะถูกเรียกโดยอ็อบเจกต์ ScopedGuard ที่สร้างขึ้น |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| f | F | อ็อบเจกต์ฟังก์ชันที่จะส่งให้กับคอนสตรักเตอร์ของคลาส ScopedGuard. |

### ค่าที่ส่งกลับ

อินสแตนซ์ใหม่ของคลาส ScopedGuard

## ดูเพิ่มเติม

* Struct [ScopeGuard](../scopeguard/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)