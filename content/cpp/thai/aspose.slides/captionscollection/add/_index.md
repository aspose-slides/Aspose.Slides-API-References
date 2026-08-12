---
title: Add()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เพิ่มคำบรรยายปิดแบบ WebVTT ไปยังส่วนท้ายของคอลเลกชัน.
type: docs
weight: 27
url: /th/aspose.slides/captionscollection/add/
---
## CaptionsCollection::Add(System::String, System::String) เมธอด

เพิ่มคำบรรยายปิดแบบ WebVTT ไปยังส่วนท้ายของคอลเลกชัน

```cpp
System::SharedPtr<ICaptions> Aspose::Slides::CaptionsCollection::Add(System::String label, System::String filePath) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | ป้ายกำกับของคำบรรยายปิด. |
| filePath | [System::String](../../../system/string/) | พาธไปยังไฟล์ WebVTT. |

### ค่าที่คืนกลับ

อินสแตนซ์ [ICaptions](../../icaptions/) ที่เพิ่มแล้ว.

## CaptionsCollection::Add(System::String, System::SharedPtr\<System::IO::Stream\>) เมธอด

เพิ่มคำบรรยายปิดแบบ WebVTT ไปยังส่วนท้ายของคอลเลกชันจากสตรีม

```cpp
System::SharedPtr<ICaptions> Aspose::Slides::CaptionsCollection::Add(System::String label, System::SharedPtr<System::IO::Stream> stream) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | ป้ายกำกับของคำบรรยายปิด. |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | สตรีมอินพุตที่มีข้อมูลในรูปแบบ WebVTT. |

### ค่าที่คืนกลับ

อินสแตนซ์ [ICaptions](../../icaptions/) ที่เพิ่มแล้ว.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICaptions](../../icaptions/)
* Class [String](../../../system/string/)
* Class [CaptionsCollection](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)