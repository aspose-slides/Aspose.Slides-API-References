---
title: SetMacroHyperlinkClick
second_title: Aspose.Slides for .NET API 参考
description: 单击设置宏超链接
type: docs
weight: 70
url: /zh/net/aspose.slides/hyperlinkmanager/setmacrohyperlinkclick/
---
## HyperlinkManager.SetMacroHyperlinkClick method

单击设置宏超链接。

```csharp
public IHyperlink SetMacroHyperlinkClick(string macroName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| macroName | String | 宏名称 |

### 返回值

超链接对象[`IHyperlink`](../../ihyperlink)

### 例子

```csharp
[C#]
using (Presentation presentation = new Presentation())
{
    IAutoShape shape = presentation.Slides[0].Shapes.AddAutoShape(ShapeType.BlankButton, 20, 20, 80, 30);
    shape.HyperlinkManager.SetMacroHyperlinkClick("MacroName");
}
```

### 也可以看看

* interface [IHyperlink](../../ihyperlink)
* class [HyperlinkManager](../../hyperlinkmanager)
* 命名空间 [Aspose.Slides](../../hyperlinkmanager)
* 部件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->