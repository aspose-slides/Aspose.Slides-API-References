---
title: Handle()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: เรียกใช้ฟังก์ชันตัวจัดการสำหรับแต่ละข้อยกเว้นภายในและโยนข้อยกเว้นที่ไม่ได้รับการจัดการใหม่
type: docs
weight: 66
url: /th/system/details_aggregateexception/handle/
---
## รายละเอียด_AggregateException::Handle(const Func\<Exception, bool\>\&) method


เรียกใช้ฟังก์ชันตัวจัดการสำหรับแต่ละข้อยกเว้นภายในและโยนข้อยกเว้นที่ไม่ได้รับการจัดการใหม่

```cpp
void System::Details_AggregateException::Handle(const Func<Exception, bool> &predicate)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| predicate | const [Func](../../func/)\<[Exception](../../exception/), **bool**\>\& | ฟังก์ชันที่รับ Exception และคืนค่า true หากได้รับการจัดการ |
## หมายเหตุ



หากข้อยกเว้นทั้งหมดได้รับการจัดการ เมธอดจะคืนค่าโดยปกติ; หากไม่เช่นนั้น จะขว้าง AggregateException ใหม่ที่มีข้อยกเว้นที่ไม่ได้รับการจัดการ

## ดูเพิ่มเติม

* Typedef [Exception](../../exception/)
* คลาส [Func](../../func/)
* คลาส [Details_AggregateException](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)