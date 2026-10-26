---
title: ToBorderBox()
second_title: Aspose.Slides for C++ API 參考
description: 將此元素放入邊框盒中
type: docs
weight: 261
url: /zh-hant/aspose.slides.mathtext/imathelement/toborderbox/
---
## IMathElement::ToBorderBox() 方法


將此元素放入邊框盒中

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathElement::ToBorderBox()=0
```


### 返回值

包含此元素的邊框盒
## 備註



範例: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
```

## IMathElement::ToBorderBox(bool, bool, bool, bool, bool, bool, bool, bool) 方法


將此元素放入邊框盒中

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathElement::ToBorderBox(bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)=0
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| hideTop | **bool** | 隱藏上緣 |
| hideBottom | **bool** | 隱藏下緣 |
| hideLeft | **bool** | 隱藏左緣 |
| hideRight | **bool** | 隱藏右緣 |
| strikethroughHorizontal | **bool** | 邊框盒水平刪除線 |
| strikethroughVertical | **bool** | 邊框盒垂直刪除線 |
| strikethroughBottomLeftToTopRight | **bool** | 邊框盒從左下到右上刪除線 |
| strikethroughTopLeftToBottomRight | **bool** | 邊框盒從左上到右下刪除線 |

### 返回值

包含此元素的邊框盒
## 備註



範例: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox(false, false, true, true, false, false, false, false);
```

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBorderBox](../../imathborderbox/)
* Class [IMathElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)