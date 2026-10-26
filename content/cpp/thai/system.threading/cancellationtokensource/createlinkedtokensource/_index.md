---
title: CreateLinkedTokenSource()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างแหล่งโทเค็นที่เชื่อมโยงซึ่งจะถูกยกเลิกเมื่อโทเค็นใดโทเค็นหนึ่งที่ให้มาถูกยกเลิก
type: docs
weight: 66
url: /th/system.threading/cancellationtokensource/createlinkedtokensource/
---
## CancellationTokenSource::CreateLinkedTokenSource(const CancellationToken\&, const CancellationToken\&) method

สร้างแหล่งโทเค็นที่เชื่อมโยงซึ่งจะถูกยกเลิกเมื่อโทเค็นใดโทเค็นหนึ่งที่ให้มาถูกยกเลิก

```cpp
static SharedPtr<CancellationTokenSource> System::Threading::CancellationTokenSource::CreateLinkedTokenSource(const CancellationToken &token1, const CancellationToken &token2)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| token1 | const [CancellationToken](../../cancellationtoken/)\& | โทเค็นยกเลิกแรกที่ต้องตรวจสอบ |
| token2 | const [CancellationToken](../../cancellationtoken/)\& | โทเค็นยกเลิกที่สองที่ต้องตรวจสอบ |

### ค่าที่คืนกลับ

แหล่งโทเค็นใหม่ที่จะถูกยกเลิกเมื่อโทเค็นใดโทเค็นหนึ่งของอินพุตถูกยกเลิก

## หมายเหตุ

แหล่งที่ส่งคืนจะยกเลิกทันทีหากโทเค็นอินพุตใดเป็นที่ยกเลิกแล้ว

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [CancellationTokenSource](../)
* คลาส [CancellationToken](../../cancellationtoken/)
* เนมสเปซ [System::Threading](../../)
* Library [Aspose.Slides](../../../)