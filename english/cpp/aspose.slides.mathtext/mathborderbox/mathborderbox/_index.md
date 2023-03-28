---
title: MathBorderBox()
second_title: Aspose.Slides for C++ API Reference
description: Creates MathBorderBox element with rectangular border
type: docs
weight: 222
url: /cpp/aspose.slides.mathtext/mathborderbox/mathborderbox/
---
## MathBorderBox::MathBorderBox([System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>) constructor


Creates [MathBorderBox](../) element with rectangular border

```cpp
Aspose::Slides::MathText::MathBorderBox::MathBorderBox(System::SharedPtr<IMathElement> element)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | The base element to which the border box is applied. Can be null. |
## Remarks



Example: 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"));
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathBorderBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
## MathBorderBox::MathBorderBox([System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**) constructor


Creates [MathBorderBox](../) element

```cpp
Aspose::Slides::MathText::MathBorderBox::MathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | The base element to which the border box is applied |
| hideTop | **bool** | Hide Top Edge |
| hideBottom | **bool** | Hide Bottom Edge |
| hideLeft | **bool** | Hide Left Edge |
| hideRight | **bool** | Hide Right Edge |
| strikethroughHorizontal | **bool** | Strikethrough Horizontal |
| strikethroughVertical | **bool** | Strikethrough Vertical |
| strikethroughBottomLeftToTopRight | **bool** | Strikethrough Bottom-Left to Top-Right |
| strikethroughTopLeftToBottomRight | **bool** | Strikethrough Top-Left to Bottom-Right |
## Remarks



Example: 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"), true, true, true, false, true, true, true, true);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathBorderBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
