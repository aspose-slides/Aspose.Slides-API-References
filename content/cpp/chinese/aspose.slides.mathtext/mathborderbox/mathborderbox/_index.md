---
title: MathBorderBox()
second_title: Aspose.Slides for C++ API 参考
description: 创建带有矩形边框的 MathBorderBox 元素
type: docs
weight: 222
url: /zh/aspose.slides.mathtext/mathborderbox/mathborderbox/
---
## MathBorderBox::MathBorderBox(System::SharedPtr\<IMathElement\>) 构造函数

创建带有矩形边框的 [MathBorderBox](../) 元素

```cpp
Aspose::Slides::MathText::MathBorderBox::MathBorderBox(System::SharedPtr<IMathElement> element)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 要应用边框框的基元素。可以为 null。 |

## 备注



示例：
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBorderBox::MathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) 构造函数

创建 [MathBorderBox](../) 元素

```cpp
Aspose::Slides::MathText::MathBorderBox::MathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 要应用边框框的基元素 |
| hideTop | **bool** | 隐藏顶部边缘 |
| hideBottom | **bool** | 隐藏底部边缘 |
| hideLeft | **bool** | 隐藏左侧边缘 |
| hideRight | **bool** | 隐藏右侧边缘 |
| strikethroughHorizontal | **bool** | 水平删除线 |
| strikethroughVertical | **bool** | 垂直删除线 |
| strikethroughBottomLeftToTopRight | **bool** | 从左下到右上的删除线 |
| strikethroughTopLeftToBottomRight | **bool** | 从左上到右下的删除线 |

## 备注



示例：
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"), true, true, true, false, true, true, true, true);
```

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathElement](../../imathelement/)
* 类 [MathBorderBox](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)