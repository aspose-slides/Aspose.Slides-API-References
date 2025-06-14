---
title: Add
second_title: Aspose.Sildes for .NET API Reference
description: 将指定的 FallBack 规则添加到集合的末尾。
type: docs
weight: 60
url: /zh/aspose.slides/fontfallbackrulescollection/add/
---

## FontFallBackRulesCollection.Add 方法

将指定的 FallBack 规则添加到集合的末尾。

```csharp
public void Add(IFontFallBackRule sourceRule)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceRule | IFontFallBackRule | 要添加的指定规则 |

### 示例

```csharp
[C#]
using (Presentation pres = new Presentation ())
{
    //从 FontsManager 获取空的或预初始化的规则集合
    IFontFallBackRulesCollection rulesList = pres.FontsManager.FontFallBackRulesCollection;

    //将新规则添加到集合
    rulesList.Add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
}
```

### 另见

* 接口 [IFontFallBackRule](../../ifontfallbackrule)
* 类 [FontFallBackRulesCollection](../../fontfallbackrulescollection)
* 命名空间 [Aspose.Slides](../../fontfallbackrulescollection)
* 程序集 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->