---
title: GetFontBytes()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ดึงอาร์เรย์ไบต์ที่แสดงข้อมูลฟอนต์สำหรับสไตล์ฟอนต์และข้อมูลฟอนต์ที่ระบุ
type: docs
weight: 131
url: /th/aspose.slides/ifontsmanager/getfontbytes/
---
## IFontsManager::GetFontBytes(System::SharedPtr\<IFontData\>, FontStyleType) method

ดึงอาร์เรย์ไบต์ที่แสดงข้อมูลฟอนต์สำหรับสไตล์ฟอนต์และข้อมูลฟอนต์ที่ระบุ.

```cpp
virtual System::ArrayPtr<uint8_t> Aspose::Slides::IFontsManager::GetFontBytes(System::SharedPtr<IFontData> fontData, FontStyleType fontStyle)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | อ็อบเจ็กต์ข้อมูลฟอนต์ที่มีข้อมูลเกี่ยวกับฟอนต์ [IFontData](../../ifontdata/). |
| fontStyle | [FontStyleType](../../fontstyletype/) | สไตล์ของฟอนต์ที่ต้องการดึงข้อมูล [FontStyleType](../../fontstyletype/). |

### ค่าที่คืนกลับ

อาเรย์ไบต์ที่มีข้อมูลฟอนต์สำหรับสไตล์ฟอนต์ที่ระบุ หากไม่พบข้อมูลฟอนต์หรือสไตล์ จะคืนค่า null.

## หมายเหตุ


```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Retrieve all fonts used in the presentation
System::ArrayPtr<System::SharedPtr<IFontData>> fonts = pres->get_FontsManager()->GetFonts();

// Get the byte array representing the regular style of the first font in the presentation
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fonts[0], FontStyleType::Regular);
```

## ดูเพิ่มเติม

* Enum [FontStyleType](../../fontstyletype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IFontData](../../ifontdata/)
* คลาส [IFontsManager](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)