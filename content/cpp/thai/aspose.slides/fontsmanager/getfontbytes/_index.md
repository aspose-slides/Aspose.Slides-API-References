---
title: GetFontBytes()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: ดึงอาเรย์ไบต์ที่เป็นตัวแทนของข้อมูลฟอนต์สำหรับสไตล์ฟอนต์และข้อมูลฟอนต์ที่ระบุ
type: docs
weight: 131
url: /th/aspose.slides/fontsmanager/getfontbytes/
---
## FontsManager::GetFontBytes(System::SharedPtr\<Aspose::Slides::IFontData\>, Aspose::Slides::FontStyleType) เมธอด

ดึงอาเรย์ไบต์ที่เป็นตัวแทนของข้อมูลฟอนต์สำหรับสไตล์ฟอนต์และข้อมูลฟอนต์ที่ระบุ

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::FontsManager::GetFontBytes(System::SharedPtr<Aspose::Slides::IFontData> fontData, Aspose::Slides::FontStyleType fontStyle) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontData](../../ifontdata/)\> | อ็อบเจ็กต์ข้อมูลฟอนต์ที่ประกอบด้วยข้อมูลเกี่ยวกับฟอนต์ [IFontData](../../ifontdata/). |
| fontStyle | [Aspose::Slides::FontStyleType](../../fontstyletype/) | สไตล์ของฟอนต์ที่ต้องการดึงข้อมูล [FontStyleType](../../fontstyletype/). |

### ค่าที่ส่งกลับ

อาเรย์ไบต์ที่ประกอบด้วยข้อมูลฟอนต์สำหรับสไตล์ฟอนต์ที่ระบุ หากไม่พบข้อมูลฟอนต์หรือสไตล์จะคืนค่า null.
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
* Class [IFontData](../../ifontdata/)
* Class [FontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)