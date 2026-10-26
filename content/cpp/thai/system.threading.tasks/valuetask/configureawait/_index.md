---
title: ConfigureAwait()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: กำหนดค่า awaiter สำหรับงานนี้.
type: docs
weight: 79
url: /th/system.threading.tasks/valuetask/configureawait/
---
## ValueTask::ConfigureAwait(bool) const เมธอด

กำหนดค่า awaiter สำหรับงานนี้.

```cpp
Runtime::CompilerServices::ConfiguredValueTaskAwaitable System::Threading::Tasks::ValueTask::ConfigureAwait(bool continueOnCapturedContext) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | true หากต้องการพยายามส่งต่อการทำงานต่อกลับไปยังบริบทเดิมที่จับได้; มิฉะนั้น false. |

### ค่าที่ส่งคืน

ConfiguredValueTaskAwaitable วัตถุที่กำหนดวิธีการทำงานของ awaiter สำหรับงานนี้.

## ดูเพิ่มเติม

* คลาส [ConfiguredValueTaskAwaitable](../../../system.runtime.compilerservices/configuredvaluetaskawaitable/)
* คลาส [ValueTask](../)
* เนมสเปซ [System::Threading::Tasks](../../)
* ไลบรารี [Aspose.Slides](../../../)