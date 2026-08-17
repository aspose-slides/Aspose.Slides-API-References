---
title: IFontFallBackRulesCollection
second_title: Aspose.Slides Java API 参考
description: 表示由用户定义的 FontFallBack 规则集合
type: docs
url: /zh/com.aspose.slides/ifontfallbackrulescollection/
---
**所有实现的接口：**
com.aspose.slides.IGenericCollection
```
public interface IFontFallBackRulesCollection extends IGenericCollection<IFontFallBackRule>
```

表示由用户定义的 FontFallBack 规则的集合
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的规则。 |
| [add(IFontFallBackRule sourceRule)](#add-com.aspose.slides.IFontFallBackRule-) | 在集合末尾添加一个新的 FallBack 规则。 |
| [remove(IFontFallBackRule targetRule)](#remove-com.aspose.slides.IFontFallBackRule-) | 从集合中删除特定 FallBack 规则的第一次出现。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IFontFallBackRule get_Item(int index)
```

获取指定索引处的规则。只读 [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)。

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //从 FontsManager 获取空的或预初始化的规则集合
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //向集合添加多个规则
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //检索集合中第一个规则的对象
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回值：**
[IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
### add(IFontFallBackRule sourceRule) {#add-com.aspose.slides.IFontFallBackRule-}
```
public abstract void add(IFontFallBackRule sourceRule)
```

在集合末尾添加一个新的 FallBack 规则。

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //获取来自 FontsManager 的空或预初始化的规则集合
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //向集合中添加新规则
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | 用于添加的指定规则 |

### remove(IFontFallBackRule targetRule) {#remove-com.aspose.slides.IFontFallBackRule-}
```
public abstract void remove(IFontFallBackRule targetRule)
```

从集合中删除特定 FallBack 规则的第一次出现。

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //从 FontsManager 获取空的或预初始化的规则集合
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //向集合中添加多个规则
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //检索集合中第一个规则的对象
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>      //移除
>      rulesList.remove(firstRule);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| targetRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | 要从集合中删除的规则。 |