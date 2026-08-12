---
title: ReportProgress()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "ทำให้เกิดเหตุการณ์ System::ComponentModel::BackgroundWorker::ProgressChanged."
type: docs
weight: 40
url: /th/system.componentmodel/backgroundworker/reportprogress/
---
## BackgroundWorker::ReportProgress(int) เมธอด

ทำให้เกิดเหตุการณ์ **System::ComponentModel::BackgroundWorker::ProgressChanged**.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| percentProgress | int | เปอร์เซ็นต์จาก 0 ถึง 100 ของการดำเนินงานในพื้นหลังที่เสร็จสมบูรณ์. |

## BackgroundWorker::ReportProgress(int, const System::SharedPtr\<System::Object\>\&) เมธอด

ทำให้เกิดเหตุการณ์ **System::ComponentModel::BackgroundWorker::ProgressChanged** พร้อมอ็อบเจกต์ userState.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress, const System::SharedPtr<System::Object> &userState)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| percentProgress | int | เปอร์เซ็นต์จาก 0 ถึง 100 ของการดำเนินงานในพื้นหลังที่เสร็จสมบูรณ์. |
| userState | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | อ็อบเจกต์สถานะที่ส่งให้ System::ComponentModel::BackgroundWorker::RunWorkerAsync(System::Object). |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [BackgroundWorker](../)
* คลาส [Object](../../../system/object/)
* เนมสเปซ [System::ComponentModel](../../)
* ไลบรารี [Aspose.Slides](../../../)