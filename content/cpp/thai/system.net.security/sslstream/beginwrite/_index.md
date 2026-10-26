---
title: BeginWrite()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เริ่มการดำเนินการเขียนแบบอะซิงโครนัส.
type: docs
weight: 443
url: /th/system.net.security/sslstream/beginwrite/
---
## SslStream::BeginWrite(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) เมธอด

เริ่มการดำเนินการเขียนแบบอะซิงโครนัส

```cpp
System::SharedPtr<IAsyncResult> System::Net::Security::SslStream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count, AsyncCallback asyncCallback, System::SharedPtr<Object> asyncState) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | อาร์เรย์ของไบต์ที่ใช้เขียนข้อมูลไปยัง |
| offset | **int32_t** | ออฟเซ็ตเป็นไบต์ในอาร์เรย์ที่ระบุ |
| count | **int32_t** | จำนวนไบต์ที่ต้องการเขียน |
| asyncCallback | [AsyncCallback](../../../system/asynccallback/) | คอลแบ็กที่จะถูกเรียกเมื่อการดำเนินการเสร็จสมบูรณ์ |
| asyncState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | ข้อมูลที่ผู้ใช้ให้มาใช้เพื่อระบุเอกลักษณ์ของแต่ละการดำเนินการเขียนแบบอะซิงโครนัส |

### ค่ารีเทิร์น

อ็อบเจกต์ [IAsyncResult](../../../system/iasyncresult/) ที่แสดงถึงการดำเนินการเขียนแบบอะซิงโครนัสที่เริ่มต้น

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* คลาส [IAsyncResult](../../../system/iasyncresult/)
* คลาส [Object](../../../system/object/)
* คลาส [SslStream](../)
* เนมสเปซ [System::Net::Security](../../)
* ไลบรารี [Aspose.Slides](../../../)