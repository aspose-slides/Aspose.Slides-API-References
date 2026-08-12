---
title: Hyperlink()
second_title: Aspose.Slides สำหรับ C++ - เอกสารอ้างอิง API
description: สร้างอินสแตนซ์ของไฮเปอร์ลิงก์.
type: docs
weight: 339
url: /th/aspose.slides/hyperlink/hyperlink/
---
## Hyperlink::Hyperlink(System::String) คอนสตรัคเตอร์

สร้างอินสแตนซ์ของไฮเปอร์ลิงก์.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::String url)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| url | [System::String](../../../system/string/) | [Hyperlink](../) URL. |

## Hyperlink::Hyperlink(System::SharedPtr\<ISlide\>) คอนสตรัคเตอร์

สร้างอินสแตนซ์ของไฮเปอร์ลิงก์ที่ชี้ไปยังสไลด์เฉพาะ. หมายเหตุ: ไฮเปอร์ลิงก์ที่สร้างควรถูกกำหนดให้กับวัตถุจากการนำเสนอเดียวกัน มิฉะนั้นลิงก์จะถูกบันทึกเป็น NoAction.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::SharedPtr<ISlide> slide)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | สไลด์เป้าหมาย. |

## Hyperlink::Hyperlink(System::SharedPtr\<Hyperlink\>, System::String, System::String, bool, bool, bool) คอนสตรัคเตอร์

สร้างอินสแตนซ์ของไฮเปอร์ลิงก์โดยใช้ไฮเปอร์ลิงก์อื่นเป็นแหล่งที่มาและแทนที่คุณสมบัติรอง.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::SharedPtr<Hyperlink> source, System::String targetFrame, System::String tooltip, bool history, bool stopSoundsOnClick, bool highlightClick)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| source | [System::SharedPtr](../../../system/sharedptr/)\<[Hyperlink](../)\> | ไฮเปอร์ลิงก์ต้นทาง |
| targetFrame | [System::String](../../../system/string/) | เฟรมเป้าหมาย |
| tooltip | [System::String](../../../system/string/) | ข้อความคำแนะนำ |
| history | **bool** |  |
| stopSoundsOnClick | **bool** |  |
| highlightClick | **bool** |  |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [String](../../../system/string/)
* คลาส [Hyperlink](../)
* คลาส [ISlide](../../islide/)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)