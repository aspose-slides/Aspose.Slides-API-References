---
title: DrawString()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: วาดสตริงที่ระบุที่ตำแหน่งที่กำหนดโดยใช้แบบอักษรและแปรงที่ระบุ.
type: docs
weight: 365
url: /th/system.drawing/graphics/drawstring/
---
## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, PointF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) เมธอด

วาดสตริงที่ระบุที่ตำแหน่งที่กำหนดโดยใช้แบบอักษรและแปรงที่ระบุ

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, PointF topLeft, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | สตริงที่จะวาด |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | แบบอักษรที่จะใช้ |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | วัตถุ [Brush](../../brush/) ที่ใช้สำหรับการวาด |
| topLeft | [PointF](../../pointf/) | ระบุพิกัดของมุมบนซ้ายของสตริงที่วาด |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | ระบุรูปแบบของสตริง |

## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, RectangleF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) เมธอด

วาดสตริงที่ระบุในสี่เหลี่ยมที่กำหนดโดยใช้แบบอักษรและแปรงที่ระบุ

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, RectangleF layoutRectangle, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | สตริงที่จะวาด |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | แบบอักษรที่จะใช้ |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | วัตถุ [Brush](../../brush/) ที่ใช้สำหรับการวาด |
| layoutRectangle | [RectangleF](../../rectanglef/) | ระบุสี่เหลี่ยมที่ใช้วาดสตริง |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | ระบุรูปแบบของสตริง |

## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, float, float, const System::SharedPtr\<System::Drawing::StringFormat\>\&) เมธอด

วาดสตริงที่ระบุที่ตำแหน่งที่กำหนดโดยใช้แบบอักษรและแปรงที่ระบุ

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, float x, float y, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | สตริงที่จะวาด |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | แบบอักษรที่จะใช้ |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | วัตถุ [Brush](../../brush/) ที่ใช้สำหรับการวาด |
| x | **float** | พิกัด X ของตำแหน่งมุมบนซ้ายของสตริงที่วาด |
| y | **float** | พิกัด Y ของตำแหน่งมุมบนซ้ายของสตริงที่วาด |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | ระบุรูปแบบของสตริง |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [String](../../../system/string/)
* คลาส [Font](../../font/)
* คลาส [Brush](../../brush/)
* คลาส [PointF](../../pointf/)
* คลาส [StringFormat](../../stringformat/)
* คลาส [Graphics](../)
* คลาส [RectangleF](../../rectanglef/)
* เนมสเปซ [System::Drawing](../../)
* ไลบรารี [Aspose.Slides](../../../)