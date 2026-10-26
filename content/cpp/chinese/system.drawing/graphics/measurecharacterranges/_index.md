---
title: MeasureCharacterRanges()
second_title: Aspose.Slides for C++ API 参考
description: 返回一个区域数组，每个区域限定了指定字符串中的字符位置。
type: docs
weight: 508
url: /zh/system.drawing/graphics/measurecharacterranges/
---
## Graphics::MeasureCharacterRanges(const System::String\&, const SharedPtr\<Font\>\&, RectangleF, const SharedPtr\<StringFormat\>\&) 方法

返回一个区域数组，每个区域限定了指定字符串中的字符位置。

```cpp
ArrayPtr<SharedPtr<Region>> System::Drawing::Graphics::MeasureCharacterRanges(const System::String &text, const SharedPtr<Font> &font, RectangleF layoutRect, const SharedPtr<StringFormat> &stringFormat)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | const [System::String](../../../system/string/)\& | 要测量的字符串 |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | 在测量字符串期间使用的字体 |
| layoutRect | [RectangleF](../../rectanglef/) | 在测量字符串期间使用的布局矩形 |
| stringFormat | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\>\& | 字符串格式，包含要测量的字符范围 |

## 另见

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [Region](../../region/)
* 类 [String](../../../system/string/)
* 类 [Font](../../font/)
* 类 [RectangleF](../../rectanglef/)
* 类 [StringFormat](../../stringformat/)
* 类 [Graphics](../)
* 命名空间 [System::Drawing](../../)
* 库 [Aspose.Slides](../../../)