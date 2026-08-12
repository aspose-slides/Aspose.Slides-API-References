---
title: ResultValueTask()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: สร้าง ResultValueTask ที่ว่างเปล่าและไม่ได้กำหนดค่า.
type: docs
weight: 1
url: /th/system.threading.tasks/resultvaluetask/resultvaluetask/
---
## ResultValueTask::ResultValueTask() ตัวสร้าง

สร้าง [ResultValueTask](../) ที่ว่างเปล่าและไม่ได้กำหนดค่า.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask()
```

## หมายเหตุ

งานยังไม่เสร็จและไม่มีผลลัพธ์ การพยายามดึงผลลัพธ์จะทำให้เกิดข้อยกเว้น. 

## ResultValueTask::ResultValueTask(const T&) ตัวสร้าง

สร้าง [ResultValueTask](../) ที่เสร็จสมบูรณ์พร้อมผลลัพธ์ที่ระบุ.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const T &result)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| result | const T\& | ค่า result ที่จะใส่ในงานที่เสร็จสมบูรณ์. |

## หมายเหตุ

นี่จะสร้างงานที่เสร็จสมบูรณ์อย่างสำเร็จและส่งคืนค่าโดยทันที. 

## ResultValueTask::ResultValueTask(const RTaskPtr\<T\>\&) ตัวสร้าง

สร้าง [ResultValueTask](../) จาก shared pointer ของ ResultTask<T>.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const RTaskPtr<T> &task)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| task | const [RTaskPtr](../../../system/rtaskptr/)\<T\>\& | งานที่ห่อหุ้ม สามารถเป็น null สำหรับงานว่าง. |

## หมายเหตุ

[ResultValueTask](../) จะเป็นตัวแทนของสถานะและผลลัพธ์ของงานที่ให้มา. 

## ดูเพิ่มเติม

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* คลาส [ResultValueTask](../)
* เนมสเปซ [System::Threading::Tasks](../../)
* ไลบรารี [Aspose.Slides](../../../)