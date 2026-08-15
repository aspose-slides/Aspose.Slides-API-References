---
title: ToBorderBox()
second_title: Aspose.Slides for C++ API 參考
description: 將此元素放置於邊框盒中
type: docs
weight: 248
url: /zh-hant/aspose.slides.mathtext/mathelementbase/toborderbox/
---
## MathElementBase::ToBorderBox() 方法


將此元素放置於邊框盒中

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathElementBase::ToBorderBox() override
```


### 返回值

包含此元素的邊框盒
## 備註



範例: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
```

## MathElementBase::ToBorderBox(bool, bool, bool, bool, bool, bool, bool, bool) 方法


將此元素放置於邊框盒中

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathElementBase::ToBorderBox(bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight) override
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| hideTop | **bool** | 隱藏上邊緣 |
| hideBottom | **bool** | 隱藏下邊緣 |
| hideLeft | **bool** | 隱藏左邊緣 |
| hideRight | **bool** | 隱藏右邊緣 |
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

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathBorderBox](../../imathborderbox/)
* 類別 [MathElementBase](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)