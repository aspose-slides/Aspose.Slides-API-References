---
title: FoundResult()
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: เมธอด callback ที่รับข้อมูลเกี่ยวกับข้อความที่พบ.
type: docs
weight: 1
url: /th/aspose.slides/ifindresultcallback/foundresult/
---
## IFindResultCallback::FoundResult(System::SharedPtr\<ITextFrame\>, System::String, System::String, int32_t) เมธอด

เมธอด callback ที่รับข้อมูลเกี่ยวกับข้อความที่พบ.

```cpp
virtual void Aspose::Slides::IFindResultCallback::FoundResult(System::SharedPtr<ITextFrame> textFrame, System::String sourceText, System::String foundText, int32_t textPosition)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| textFrame | [System::SharedPtr](../../../system/sharedptr/)\<[ITextFrame](../../itextframe/)\> | [ITextFrame](../../itextframe/) ที่ข้อความถูกพบ. |
| sourceText | [System::String](../../../system/string/) | ข้อความต้นฉบับที่ข้อความถูกพบ. |
| foundText | [System::String](../../../system/string/) | ข้อความที่พบ. |
| textPosition | **int32_t** | ตำแหน่งของข้อความที่พบ. |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ITextFrame](../../itextframe/)
* คลาส [String](../../../system/string/)
* คลาส [IFindResultCallback](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)