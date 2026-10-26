---
title: Add()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เพิ่มคำบรรยายปิดรูปแบบ WebVTT ที่ส่วนท้ายของคอลเลกชัน.
type: docs
weight: 27
url: /th/aspose.slides/icaptionscollection/add/
---
## ICaptionsCollection::Add(System::String, System::String) เมธอด

เพิ่มคำบรรยายปิดรูปแบบ WebVTT ที่ส่วนท้ายของคอลเลกชัน.

```cpp
virtual System::SharedPtr<ICaptions> Aspose::Slides::ICaptionsCollection::Add(System::String label, System::String filePath)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | ป้ายกำกับของคำบรรยายปิด. |
| filePath | [System::String](../../../system/string/) | พาธไปยังไฟล์ WebVTT. |

### ค่าที่ส่งคืน

อินสแตนซ์ [ICaptions](../../icaptions/) ที่เพิ่ม.

## ICaptionsCollection::Add(System::String, System::SharedPtr\<System::IO::Stream\>) เมธอด

เพิ่มคำบรรยายปิดรูปแบบ WebVTT ที่ส่วนท้ายของคอลเลกชันจากสตรีม.

```cpp
virtual System::SharedPtr<ICaptions> Aspose::Slides::ICaptionsCollection::Add(System::String label, System::SharedPtr<System::IO::Stream> stream)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | ป้ายกำกับของคำบรรยายปิด. |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | สตรีมอินพุตที่มีข้อมูลในรูปแบบ WebVTT. |

### ค่าที่ส่งคืน

อินสแตนซ์ [ICaptions](../../icaptions/) ที่เพิ่ม.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICaptions](../../icaptions/)
* Class [String](../../../system/string/)
* Class [ICaptionsCollection](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)