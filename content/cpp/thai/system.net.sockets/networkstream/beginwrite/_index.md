---
title: BeginWrite()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เริ่มต้นการดำเนินการเขียนแบบอะซิงโครนัส
type: docs
weight: 274
url: /th/system.net.sockets/networkstream/beginwrite/
---
## NetworkStream::BeginWrite(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) เมธอด

เริ่มต้นการเขียนแบบอะซิงโครนัส

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::NetworkStream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, AsyncCallback callback, System::SharedPtr<Object> state) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | บัฟเฟอร์ที่มีข้อมูลที่จะเขียน |
| offset | **int32_t** | ออฟเซตเป็นจำนวนไบต์ในอาเรย์ที่ระบุ |
| size | **int32_t** | จำนวนไบต์ที่จะเขียน |
| callback | [AsyncCallback](../../../system/asynccallback/) | คอลแบ็กที่จะถูกเรียกเมื่อการดำเนินการเสร็จสิ้น |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | ข้อมูลที่ผู้ใช้จัดหาเพื่อระบุการเขียนแบบอะซิงโครนัสแต่ละรายการอย่างไม่ซ้ำกัน |

### Return Value

อ็อบเจกต์ [IAsyncResult](../../../system/iasyncresult/) ที่แสดงการดำเนินการเขียนแบบอะซิงโครนัสที่เริ่มต้น

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Object](../../../system/object/)
* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)