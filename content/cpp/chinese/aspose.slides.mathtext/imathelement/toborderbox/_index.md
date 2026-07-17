---
title: ToBorderBox()
second_title: Aspose.Slides for C++ API 参考
description: 将此元素放置在边框盒中
type: docs
weight: 261
url: /zh/aspose.slides.mathtext/imathelement/toborderbox/
---
## IMathElement::ToBorderBox() 方法


将此元素放置在边框盒中

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathElement::ToBorderBox()=0
```


### 返回值

边框盒中已放置此元素
## 备注



示例: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
```

## IMathElement::ToBorderBox(bool, bool, bool, bool, bool, bool, bool, bool) 方法


将此元素放置在边框盒中

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathElement::ToBorderBox(bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)=0
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| hideTop | **bool** | 隐藏顶部边缘 |
| hideBottom | **bool** | 隐藏底部边缘 |
| hideLeft | **bool** | 隐藏左侧边缘 |
| hideRight | **bool** | 隐藏右侧边缘 |
| strikethroughHorizontal | **bool** | 边框盒水平删除线 |
| strikethroughVertical | **bool** | 边框盒垂直删除线 |
| strikethroughBottomLeftToTopRight | **bool** | 边框盒从左下到右上删除线 |
| strikethroughTopLeftToBottomRight | **bool** | 边框盒从左上到右下删除线 |

### 返回值

边框盒中已放置此元素
## 备注



示例: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox(false, false, true, true, false, false, false, false);
```

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathBorderBox](../../imathborderbox/)
* 类 [IMathElement](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)