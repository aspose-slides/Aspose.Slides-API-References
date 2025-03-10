---
title: IComment
second_title: Aspose.Slides for .NET API 参考
description: 表示幻灯片上的注释
type: docs
weight: 5060
url: /zh/aspose.slides/icomment/
---
## IComment interface

表示幻灯片上的注释。

```csharp
public interface IComment
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Author](../../aspose.slides/icomment/author) { get; } | 返回评论的作者。 只读[`ICommentAuthor`](../icommentauthor)。 |
| [CreatedTime](../../aspose.slides/icomment/createdtime) { get; set; } | 返回或设置评论创建时间。 将此属性设置为MinValue意味着没有设置评论时间。 读/写DateTime。 |
| [ParentComment](../../aspose.slides/icomment/parentcomment) { get; set; } | 获取或设置父评论。 读/写[`IComment`](../icomment)。 |
| [Position](../../aspose.slides/icomment/position) { get; set; } | 返回或设置幻灯片上注释的位置。 读/写PointF。 |
| [Slide](../../aspose.slides/icomment/slide) { get; } | 返回或设置评论的父幻灯片。 只读[`ISlide`](../islide)。 |
| [Text](../../aspose.slides/icomment/text) { get; set; } | 返回或设置幻灯片注释的纯文本。 读/写String。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Remove](../../aspose.slides/icomment/remove)() | 从父集合中删除评论及其所有回复。 |

### 也可以看看

* 命名空间 [Aspose.Slides](../../aspose.slides)
* 部件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
