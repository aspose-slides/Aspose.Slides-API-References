---
title: RemoveAt
second_title: Aspose.Sildes for .NET API Reference
description: 在列表的指定索引处移除 FallBack 字体。
type: docs
weight: 90
url: /zh/aspose.slides/ifontfallbackrule/removeat/
---

## IFontFallBackRule.RemoveAt 方法

在列表的指定索引处移除 FallBack 字体。

```csharp
public void RemoveAt(int index)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | Int32 | 要移除的字体的零基索引。 |

### 示例

```csharp
[C#]
// 创建一个包含字体列表的规则。
IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");

// 从列表中移除 Tahoma
newRule.Remove (2);
```

### 另见

* 接口 [IFontFallBackRule](../../ifontfallbackrule)
* 命名空间 [Aspose.Slides](../../ifontfallbackrule)
* 程序集 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->