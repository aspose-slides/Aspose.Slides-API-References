---
title: Remove
second_title: Aspose.Sildes for .NET API Reference
description: 从列表中移除特定 FallBack 字体的第一次出现。
type: docs
weight: 90
url: /zh/aspose.slides/fontfallbackrule/remove/
---

## FontFallBackRule.Remove 方法

从列表中移除特定 FallBack 字体的第一次出现。

```csharp
public void Remove(string fontName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontName | String | 要从列表中移除的字体名称。 |

### 示例

```csharp
[C#]
// 创建一个包含字体列表的规则。
IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");

// 从列表中移除 Tahoma。
newRule.Remove ("Tahoma");
```

### 另见

* class [FontFallBackRule](../../fontfallbackrule)
* namespace [Aspose.Slides](../../fontfallbackrule)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->