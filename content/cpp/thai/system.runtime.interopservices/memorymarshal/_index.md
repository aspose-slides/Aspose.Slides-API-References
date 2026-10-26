---
title: MemoryMarshal
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ให้การดำเนินการ memory marshalling. เพื่อความเข้ากันได้กับโค้ดที่แปลเท่านั้น เนื่องจากไม่มีโค้ดที่จัดการบนฝั่ง C++ นี้เป็นประเภทแบบสถิตย์ที่ไม่มีบริการอินสแตนซ์ คุณไม่ควรสร้างอินสแตนซ์ของมันด้วยวิธีใดๆ
type: docs
weight: 27
url: /th/system.runtime.interopservices/memorymarshal/
---
## MemoryMarshal คลาส

ให้การดำเนินการ memory marshalling. เพื่อความเข้ากันได้กับโค้ดที่แปลเท่านั้น เนื่องจากไม่มีโค้ดที่จัดการบนฝั่ง C++ นี้เป็นประเภทแบบสถิตย์ที่ไม่มีบริการอินสแตนซ์ คุณไม่ควรสร้างอินสแตนซ์ของมันด้วยวิธีใดๆ

```cpp
class MemoryMarshal
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| static [Span](../../system/span/)\<**uint8_t**\> [AsBytes](./asbytes/)(const [Span](../../system/span/)\<T\>\&) | แปลง [Span](../../system/span/) ของชนิดพื้นฐานหนึ่งประเภท T ให้เป็น [Span](../../system/span/) ของไบต์. |
| static [Span](../../system/span/)\<TTo\> [Cast](./cast/)(const [Span](../../system/span/)\<TFrom\>\&) | แปลง [Span](../../system/span/) ของชนิดพื้นฐานหนึ่งประเภท TFrom ให้เป็นชนิดพื้นฐานอีกประเภทหนึ่ง TTo. |

## ดูเพิ่มเติม

* เนมสเปซ [System::Runtime::InteropServices](../)
* ไลบรารี [Aspose.Slides](../../)