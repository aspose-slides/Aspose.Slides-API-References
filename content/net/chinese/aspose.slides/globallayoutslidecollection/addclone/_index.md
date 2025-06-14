---
title: AddClone
second_title: Aspose.Sildes for .NET API Reference
description: 将指定的布局幻灯片的副本添加到演示文稿中。
type: docs
weight: 20
url: /zh/aspose.slides/globallayoutslidecollection/addclone/
---

## AddClone(ILayoutSlide) {#addclone}

将指定的布局幻灯片的副本添加到演示文稿中。

```csharp
public ILayoutSlide AddClone(ILayoutSlide sourceLayout)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceLayout | ILayoutSlide | 要克隆的幻灯片。 |

### 返回值

添加的幻灯片。

### 备注

在不同演示文稿之间克隆布局时，可以克隆布局的母板以保持源格式。使用内部注册表跟踪自动克隆的母板，以防止创建相同母板幻灯片的多个克隆。手动克隆母板幻灯片不会被阻止或注册。

### 另请参阅

* 接口 [ILayoutSlide](../../ilayoutslide)
* 类 [GlobalLayoutSlideCollection](../../globallayoutslidecollection)
* 命名空间 [Aspose.Slides](../../globallayoutslidecollection)
* 程序集 [Aspose.Slides](../../../)

---

## AddClone(ILayoutSlide, IMasterSlide) {#addclone_1}

将指定的布局幻灯片的副本添加到演示文稿中。

```csharp
public ILayoutSlide AddClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceLayout | ILayoutSlide | 要克隆的幻灯片。 |
| destMaster | IMasterSlide | 新布局的母板幻灯片。 |

### 返回值

添加的幻灯片。

### 备注

1) 新布局将与目标演示文稿中定义的母板链接。因此，这是在 PowerPoint 中使用“使用目标主题”选项的复制/粘贴的类似功能。2) 此方法的类似方法是通过 [`LayoutSlides`](../../imasterslide/layoutslides) 属性访问的 [`AddClone`](../../imasterlayoutslidecollection/addclone) 方法。

### 另请参阅

* 接口 [ILayoutSlide](../../ilayoutslide)
* 接口 [IMasterSlide](../../imasterslide)
* 类 [GlobalLayoutSlideCollection](../../globallayoutslidecollection)
* 命名空间 [Aspose.Slides](../../globallayoutslidecollection)
* 程序集 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->