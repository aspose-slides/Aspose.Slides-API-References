---
title: MeasureCharacterRanges()
second_title: Aspose.Slides for C++ API Reference
description: Returns an array of regions each of which bounds character positions in the specified string.
type: docs
weight: 508
url: /cpp/system.drawing/graphics/measurecharacterranges/
---
## Graphics::MeasureCharacterRanges(const [System::String](../../../system/string/)\&, const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\&, [RectangleF](../../rectanglef/), const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\>\&) method


Returns an array of regions each of which bounds character positions in the specified string.

```cpp
ArrayPtr<SharedPtr<Region>> System::Drawing::Graphics::MeasureCharacterRanges(const System::String &text, const SharedPtr<Font> &font, RectangleF layoutRect, const SharedPtr<StringFormat> &stringFormat)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| text | const [System::String](../../../system/string/)\& | The string to measure |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | The font used during the measurement of the string |
| layoutRect | [RectangleF](../../rectanglef/) | The layout rectangle used during the measurement of the string |
| stringFormat | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\>\& | The string format, contaions the character ranges to measure |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Region](../../region/)
* Class [String](../../../system/string/)
* Class [Font](../../font/)
* Class [RectangleF](../../rectanglef/)
* Class [StringFormat](../../stringformat/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)
