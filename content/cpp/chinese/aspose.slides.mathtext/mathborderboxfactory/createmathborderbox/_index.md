---
title: CreateMathBorderBox()
second_title: Aspose.Slides for C++ API 参考
description: 通过对元素应用来创建数学边框框
type: docs
weight: 1
url: /zh/aspose.slides.mathtext/mathborderboxfactory/createmathborderbox/
---
## MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>) 方法

通过对元素应用来创建数学边框框

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 要应用边框框的数学元素 |

### 返回值

新的边框框元素

## MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) 方法

通过对元素应用来创建数学边框框

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 要应用边框框的数学元素 |
| hideTop | **bool** | 隐藏顶部边缘 |
| hideBottom | **bool** | 隐藏底部边缘 |
| hideLeft | **bool** | 隐藏左侧边缘 |
| hideRight | **bool** | 隐藏右侧边缘 |
| strikethroughHorizontal | **bool** | 边框框水平删除线 |
| strikethroughVertical | **bool** | 边框框垂直删除线 |
| strikethroughBottomLeftToTopRight | **bool** | 边框框从左下至右上删除线 |
| strikethroughTopLeftToBottomRight | **bool** | 边框框从左上至右下删除线 |

### 返回值

新的边框框元素

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathBorderBox](../../imathborderbox/)
* 类 [IMathElement](../../imathelement/)
* 类 [MathBorderBoxFactory](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)