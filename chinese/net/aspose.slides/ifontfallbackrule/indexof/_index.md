---
title: IndexOf
second_title: Aspose.Slides for .NET API 参考
description: 返回集合中指定规则的索引
type: docs
weight: 70
url: /zh/net/aspose.slides/ifontfallbackrule/indexof/
---
## IFontFallBackRule.IndexOf method

返回集合中指定规则的索引。

```csharp
public int IndexOf(string fontName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fontName | String | 要查找的字体名称。 |

### 返回值

字体索引，如果在列表中未找到字体，则为 -1。

### 例子

```csharp
[C#]
 // 创建一个包含字体列表的规则。
IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");

 //获取Tahoma

int tahomaIndex = newRule.IndexOf("Tahoma");
```

### 也可以看看

* interface [IFontFallBackRule](../../ifontfallbackrule)
* 命名空间 [Aspose.Slides](../../ifontfallbackrule)
* 部件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->