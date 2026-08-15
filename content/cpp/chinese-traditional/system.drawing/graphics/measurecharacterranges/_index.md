---
title: MeasureCharacterRanges()
second_title: Aspose.Slides for C++ API 參考
description: 傳回一個區域陣列，每個區域界定指定字串中的字元位置。
type: docs
weight: 508
url: /zh-hant/system.drawing/graphics/measurecharacterranges/
---
## Graphics::MeasureCharacterRanges(const System::String\&, const SharedPtr\<Font\>\&, RectangleF, const SharedPtr\<StringFormat\>\&) method

傳回一個區域陣列，每個區域界定指定字串中的字元位置。

```cpp
ArrayPtr<SharedPtr<Region>> System::Drawing::Graphics::MeasureCharacterRanges(const System::String &text, const SharedPtr<Font> &font, RectangleF layoutRect, const SharedPtr<StringFormat> &stringFormat)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | const [System::String](../../../system/string/)\& | 要測量的字串 |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | 測量字串時使用的字型 |
| layoutRect | [RectangleF](../../rectanglef/) | 測量字串時使用的版面矩形 |
| stringFormat | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\>\& | 字串格式，包含要測量的字元範圍 |

## 參見

* 型別別名 [ArrayPtr](../../../system/arrayptr/)
* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [Region](../../region/)
* 類別 [String](../../../system/string/)
* 類別 [Font](../../font/)
* 類別 [RectangleF](../../rectanglef/)
* 類別 [StringFormat](../../stringformat/)
* 類別 [Graphics](../)
* 命名空間 [System::Drawing](../../)
* 函式庫 [Aspose.Slides](../../../)