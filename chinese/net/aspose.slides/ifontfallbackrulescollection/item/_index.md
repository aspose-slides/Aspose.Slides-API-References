---
title: Item
second_title: Aspose.Slides for .NET API 参考
description: 获取指定索引处的规则 只读IFontFallBackRuleaspose.slides/ifontfallbackrule
type: docs
weight: 10
url: /zh/net/aspose.slides/ifontfallbackrulescollection/item/
---
## IFontFallBackRulesCollection indexer

获取指定索引处的规则。 只读[`IFontFallBackRule`](../../ifontfallbackrule)。

```csharp
public IFontFallBackRule this[int index] { get; }
```

### 例子

```csharp
[C#]
using (Presentation pres = new Presentation ())
{
     //从 FontsManager
则集合
    IFontFallBackRulesCollection rulesList = pres.FontsManager.FontFallBackRulesCollection;

    //向collection

    rulesList.Add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
    rulesList.Add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));

    //获取collection

    IFontFallBackRule firstRule = rulesList[0];
}
```

### 也可以看看

* interface [IFontFallBackRule](../../ifontfallbackrule)
* interface [IFontFallBackRulesCollection](../../ifontfallbackrulescollection)
* 命名空间 [Aspose.Slides](../../ifontfallbackrulescollection)
* 部件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->