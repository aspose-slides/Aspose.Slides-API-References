---
title: ConfigureAwait()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: กำหนดค่า awaiter สำหรับงานนี้.
type: docs
weight: 92
url: /th/system.threading.tasks/resultvaluetask/configureawait/
---
## ResultValueTask::ConfigureAwait(bool) const เมธอด

กำหนดค่า awaiter สำหรับงานนี้.

```cpp
Runtime::CompilerServices::ConfiguredResultValueTaskAwaitable<T> System::Threading::Tasks::ResultValueTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | true หากพยายามส่งต่อการทำงานต่อกลับไปยังบริบทเดิมที่ถูกจับ; มิฉะนั้นเป็น false. |

### ค่าที่ส่งกลับ

ConfiguredResultValueTaskAwaitable<T> ออบเจ็กต์ที่กำหนดวิธีที่ awaiters ทำงานสำหรับงานนี้.

## ดูเพิ่มเติม

* คลาส [ConfiguredResultValueTaskAwaitable](../../../system.runtime.compilerservices/configuredresultvaluetaskawaitable/)
* คลาส [ResultValueTask](../)
* เนมสเปซ [System::Threading::Tasks](../../)
* ไลบรารี [Aspose.Slides](../../../)