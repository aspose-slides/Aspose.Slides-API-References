---
title: Remove
second_title: Aspose.Slides for .NET API 参考
description: 从集合中删除第一次出现的特定后备规则
type: docs
weight: 30
url: /zh/aspose.slides/ifontfallbackrulescollection/remove/
---
## IFontFallBackRulesCollection.Remove method

从集合中删除第一次出现的特定后备规则。

```csharp
public void Remove(IFontFallBackRule targetRule)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| targetRule | IFontFallBackRule | 从集合中删除的规则。 |

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
    //删除
    rulesList.Remove (firstRule);
}
```

### 也可以看看

* interface [IFontFallBackRule](../../ifontfallbackrule)
* interface [IFontFallBackRulesCollection](../../ifontfallbackrulescollection)
* 命名空间 [Aspose.Slides](../../ifontfallbackrulescollection)
* 部件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
