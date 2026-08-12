---
title: BeginRead()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: เริ่มต้นการดำเนินการอ่านแบบอะซิงโครนัส.
type: docs
weight: 417
url: /th/system.net.security/sslstream/beginread/
---
## SslStream::BeginRead(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) เมธอด

เริ่มต้นการอ่านแบบอะซิงโครนัส

```cpp
System::SharedPtr<IAsyncResult> System::Net::Security::SslStream::BeginRead(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count, AsyncCallback asyncCallback, System::SharedPtr<Object> asyncState) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | อาร์เรย์ของไบต์ที่ใช้สำหรับอ่านข้อมูล |
| offset | **int32_t** | ออฟเซ็ตเป็นไบต์ในอาร์เรย์ที่ระบุ |
| count | **int32_t** | จำนวนไบต์ที่จะอ่าน |
| asyncCallback | [AsyncCallback](../../../system/asynccallback/) | คอลแบ็กที่จะถูกเรียกเมื่อการดำเนินการเสร็จสมบูรณ์ |
| asyncState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | ข้อมูลที่ผู้ใช้ให้มาใช้เพื่อระบุตัวการอ่านแบบอะซิงโครนัสแต่ละรายการอย่างไม่ซ้ำกัน |

### ค่าที่คืน

อ็อบเจกต์ [IAsyncResult](../../../system/iasyncresult/) ที่แสดงถึงการดำเนินการอ่านแบบอะซิงโครนัสที่เริ่มต้น

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* คลาส [IAsyncResult](../../../system/iasyncresult/)
* คลาส [Object](../../../system/object/)
* คลาส [SslStream](../)
* เนมสเปซ [System::Net::Security](../../)
* ไลบรารี [Aspose.Slides](../../../)