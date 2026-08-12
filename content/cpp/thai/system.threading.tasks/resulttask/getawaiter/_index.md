---
title: GetAwaiter()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: รับ awaiter สำหรับ result task นี้เพื่อใช้กับ Await.
type: docs
weight: 53
url: /th/system.threading.tasks/resulttask/getawaiter/
---
## ResultTask::GetAwaiter() const วิธีการ

รับอ็อบเจ็กต์ awaiter สำหรับผลลัพธ์นี้เพื่อใช้กับ Await.

```cpp
Runtime::CompilerServices::ResultTaskAwaiter<T> System::Threading::Tasks::ResultTask<T>::GetAwaiter() const
```

### Return Value

Runtime::CompilerServices::ResultTaskAwaiter<T> อินสแตนซ์ awaiter ที่ส่งคืนผลลัพธ์
## Remarks

เมื่อทำการ await แล้ว coroutine จะทำงานต่อเมื่อค่าผลลัพธ์พร้อมใช้งาน

## See Also

* คลาส [ResultTaskAwaiter](../../../system.runtime.compilerservices/resulttaskawaiter/)
* คลาส [ResultTask](../)
* เนมสเปซ [System::Threading::Tasks](../../)
* ไลบรารี [Aspose.Slides](../../../)