---
title: BeginWrite()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เริ่มต้นการดำเนินการเขียนแบบอะซิงโครนัส
type: docs
weight: 170
url: /th/system.io/stream/beginwrite/
---
## Stream::BeginWrite(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) method


เริ่มต้นการดำเนินการเขียนแบบอะซิงโครนัส

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | บัฟเฟอร์ที่มีข้อมูลที่จะเขียน |
| offset | int | ออฟเซ็ตเริ่มจาก 0 ใน **buffer** ระบุตำแหน่งที่ข้อมูลที่จะเขียนเริ่มต้น |
| count | int | จำนวนไบต์ที่ต้องการเขียน |
| callback | [System::AsyncCallback](../../../system/asynccallback/) | คอลแบ็กที่จะถูกเรียกเมื่อการดำเนินการเสร็จสิ้น |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | ข้อมูลที่ผู้ใช้จัดหาเพื่อระบุตัวการเขียนแบบอะซิงโครนัสแต่ละรายการอย่างเฉพาะเจาะจง |

### ค่าที่คืนกลับ

วัตถุ [IAsyncResult](../../../system/iasyncresult/) ที่แสดงถึงการเขียนแบบอะซิงโครนัสที่เริ่มต้น

## ดูเพิ่มเติม

* ชนิดนิยาม [SharedPtr](../../../system/sharedptr/)
* ชนิดนิยาม [ArrayPtr](../../../system/arrayptr/)
* ชนิดนิยาม [AsyncCallback](../../../system/asynccallback/)
* คลาส [IAsyncResult](../../../system/iasyncresult/)
* คลาส [Object](../../../system/object/)
* คลาส [Stream](../)
* เนมสเปซ [System::IO](../../)
* ไลบรารี [Aspose.Slides](../../../)