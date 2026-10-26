---
title: IFontFallBackRulesCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API Java
description: แสดงถึงคอลเลกชันของกฎ FontFallBack ที่กำหนดโดยผู้ใช้
type: docs
url: /th/com.aspose.slides/ifontfallbackrulescollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IFontFallBackRulesCollection extends IGenericCollection<IFontFallBackRule>
```

Represents a collection of FontFallBack rules, defined by user
## เมธอด

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ดึงกฎที่ตำแหน่งที่กำหนด. |
| [add(IFontFallBackRule sourceRule)](#add-com.aspose.slides.IFontFallBackRule-) | เพิ่มกฎ FallBack ใหม่ไปที่ส่วนท้ายของคอลเลกชัน. |
| [remove(IFontFallBackRule targetRule)](#remove-com.aspose.slides.IFontFallBackRule-) | ลบการเกิดครั้งแรกของกฎ FallBack เฉพาะจากคอลเลกชัน. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IFontFallBackRule get_Item(int index)
```


Gets the rule at the specified index. Read-only [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //การดึงคอลเลกชันกฎที่ว่างหรือกำหนดค่าไว้ล่วงหน้าจาก FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //การเพิ่มหลายกฎเข้าไปในคอลเลกชัน
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //การเรียกวัตถุของกฎแรกในคอลเลกชัน
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**
[IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
### add(IFontFallBackRule sourceRule) {#add-com.aspose.slides.IFontFallBackRule-}
```
public abstract void add(IFontFallBackRule sourceRule)
```


Add a new FallBack rule to the end of the collection.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //การดึงคอลเลกชันกฎที่ว่างหรือกำหนดค่าไว้ล่วงหน้าจาก FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //การเพิ่มกฎใหม่เข้าไปในคอลเลกชัน
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | กฎที่ระบุสำหรับการเพิ่ม |

### remove(IFontFallBackRule targetRule) {#remove-com.aspose.slides.IFontFallBackRule-}
```
public abstract void remove(IFontFallBackRule targetRule)
```


Removes the first occurrence of a specific FallBack rule from the collection.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //การดึงคอลเลกชันกฎที่ว่างหรือกำหนดค่าไว้ล่วงหน้าจาก FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //การเพิ่มหลายกฎเข้าไปในคอลเลกชัน
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //การเรียกวัตถุของกฎแรกในคอลเลกชัน
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>      //การลบ 
>      rulesList.remove(firstRule);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| targetRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | กฎที่จะลบออกจากคอลเลกชัน. |