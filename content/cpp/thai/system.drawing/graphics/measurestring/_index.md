---
title: MeasureString()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ส่งคืนขนาดของสตริงที่ระบุเมื่อวาดด้วยฟอนต์ที่ระบุในรูปแบบที่ระบุ
type: docs
weight: 521
url: /th/system.drawing/graphics/measurestring/
---
## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, PointF const\&, System::SharedPtr\<StringFormat\> const\&) const เมธอด

ส่งคืนขนาดของสตริงที่ระบุเมื่อวาดด้วยฟอนต์ที่ระบุในรูปแบบที่ระบุ

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, PointF const &origin=PointF(0, 0), System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | สตริงที่จะคำนวณขนาด |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | ฟอนต์ที่ใช้วาดสตริง |
| origin | [PointF](../../pointf/) const\& | ระบุตำแหน่งของมุมบนซ้ายของสตริง |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | ระบุรูปแบบสตริง |

### Return Value

อ็อบเจกต์ [SizeF](../../sizef/) ที่แสดงขนาดของสตริงในหน่วยการวัดที่ระบุโดยคุณสมบัติ PageUnit ของอ็อบเจกต์ Graphics ปัจจุบัน

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, int, System::SharedPtr\<StringFormat\> const\&) const เมธอด

ส่งคืนขนาดของสตริงที่ระบุเมื่อวาดด้วยฟอนต์ที่ระบุในรูปแบบที่ระบุ

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, int width, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | สตริงที่จะคำนวณขนาด |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | ฟอนต์ที่ใช้วาดสตริง |
| width | int | ความกว้างสูงสุดของสตริง |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | ระบุรูปแบบสตริง |

### Return Value

อ็อบเจกต์ [SizeF](../../sizef/) ที่แสดงขนาดของสตริงในหน่วยการวัดที่ระบุโดยคุณสมบัติ PageUnit ของอ็อบเจกต์ Graphics ปัจจุบัน

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, SizeF const\&, System::SharedPtr\<StringFormat\> const\&, int\&, int\&) const เมธอด

ยังไม่ได้ทำการใช้งาน

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat, int &charactersFitted, int &linesFilled) const
```

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, SizeF const\&, System::SharedPtr\<StringFormat\> const\&) const เมธอด

ส่งคืนขนาดของสตริงที่ระบุเมื่อวาดด้วยฟอนต์ที่ระบุในรูปแบบที่ระบุ

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | สตริงที่จะคำนวณขนาด |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | ฟอนต์ที่ใช้วาดสตริง |
| layoutArea | [SizeF](../../sizef/) const\& | พื้นที่จัดวางสูงสุดของสตริง |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | ระบุรูปแบบสตริง |

### Return Value

อ็อบเจกต์ [SizeF](../../sizef/) ที่แสดงขนาดของสตริงในหน่วยการวัดที่ระบุโดยคุณสมบัติ PageUnit ของอ็อบเจกต์ Graphics ปัจจุบัน

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [SizeF](../../sizef/)
* คลาส [String](../../../system/string/)
* คลาส [Font](../../font/)
* คลาส [PointF](../../pointf/)
* คลาส [StringFormat](../../stringformat/)
* คลาส [Graphics](../)
* เนมส페스 [System::Drawing](../../)
* ไลบรารี [Aspose.Slides](../../../)