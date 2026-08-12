---
title: FontFamily()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างอินสแตนซ์ใหม่ของคลาส FontFamily ที่แสดงถึงฟอนต์แฟมิลี่ที่มีชื่อที่ระบุ
type: docs
weight: 1
url: /th/system.drawing/fontfamily/fontfamily/
---
## FontFamily::FontFamily(const String\&) คอนสตรัคเตอร์

สร้างอินสแตนซ์ใหม่ของคลาส [FontFamily](../) ที่แสดงถึงฟอนต์แฟมิลี่ที่มีชื่อที่ระบุ

```cpp
System::Drawing::FontFamily::FontFamily(const String &name)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | ชื่อฟอนต์แฟมิลี่ |

## FontFamily::FontFamily(const String\&, const SharedPtr\<Text::FontCollection\>\&) คอนสตรัคเตอร์

สร้างอินสแตนซ์ใหม่ของ [FontFamily](../) ใน FontCollection ที่ระบุพร้อมชื่อที่ระบุ

```cpp
System::Drawing::FontFamily::FontFamily(const String &name, const SharedPtr<Text::FontCollection> &font_collection)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | ชื่อฟอนต์แฟมิลี่ |
| font_collection | const [SharedPtr](../../../system/sharedptr/)\<[Text::FontCollection](../../../system.drawing.text/fontcollection/)\>\& | FontCollection ที่มีอินสแตนซ์นี้ |

## FontFamily::FontFamily(Text::GenericFontFamilies) คอนสตรัคเตอร์

สร้างอินสแตนซ์ใหม่ของ [FontFamily](../) จากฟอนต์แฟมิลี่ทั่วไปที่ระบุ

```cpp
System::Drawing::FontFamily::FontFamily(Text::GenericFontFamilies generic_family)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| generic_family | [Text::GenericFontFamilies](../../../system.drawing.text/genericfontfamilies/) | ค่า GenericFontFamilies เพื่อสร้าง [FontFamily](../) |

## ดูเพิ่มเติม

* Enum [GenericFontFamilies](../../../system.drawing.text/genericfontfamilies/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [String](../../../system/string/)
* คลาส [FontFamily](../)
* คลาส [FontCollection](../../../system.drawing.text/fontcollection/)
* เนมสเปซ [System::Drawing](../../)
* ไลบรารี [Aspose.Slides](../../../)