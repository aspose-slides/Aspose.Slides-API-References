---
title: FontFallBackRulesCollection
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API อ้างอิง
description: แสดงถึงคอลเลกชันของกฎ FontFallBack ที่กำหนดโดยผู้ใช้
type: docs
url: /th/com.aspose.slides/fontfallbackrulescollection/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
[com.aspose.slides.IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)
```
public class FontFallBackRulesCollection implements IFontFallBackRulesCollection
```

แสดงถึงคอลเลกชันของกฎ FontFallBack ที่กำหนดโดยผู้ใช้
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [FontFallBackRulesCollection()](#FontFallBackRulesCollection--) |  |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [size()](#size--) | รับจำนวนของกฎที่มีอยู่จริงในคอลเลกชัน. |
| [add(IFontFallBackRule sourceRule)](#add-com.aspose.slides.IFontFallBackRule-) | เพิ่มกฎ FallBack ที่ระบุลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [remove(IFontFallBackRule targetRule)](#remove-com.aspose.slides.IFontFallBackRule-) | ลบการปรากฏครั้งแรกของกฎ FallBack ที่ระบุจากคอลเลกชัน. |
| [get_Item(int index)](#get-Item-int-) | รับกฎที่ตำแหน่งที่ระบุ. |
| [iterator()](#iterator--) | คืนค่า enumerator ที่ทำการวนซ้ำผ่านคอลเลกชัน. |
| [iteratorJava()](#iteratorJava--) | คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกทุกองค์ประกอบจากคอลเลกชันไปยังอาเรย์ที่ระบุ. |
| [isSynchronized()](#isSynchronized--) | คืนค่าที่บ่งบอกว่าการเข้าถึงคอลเลกชันเป็นแบบ synchronized (thread-safe) หรือไม่. |
| [getSyncRoot()](#getSyncRoot--) | คืนรากฐานการซิงโครไนซ์. |
### FontFallBackRulesCollection() {#FontFallBackRulesCollection--}
```
public FontFallBackRulesCollection()
```


### size() {#size--}
```
public final int size()
```

รับจำนวนของกฎที่มีอยู่จริงในคอลเลกชัน. อ่านอย่างเดียว int.

**ค่าที่คืน:**
int
### add(IFontFallBackRule sourceRule) {#add-com.aspose.slides.IFontFallBackRule-}
```
public final void add(IFontFallBackRule sourceRule)
```

เพิ่มกฎ FallBack ที่ระบุลงในตำแหน่งสุดท้ายของคอลเลกชัน.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //การดึงคอลเลกชันของกฎที่ว่างหรือกำหนดล่วงหน้าจาก FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //การเพิ่มกฎใหม่ลงในคอลเลกชัน
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sourceRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | กฎที่ระบุสำหรับการเพิ่ม |

### remove(IFontFallBackRule targetRule) {#remove-com.aspose.slides.IFontFallBackRule-}
```
public final void remove(IFontFallBackRule targetRule)
```

ลบการปรากฏครั้งแรกของกฎ FallBack ที่ระบุจากคอลเลกชัน.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //การดึงคอลเลกชันของกฎที่ว่างหรือกำหนดล่วงหน้าจาก FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //การเพิ่มกฎหลายรายการลงในคอลเลกชัน
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //การดึงอ็อบเจกต์ของกฎแรกในคอลเลกชัน
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>      //การลบ
>      rulesList.remove(firstRule);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| targetRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | กฎที่ต้องการลบจากคอลเลกชัน. |

### get_Item(int index) {#get-Item-int-}
```
public final IFontFallBackRule get_Item(int index)
```

รับกฎที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //การดึงคอลเลกชันของกฎที่ว่างหรือกำหนดล่วงหน้าจาก FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //การเพิ่มกฎหลายรายการลงในคอลเลกชัน
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //การดึงอ็อบเจกต์ของกฎแรกในคอลเลกชัน
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ค่าที่คืน:**
[IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontFallBackRule> iterator()
```

คืนค่า enumerator ที่ทำการวนซ้ำผ่านคอลเลกชัน.

**ค่าที่คืน:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontFallBackRule> - IGenericEnumerator ที่สามารถใช้เพื่อวนซ้ำผ่านคอลเลกชัน.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontFallBackRule> iteratorJava()
```

คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด.

**ค่าที่คืน:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontFallBackRule> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

คัดลอกทุกองค์ประกอบจากคอลเลกชันไปยังอาเรย์ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาเรย์เป้าหมาย. |
| index | int | ดัชนีเริ่มต้นในอาเรย์เป้าหมาย. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

คืนค่าที่บ่งบอกว่าการเข้าถึงคอลเลกชันเป็นแบบ synchronized (thread-safe) หรือไม่. อ่านอย่างเดียว boolean.

**ค่าที่คืน:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

คืนรากฐานการซิงโครไนซ์. อ่านอย่างเดียว Object.

**ค่าที่คืน:**
java.lang.Object