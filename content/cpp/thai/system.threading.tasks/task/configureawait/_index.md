---
title: ConfigureAwait()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: กำหนดวิธีที่การ await บนงานนี้ควรทำงานเกี่ยวกับการจับบริบท
type: docs
weight: 144
url: /th/system.threading.tasks/task/configureawait/
---
## Task::ConfigureAwait(bool) const เมธอด

กำหนดวิธีที่การ await บนงานนี้ควรทำงานเกี่ยวกับการจับบริบท

```cpp
Runtime::CompilerServices::ConfiguredTaskAwaitable System::Threading::Tasks::Task::ConfigureAwait(bool continueOnCapturedContext) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | ว่าควรดำเนินการต่อในบริบทที่จับได้หรือไม่ |

### ค่าที่ส่งคืน

[Runtime::CompilerServices::ConfiguredTaskAwaitable](../../../system.runtime.compilerservices/configuredtaskawaitable/) วัตถุ await ที่กำหนดค่าไว้

## ดูเพิ่มเติม

* คลาส [ConfiguredTaskAwaitable](../../../system.runtime.compilerservices/configuredtaskawaitable/)
* คลาส [Task](../)
* เนมสเปซ [System::Threading::Tasks](../../)
* ไลบรารี [Aspose.Slides](../../../)