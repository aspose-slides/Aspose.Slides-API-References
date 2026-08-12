---
title: QueueUserWorkItem()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เพิ่มงานลงในคิว.
type: docs
weight: 1
url: /th/system.threading/threadpoolimpl/queueuserworkitem/
---
## ThreadPoolImpl::QueueUserWorkItem(WaitCallback, const System::SharedPtr\<System::Object\>\&) เมธอด

เพิ่มงานลงในคิว.

```cpp
bool System::Threading::ThreadPoolImpl::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | ฟังก์ชันคอลแบ็กที่จะเรียกใช้. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | อาร์กิวเมนต์ของฟังก์ชันคอลแบ็ก. |

### ค่าที่ส่งกลับ

จะคืนค่าเป็น true เสมอ.

## ดูเพิ่มเติม

* นิยามประเภท [WaitCallback](../../waitcallback/)
* นิยามประเภท [SharedPtr](../../../system/sharedptr/)
* คลาส [Object](../../../system/object/)
* คลาส [ThreadPoolImpl](../)
* เนมสเปซ [System::Threading](../../)
* ไลบรารี [Aspose.Slides](../../../)