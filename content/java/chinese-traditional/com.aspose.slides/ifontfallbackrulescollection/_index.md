---
title: IFontFallBackRulesCollection
second_title: Aspose.Slides for Java API 參考
description: 表示使用者定義的 FontFallBack 規則集合
type: docs
url: /zh-hant/com.aspose.slides/ifontfallbackrulescollection/
---
**所有已實作介面**:
com.aspose.slides.IGenericCollection
```
public interface IFontFallBackRulesCollection extends IGenericCollection<IFontFallBackRule>
```

表示由使用者定義的 FontFallBack 規則集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的規則。 |
| [add(IFontFallBackRule sourceRule)](#add-com.aspose.slides.IFontFallBackRule-) | 在集合的末端新增一個 FallBack 規則。 |
| [remove(IFontFallBackRule targetRule)](#remove-com.aspose.slides.IFontFallBackRule-) | 從集合中移除第一個特定的 FallBack 規則。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IFontFallBackRule get_Item(int index)
```


取得指定索引處的規則。唯讀 [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //從 FontsManager 獲取空的或預先初始化的規則集合
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //向集合添加多個規則
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //檢索集合中第一個規則的對象
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數**:
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**傳回值**:
[IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
### add(IFontFallBackRule sourceRule) {#add-com.aspose.slides.IFontFallBackRule-}
```
public abstract void add(IFontFallBackRule sourceRule)
```


在集合的末端新增一個 FallBack 規則。

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //從 FontsManager 獲取空的或預先初始化的規則集合
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //向集合添加新規則
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數**:
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sourceRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | 指定要加入的規則 |

### remove(IFontFallBackRule targetRule) {#remove-com.aspose.slides.IFontFallBackRule-}
```
public abstract void remove(IFontFallBackRule targetRule)
```


從集合中移除第一個特定的 FallBack 規則。

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //從 FontsManager 獲取空的或預先初始化的規則集合
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //向集合添加多個規則
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Minjo"));
>      //檢索集合中第一個規則的對象
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>      //移除 
>      rulesList.remove(firstRule);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數**:
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| targetRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | 要從集合中移除的規則。 |