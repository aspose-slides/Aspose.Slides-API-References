---
title: ConfigureAwait()
second_title: Aspose.Slides สำหรับอ้างอิง API C++
description: กำหนดวิธีการทำงานของ await บนผลลัพธ์งานนี้เกี่ยวกับการจับบริบท
type: docs
weight: 27
url: /th/system.threading.tasks/resulttask/configureawait/
---
## ResultTask::ConfigureAwait(bool) const เมธอด

กำหนดวิธีการทำงานของ await บนผลลัพธ์งานนี้เกี่ยวกับการจับบริบท

```cpp
Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T> System::Threading::Tasks::ResultTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | ว่าควรดำเนินการต่อบนบริบทที่จับไว้หรือไม่ |

### ค่ารีเทิร์น

Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T> Awaitable ที่กำหนดค่าแล้วสำหรับผลลัพธ์

## หมายเหตุ

ซึ่งทำให้สามารถควบคุมการไหลของบริบทอย่างละเอียดสำหรับรูปแบบ async/await

## ดูเพิ่มเติม

* คลาส [ConfiguredResultTaskAwaitable](../../../system.runtime.compilerservices/configuredresulttaskawaitable/)
* คลาส [ResultTask](../)
* เนมสเปซ [System::Threading::Tasks](../../)
* ไลบรารี [Aspose.Slides](../../../)