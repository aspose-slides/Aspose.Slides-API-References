---
title: IModernComment
second_title: Aspose.Slides for .NET API 参考
description: 表示幻灯片上的注释
type: docs
weight: 5900
url: /zh/net/aspose.slides/imoderncomment/
---
## IModernComment interface

表示幻灯片上的注释。

```csharp
public interface IModernComment : IComment
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AsIComment](../../aspose.slides/imoderncomment/asicomment) { get; } | 允许获取基本 IComment 接口。 只读[`IComment`](../icomment)。 |
| [Shape](../../aspose.slides/imoderncomment/shape) { get; } | 返回与注释关联的形状。 只读[`IShape`](../ishape)。 |
| [Status](../../aspose.slides/imoderncomment/status) { get; set; } | 返回或设置评论的状态。 读/写[`ModernCommentStatus`](../moderncommentstatus)。 |
| [TextSelectionLength](../../aspose.slides/imoderncomment/textselectionlength) { get; set; } | 如果注释与自选图形关联，则返回或设置文本框中的文本选择长度。 读/写Int32。 |
| [TextSelectionStart](../../aspose.slides/imoderncomment/textselectionstart) { get; set; } | 如果注释与自选图形关联，则返回或设置文本框架中文本选择的起始位置。 读/写Int32。 |

### 例子

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    ICommentAuthor newAuthor = pres.CommentAuthors.AddAuthor("Some Author", "SA");
    IModernComment modernComment = newAuthor.Comments.AddModernComment("This is modern comment", pres.Slides[0], null, new PointF(100, 100), DateTime.Now);

    pres.Save(outPptxFileName, SaveFormat.Pptx);
}
```

### 也可以看看

* interface [IComment](../icomment)
* 命名空间 [Aspose.Slides](../../aspose.slides)
* 部件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->