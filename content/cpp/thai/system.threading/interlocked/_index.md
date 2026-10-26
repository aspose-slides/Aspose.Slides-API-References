---
title: Interlocked
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ให้ API สำหรับการดำเนินการที่ปลอดภัยต่อเธรด นี่คือประเภทสแตติกที่ไม่มีบริการอินสแตนซ์ คุณไม่ควรสร้างอินสแตนซ์ของมันโดยวิธีใด ๆ
type: docs
weight: 131
url: /th/system.threading/interlocked/
---
## คลาส Interlocked

ให้ API สำหรับการดำเนินการที่ปลอดภัยต่อเธรด นี่คือประเภทสแตติกที่ไม่มีบริการอินสแตนซ์ คุณไม่ควรสร้างอินสแตนซ์ของมันโดยวิธีใดๆ

```cpp
class Interlocked
```

## เมธอด

| Method | Description |
| --- | --- |
| static **int32_t** [Add](./add/)(**int32_t**\&, **int32_t**) | เพิ่มค่าแบบอะตอมิก |
| static **int64_t** [Add](./add/)(**int64_t**\&, **int64_t**) | เพิ่มค่าแบบอะตอมิก |
| static std::enable_if\<IsSupportedInt\<T\>, T\>::type [CompareExchange](./compareexchange/)(T\&, T, T) | ทำการเปรียบเทียบและแลกเปลี่ยนค่าในตัวแปร: ตรวจสอบว่าตัวแปรเท่ากับค่าที่กำหนดและเก็บค่าที่ใหม่เฉพาะเมื่อค่าที่เก็บตรงกับที่คาดหวัง |
| static std::enable_if<\!IsSupportedInt\<T\>, T\>::type [CompareExchange](./compareexchange/)(T\&, T, T) | ทำการเปรียบเทียบและแลกเปลี่ยนค่าในตัวแปร: ตรวจสอบว่าตัวแปรเท่ากับค่าที่กำหนดและเก็บค่าที่ใหม่เฉพาะเมื่อค่าที่เก็บตรงกับที่คาดหวัง ยังไม่ได้ทำ |
| static **int32_t** [CompareExchange](./compareexchange/)(**int32_t**\&, **int32_t**, **int32_t**, **bool**\&) | ทำการเปรียบเทียบและแลกเปลี่ยนค่าในตัวแปร: ตรวจสอบว่าตัวแปรเท่ากับค่าที่กำหนดและเก็บค่าที่ใหม่เฉพาะเมื่อค่าที่เก็บตรงกับที่คาดหวัง |
| static **int32_t** [Decrement](./decrement/)(**int32_t**\&) | ลดค่าลงแบบอะตอมิก |
| static **int64_t** [Decrement](./decrement/)(**int64_t**\&) | ลดค่าลงแบบอะตอมิก |
| static std::enable_if\<IsSupportedInt\<T\>, T\>::type [Exchange](./exchange/)(T\&, T) | แลกเปลี่ยนค่าบนตัวแปร: เก็บค่าที่ใหม่และส่งคืนค่าที่ตัวแปรมีอยู่ก่อนการเก็บค่านั้น |
| static std::enable_if<\!IsSupportedInt\<T\>, T\>::type [Exchange](./exchange/)(T\&, T) | แลกเปลี่ยนค่าบนตัวแปร: เก็บค่าที่ใหม่และส่งคืนค่าที่ตัวแปรมีอยู่ก่อนการเก็บค่านั้น ยังไม่ได้ทำ |
| static **int32_t** [ExchangeAdd](./exchangeadd/)(**int32_t**\&, **int32_t**) | เพิ่มค่าแบบอะตอมิกผ่านขั้นตอน exchange-add |
| static **int64_t** [ExchangeAdd](./exchangeadd/)(**int64_t**\&, **int64_t**) | เพิ่มค่าแบบอะตอมิกผ่านขั้นตอน exchange-add |
| static **int32_t** [Increment](./increment/)(**int32_t**\&) | เพิ่มค่าแบบอะตอมิก |
| static **int64_t** [Increment](./increment/)(**int64_t**\&) | เพิ่มค่าแบบอะตอมิก |
| static **int64_t** [Read](./read/)(**int64_t**\&) | ส่งคืนค่าขนาด 64 บิตที่โหลดเป็นการดำเนินการแบบอะตอมิก |

## ดูเพิ่มเติม

* เนมสเปซ [System::Threading](../)
* ไลบรารี [Aspose.Slides](../../)