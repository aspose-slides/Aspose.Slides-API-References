---
title: Font()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างอินสแตนซ์ใหม่ของคลาส Font ที่แสดงฟอนต์ที่มีอยู่ตามที่ระบุพร้อมสไตล์ฟอนต์ที่ระบุ
type: docs
weight: 1
url: /th/system.drawing/font/font/
---
## Font::Font(const SharedPtr\<Font\>\&, FontStyle) ตัวสร้าง

สร้างอินสแตนซ์ใหม่ของคลาส [Font](../) ที่แสดงฟอนต์ที่มีอยู่ตามที่ระบุพร้อมสไตล์ฟอนต์ที่ระบุ

```cpp
System::Drawing::Font::Font(const SharedPtr<Font> &prototype, FontStyle new_style)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| prototype | const [SharedPtr](../../../system/sharedptr/)\<[Font](../)\>\& | ฟอนต์ที่มีอยู่ซึ่งใช้ในการสร้างฟอนต์ใหม่ |
| new_style | [FontStyle](../../fontstyle/) | สไตล์ฟอนต์ที่จะนำไปใช้กับฟอนต์ใหม่ |

## Font::Font(const SharedPtr\<FontFamily\>\&, float, FontStyle, GraphicsUnit, uint8_t, bool) ตัวสร้าง

สร้างอินสแตนซ์ใหม่ของคลาส [Font](../).

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../fontfamily/)\>\& | ตระกูลฟอนต์ของฟอนต์ใหม่ |
| em_size | **float** | ขนาด em ของฟอนต์ใหม่ในหน่วยที่ระบุโดยพารามิเตอร์ **unit** |
| style | [FontStyle](../../fontstyle/) | สไตล์ของฟอนต์ใหม่ |
| unit | [GraphicsUnit](../../graphicsunit/) | หน่วยการวัดของฟอนต์ใหม่ |
| gdi_charset | **uint8_t** | ชุดอักขระ GDI ที่ใช้สำหรับฟอนต์ใหม่ |
| gdi_vertical_font | **bool** | True หากฟอนต์ใหม่ได้มาจากฟอนต์แนวตั้ง GDI |

## Font::Font(const SharedPtr\<FontFamily\>\&, float, GraphicsUnit) ตัวสร้าง

สร้างอินสแตนซ์ใหม่ของคลาส [Font](../).

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../fontfamily/)\>\& | ตระกูลฟอนต์ของฟอนต์ใหม่ |
| em_size | **float** | ขนาด em ของฟอนต์ใหม่ในหน่วยที่ระบุโดยพารามิเตอร์ **unit** |
| unit | [GraphicsUnit](../../graphicsunit/) | หน่วยการวัดของฟอนต์ใหม่ |

## Font::Font(const String\&, float, FontStyle, GraphicsUnit, uint8_t, bool) ตัวสร้าง

สร้างอินสแตนซ์ใหม่ของคลาส [Font](../).

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| family_name | const [String](../../../system/string/)\& | ชื่อของตระกูลฟอนต์ของฟอนต์ใหม่ |
| em_size | **float** | ขนาด em ของฟอนต์ใหม่ในหน่วยที่ระบุโดยพารามิเตอร์ **unit** |
| style | [FontStyle](../../fontstyle/) | สไตล์ของฟอนต์ใหม่ |
| unit | [GraphicsUnit](../../graphicsunit/) | หน่วยการวัดของฟอนต์ใหม่ |
| gdi_charset | **uint8_t** | ชุดอักขระ GDI ที่ใช้สำหรับฟอนต์ใหม่ |
| gdi_vertical_font | **bool** | True หากฟอนต์ใหม่ได้มาจากฟอนต์แนวตั้ง GDI |

## Font::Font(const String\&, float, GraphicsUnit) ตัวสร้าง

สร้างอินสแตนซ์ใหม่ของคลาส [Font](../).

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| family_name | const [String](../../../system/string/)\& | ชื่อของตระกูลฟอนต์ของฟอนต์ใหม่ |
| em_size | **float** | ขนาด em ของฟอนต์ใหม่ในหน่วยที่ระบุโดยพารามิเตอร์ **unit** |
| unit | [GraphicsUnit](../../graphicsunit/) | หน่วยการวัดของฟอนต์ใหม่ |

## ดูเพิ่มเติม

* Enum [FontStyle](../../fontstyle/)
* Enum [GraphicsUnit](../../graphicsunit/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../)
* Class [FontFamily](../../fontfamily/)
* Class [String](../../../system/string/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)