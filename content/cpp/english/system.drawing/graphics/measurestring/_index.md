---
title: MeasureString()
second_title: Aspose.Slides for C++ API Reference
description: Returns a size of the specified string when drawn in the specified font in the specified format.
type: docs
weight: 521
url: /system.drawing/graphics/measurestring/
---
## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, PointF const\&, System::SharedPtr\<StringFormat\> const\&) const method


Returns a size of the specified string when drawn in the specified font in the specified format.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, PointF const &origin=PointF(0, 0), System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | The string whose size to calculate |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | The font used to draw the string |
| origin | [PointF](../../pointf/) const\& | Specifies the location of the upper left corner of the string |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | Specifies the string format |

### Return Value

A [SizeF](../../sizef/) object that represents the size of the string in the measurment units specified by the PageUnit property of the current Grapphics object.

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, int, System::SharedPtr\<StringFormat\> const\&) const method


Returns a size of the specified string when drawn in the specified font in the specified format.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, int width, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | The string whose size to calculate |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | The font used to draw the string |
| width | int | The maximum width of the string |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | Specifies the string format |

### Return Value

A [SizeF](../../sizef/) object that represents the size of the string in the measurment units specified by the PageUnit property of the current Grapphics object.

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, SizeF const\&, System::SharedPtr\<StringFormat\> const\&, int\&, int\&) const method


NOT IMPLEMENTED.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat, int &charactersFitted, int &linesFilled) const
```


## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, SizeF const\&, System::SharedPtr\<StringFormat\> const\&) const method


Returns a size of the specified string when drawn in the specified font in the specified format.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | The string whose size to calculate |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | The font used to draw the string |
| layoutArea | [SizeF](../../sizef/) const\& | The maximum layout area of the string |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | Specifies the string format |

### Return Value

A [SizeF](../../sizef/) object that represents the size of the string in the measurment units specified by the PageUnit property of the current Grapphics object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SizeF](../../sizef/)
* Class [String](../../../system/string/)
* Class [Font](../../font/)
* Class [PointF](../../pointf/)
* Class [StringFormat](../../stringformat/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)