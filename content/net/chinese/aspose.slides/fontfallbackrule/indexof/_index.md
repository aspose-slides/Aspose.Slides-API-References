---
title: IndexOf
second_title: Aspose.Sildes for .NET API Reference
description: 返回集合中指定规则的索引。
type: docs
weight: 80
url: /zh/aspose.slides/fontfallbackrule/indexof/
---

## FontFallBackRule.IndexOf 方法

返回集合中指定规则的索引。

```csharp
public int IndexOf(string fontName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontName | String | 要查找的字体名称。 |

### 返回值

字体的索引，如果列表中未找到字体，则返回 -1。

### 示例

```csharp
[C#]
// 创建一个包含字体列表的规则。
IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");

// 获取 Tahoma 的索引。
int tahomaIndex = newRule.IndexOf("Tahoma");
```

### 另见

* 类 [FontFallBackRule](../../fontfallbackrule)
* 命名空间 [Aspose.Slides](../../fontfallbackrule)
* 程序集 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->