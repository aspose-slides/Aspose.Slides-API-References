---
title: RawFrame
second_title: Aspose.Sildes for .NET API Reference
description: 返回或设置原始形状框的属性。可读写 IShapeFrameaspose.slides/ishapeframe。
type: docs
weight: 210
url: /zh/aspose.slides/ishape/rawframe/
---

## IShape.RawFrame 属性

返回或设置原始形状框的属性。可读写 [`IShapeFrame`](../../ishapeframe)。

```csharp
public IShapeFrame RawFrame { get; set; }
```

### 示例

尝试将未定义的框分配给 IShape.Frame 的代码在一般情况下没有意义（特别是在父级 GroupShape 多重嵌套到其他 GroupShape 中的情况下）。例如：

```csharp
IShape shape = ...;
shape.Frame = new ShapeFrame(float.NaN, float.NaN, float.NaN, float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, float.NaN);
```

或

```csharp
slide.Shapes.AddAutoShape(ShapeType.RoundCornerRectangle, float.NaN, float.NaN, float.NaN, float.NaN);
```

这样的代码可能导致不明确的情况。因此，对于使用未定义值的 IShape.Frame 添加了限制。x、y、width、height、flipH、flipV 和 rotationAngle 的值必须是定义的（不能是 float.NaN 或 NullableBool.NotDefined）。上面的示例代码现在抛出 ArgumentException 异常。这适用于以下用例：

```csharp
IShape shape = ...;
shape.Frame = ...; // 不能是未定义的

IShapeCollection shapes = ...;
// x, y, width, height 参数不能是 float.NaN:
{
    shapes.AddAudioFrameCD(...);
    shapes.AddAudioFrameEmbedded(...);
    shapes.AddAudioFrameLinked(...);
    shapes.AddAutoShape(...);
    shapes.AddChart(...);
    shapes.AddConnector(...);
    shapes.AddOleObjectFrame(...);
    shapes.AddPictureFrame(...);
    shapes.AddSmartArt(...);
    shapes.AddTable(...);
    shapes.AddVideoFrame(...);
    shapes.InsertAudioFrameEmbedded(...);
    shapes.InsertAudioFrameLinked(...);
    shapes.InsertAutoShape(...);
    shapes.InsertChart(...);
    shapes.InsertConnector(...);
    shapes.InsertOleObjectFrame(...);
    shapes.InsertPictureFrame(...);
    shapes.InsertTable(...);
    shapes.InsertVideoFrame(...);
}
```

但是 IShape.RawFrame 的框属性可以是未定义的。这是合乎逻辑的，当形状链接到占位符时。然后未定义的形状框值从父占位符形状中被覆盖。如果该形状没有父占位符形状，则该形状在基于其 IShape.RawFrame 评估有效框时使用默认值。默认值为 x、y、width、height、flipH、flipV 和 rotationAngle 的 0 和 NullableBool.False。例如：

```csharp
IShape shape = ...; // 形状链接到占位符
shape.RawFrame = new ShapeFrame(float.NaN, float.NaN, 100, float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0); // 现在形状从占位符继承 x、y、高度、flipH、flipV 值，并覆盖 width=100 和 rotationAngle=0。
```

### 另请参阅

* 接口 [IShapeFrame](../../ishapeframe)
* 接口 [IShape](../../ishape)
* 命名空间 [Aspose.Slides](../../ishape)
* 程序集 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->