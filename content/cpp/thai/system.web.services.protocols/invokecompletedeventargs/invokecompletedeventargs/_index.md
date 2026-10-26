---
title: InvokeCompletedEventArgs()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างอินสแตนซ์ใหม่.
type: docs
weight: 14
url: /th/system.web.services.protocols/invokecompletedeventargs/invokecompletedeventargs/
---
## InvokeCompletedEventArgs::InvokeCompletedEventArgs(Exception, bool, System::SharedPtr\<Object\>, System::ArrayPtr\<System::SharedPtr\<Object\>\>) ตัวสร้าง

สร้างอ็อบเจ็กต์ใหม่

```cpp
System::Web::Services::Protocols::InvokeCompletedEventArgs::InvokeCompletedEventArgs(Exception error, bool cancelled, System::SharedPtr<Object> userState, System::ArrayPtr<System::SharedPtr<Object>> results)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| error | [Exception](../../../system/exception/) | ข้อผิดพลาดใด ๆ ที่เกิดขึ้นระหว่างการดำเนินการแบบอะซิงโครนัส |
| cancelled | **bool** | ค่าที่บ่งบอกว่าการดำเนินการแบบอะซิงโครนัสถูกยกเลิกหรือไม่ |
| userState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | อ็อบเจ็กต์สถานะที่ผู้ใช้ส่งมาซึ่งเป็นแบบไม่บังคับส่งให้กับเมธอด [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../../system.componentmodel/backgroundworker/runworkerasync/)([System.Object](../../../system/object/)) |
| results | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | คอลเลกชันของผลลัพธ์การดำเนินการแบบอะซิงโครนัส |

## ดูเพิ่มเติม

* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [Object](../../../system/object/)
* คลาส [InvokeCompletedEventArgs](../)
* เนมสเปซ [System::Web::Services::Protocols](../../)
* ไลบรารี [Aspose.Slides](../../../)