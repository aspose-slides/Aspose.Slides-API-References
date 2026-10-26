---
title: QueueUserWorkItem()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: วางรายการงานลงคิวที่มี callback โดยไม่มีพารามิเตอร์
type: docs
weight: 14
url: /th/system.threading/threadpool/queueuserworkitem/
---
## ThreadPool::QueueUserWorkItem(WaitCallback) เมธอด


วางรายการงานลงคิวที่มี callback โดยไม่มีพารามิเตอร์

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | ฟังก์ชัน callback ที่ใช้เป็นงาน |

### ค่าที่ส่งกลับ

จะคืนค่า true เสมอ

## ThreadPool::QueueUserWorkItem(WaitCallback, const System::SharedPtr\<System::Object\>\&) เมธอด


วางรายการงานลงคิวที่มี callback โดยไม่มีพารามิเตอร์

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | ฟังก์ชัน callback ที่ใช้เป็นงาน |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | พารามิเตอร์ของฟังก์ชันงาน |

### ค่าที่ส่งกลับ

จะคืนค่า true เสมอ

## ดูเพิ่มเติม

* การพิมพ์นิยาม [WaitCallback](../../waitcallback/)
* การพิมพ์นิยาม [SharedPtr](../../../system/sharedptr/)
* คลาส [ThreadPool](../)
* คลาส [Object](../../../system/object/)
* เนมสเปซ [System::Threading](../../)
* ไลบรารี [Aspose.Slides](../../../)