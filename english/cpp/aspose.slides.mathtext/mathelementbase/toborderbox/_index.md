---
title: ToBorderBox()
second_title: Aspose.Slides for C++ API Reference
description: Places this element in a border-box
type: docs
weight: 248
url: /cpp/aspose.slides.mathtext/mathelementbase/toborderbox/
---
## MathElementBase::ToBorderBox() method


Places this element in a border-box

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathElementBase::ToBorderBox() override
```


### Return Value

Border-box with this element placed inside
## Remarks



Example: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBorderBox](../../imathborderbox/)
* Class [MathElementBase](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
## MathElementBase::ToBorderBox(**bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**) method


Places this element in a border-box

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathElementBase::ToBorderBox(bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| hideTop | **bool** | Hide Top Edge |
| hideBottom | **bool** | Hide Bottom Edge |
| hideLeft | **bool** | Hide Left Edge |
| hideRight | **bool** | Hide Right Edge |
| strikethroughHorizontal | **bool** | Border Box Strikethrough Horizontal |
| strikethroughVertical | **bool** | Border Box Strikethrough Vertical |
| strikethroughBottomLeftToTopRight | **bool** | Border Box Strikethrough Bottom-Left to Top-Right |
| strikethroughTopLeftToBottomRight | **bool** | Border Box Strikethrough Top-Left to Bottom-Right |

### Return Value

Border-box with this element placed inside
## Remarks



Example: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox(false, false, true, true, false, false, false, false);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBorderBox](../../imathborderbox/)
* Class [MathElementBase](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
