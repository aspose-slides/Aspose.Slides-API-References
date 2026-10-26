---
title: IFontFallBackRulesCollection
second_title: Aspose.Slides สำหรับอ้างอิง API ของ Java
description: เป็นคอลเลกชันของกฎ FontFallBack ที่กำหนดโดยผู้ใช้
type: docs
url: /th/com.aspose.slides/ifontfallbackrulescollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IFontFallBackRulesCollection extends IGenericCollection<IFontFallBackRule>
```

เป็นคอลเลกชันของกฎ FontFallBack ที่กำหนดโดยผู้ใช้
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ดึงกฎที่ตำแหน่งที่ระบุ |
| [add(IFontFallBackRule sourceRule)](#add-com.aspose.slides.IFontFallBackRule-) | เพิ่มกฎ FallBack ใหม่ไปยังส่วนท้ายของคอลเลกชัน |
| [remove(IFontFallBackRule targetRule)](#remove-com.aspose.slides.IFontFallBackRule-) | ลบการพบครั้งแรกของกฎ FallBack เฉพาะจากคอลเลกชัน |
### get_Item(int index) {#get-Item-int-}
```
public abstract IFontFallBackRule get_Item(int index)
```


ดึงกฎที่ตำแหน่งที่ระบุ อ่านอย่างเดียว [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //การดึงคอลเลกชันของกฎที่ว่างหรือกำหนดค่าไว้ล่วงหน้าจาก FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //การเพิ่มกฎหลายรายการลงในคอลเลกชัน
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //การดึงอ็อบเจ็กต์ของกฎแรกในคอลเลกชัน
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ผลลัพธ์:**
[IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
### add(IFontFallBackRule sourceRule) {#add-com.aspose.slides.IFontFallBackRule-}
```
public abstract void add(IFontFallBackRule sourceRule)
```


เพิ่มกฎ FallBack ใหม่ไปยังส่วนท้ายของคอลเลกชัน

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //การดึงคอลเลกชันของกฎที่ว่างหรือกำหนดค่าไว้ล่วงหน้าจาก FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //การเพิ่มกฎใหม่ลงในคอลเลกชัน
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| sourceRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | กฎที่ระบุสำหรับการเพิ่ม |

### remove(IFontFallBackRule targetRule) {#remove-com.aspose.slides.IFontFallBackRule-}
```
public abstract void remove(IFontFallBackRule targetRule)
```


ลบการพบครั้งแรกของกฎ FallBack เฉพาะจากคอลเลกชัน

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //การดึงคอลเลกชันของกฎที่ว่างหรือกำหนดค่าไว้ล่วงหน้าจาก FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //การเพิ่มหลายกฎลงในคอลเลกชัน
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //การดึงอ็อบเจ็กต์ของกฎแรกในคอลเลกชัน
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>      //การลบ 
>      rulesList.remove(firstRule);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| targetRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | กฎที่จะลบออกจากคอลเลกชัน |