---
title: AddTextPlaceholder
second_title: Aspose.Sildes for .NET API Reference
description: 将新的占位符形状添加到布局幻灯片中以容纳文本内容。
type: docs
weight: 80
url: /zh/aspose.slides/layoutplaceholdermanager/addtextplaceholder/
---

## LayoutPlaceholderManager.AddTextPlaceholder 方法

将新的占位符形状添加到布局幻灯片中以容纳文本内容。

```csharp
public IAutoShape AddTextPlaceholder(float x, float y, float width, float height)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | Single | 新占位符形状的 X 坐标。 |
| y | Single | 新占位符形状的 Y 坐标。 |
| width | Single | 新占位符形状的宽度。 |
| height | Single | 新占位符形状的高度。 |

### 返回值

创建的 [`IAutoShape`](../../iautoshape) ，具有文本占位符。

### 示例

下面的示例演示如何将文本占位符形状添加到布局幻灯片中。

```csharp
[C#]
using (Presentation pres = new Presentation())
{
	ILayoutSlide layout = pres.LayoutSlides.GetByType(SlideLayoutType.Blank);
	IAutoShape placeholder = layout.PlaceholderManager.AddTextPlaceholder(20, 20, 500, 300);
}
```

### 另请参见

* 接口 [IAutoShape](../../iautoshape)
* 类 [LayoutPlaceholderManager](../../layoutplaceholdermanager)
* 命名空间 [Aspose.Slides](../../layoutplaceholdermanager)
* 程序集 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->