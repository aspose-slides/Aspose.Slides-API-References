---
title: DrawString()
second_title: Aspose.Slides for C++ API 參考文件
description: 在指定位置使用指定的字型和畫筆繪製指定的字串。
type: docs
weight: 365
url: /zh-hant/system.drawing/graphics/drawstring/
---
## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, PointF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) 方法

在指定位置使用指定的字型和畫筆繪製指定的字串。

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, PointF topLeft, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | 要繪製的字串 |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | 要使用的字型 |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | 用於繪製的 [Brush](../../brush/) 物件 |
| topLeft | [PointF](../../pointf/) | 指定已繪製字串的左上角位置 |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | 指定字串的格式 |

## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, RectangleF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) 方法

在指定的矩形內使用指定的字型和畫筆繪製指定的字串。

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, RectangleF layoutRectangle, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | 要繪製的字串 |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | 要使用的字型 |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | 用於繪製的 [Brush](../../brush/) 物件 |
| layoutRectangle | [RectangleF](../../rectanglef/) | 指定繪製字串的矩形 |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | 指定字串的格式 |

## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, float, float, const System::SharedPtr\<System::Drawing::StringFormat\>\&) 方法

在指定位置使用指定的字型和畫筆繪製指定的字串。

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, float x, float y, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | 要繪製的字串 |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | 要使用的字型 |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | 用於繪製的 [Brush](../../brush/) 物件 |
| x | **float** | 已繪製字串左上角位置的 X 座標 |
| y | **float** | 已繪製字串左上角位置的 Y 座標 |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | 指定字串的格式 |

## 參見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [String](../../../system/string/)
* 類別 [Font](../../font/)
* 類別 [Brush](../../brush/)
* 類別 [PointF](../../pointf/)
* 類別 [StringFormat](../../stringformat/)
* 類別 [Graphics](../)
* 類別 [RectangleF](../../rectanglef/)
* 命名空間 [System::Drawing](../../)
* 函式庫 [Aspose.Slides](../../../)