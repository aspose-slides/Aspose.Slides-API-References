---
title: IMotionPath
second_title: Aspose.Slides for .NET API Reference
description: 表示运动路径。
type: docs
weight: 450
url: /zh/aspose.slides.animation/imotionpath/
---

## IMotionPath 接口

表示运动路径。

```csharp
public interface IMotionPath : IEnumerable<IMotionCmdPath>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AsIEnumerable](../../aspose.slides.animation/imotionpath/asienumerable) { get; } | 允许获取基接口 IBehavior. 仅可读的 IEnumerable. |
| [Count](../../aspose.slides.animation/imotionpath/count) { get; } | 返回集合中路径的数量. 仅可读的 Int32. |
| [Item](../../aspose.slides.animation/imotionpath/item) { get; } | 返回指定索引处的命令. |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Add](../../aspose.slides.animation/imotionpath/add)(MotionCommandPathType, PointF[], MotionPathPointsType, bool) | 向路径添加新命令 |
| [Clear](../../aspose.slides.animation/imotionpath/clear)() | 从集合中删除所有命令. |
| [Insert](../../aspose.slides.animation/imotionpath/insert)(int, MotionCommandPathType, PointF[], MotionPathPointsType, bool) | 向路径插入新命令 |
| [Remove](../../aspose.slides.animation/imotionpath/remove)(IMotionCmdPath) | 从集合中删除指定命令. |
| [RemoveAt](../../aspose.slides.animation/imotionpath/removeat)(int) | 删除指定索引处的命令. |

### 另见

* 接口 [IMotionCmdPath](../imotioncmdpath)
* 命名空间 [Aspose.Slides.Animation](../../aspose.slides.animation)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->