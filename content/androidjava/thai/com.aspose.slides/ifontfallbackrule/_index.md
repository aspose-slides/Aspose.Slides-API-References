---
title: IFontFallBackRule
second_title: Aspose.Slides for Android via Java API Reference
description: แสดงกฎการสำรองแบบอักษร
type: docs
url: /th/com.aspose.slides/ifontfallbackrule/
---```
public interface IFontFallBackRule
```

แสดงกฎการสำรองแบบอักษร
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | เพิ่มฟอนท์ใหม่ลงในรายการ FallBack fonts |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | เพิ่มฟอนท์ใหม่ลงในรายการ FallBack fonts |
| [getRangeStartIndex()](#getRangeStartIndex--) | รับดัชนีแรกของช่วงยูนิโค้ดต่อเนื่อง |
| [getRangeEndIndex()](#getRangeEndIndex--) | รับดัชนีสุดท้ายของช่วงยูนิโค้ดต่อเนื่อง |
| [getCount()](#getCount--) | รับจำนวนฟอนท์ที่กำหนดไว้จริงสำหรับช่วง |
| [get_Item(int index)](#get-Item-int-) | รับชื่อฟอนท์ที่ตำแหน่งที่ระบุ |
| [clear()](#clear--) | ลบฟอนท์ทั้งหมดออกจากรายการ |
| [remove(String fontName)](#remove-java.lang.String-) | ลบการเกิดขึ้นครั้งแรกของฟอนท์ FallBack ที่กำหนดจากรายการ |
| [removeAt(int index)](#removeAt-int-) | ลบฟอนท์ FallBack ที่ตำแหน่งที่ระบุในรายการ |
| [toArray()](#toArray--) | สร้างและคืนอาร์เรย์ที่มีฟอนท์ FallBack ทั้งหมดสำหรับกฎนี้ |
| [toArray(int startIndex, int count)](#toArray-int-int-) | สร้างและคืนอาร์เรย์ที่มีฟอนท์ FallBack ทั้งหมดจากช่วงที่ระบุในรายการ |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | คืนดัชนีของกฎที่ระบุในคอลเลกชัน |

### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public abstract void addFallBackFonts(String fontName)
```

เพิ่มฟอนท์ใหม่ลงในรายการ FallBack fonts

--------------------

> ```
> //สร้างอินสแตนซ์ใหม่ของ FantFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //เพิ่มฟอนท์ที่สองลงในกฎ 
>  newRule.addFallBackFonts("MS Gothic");
>  //เพิ่มฟอนท์ที่สามและสี่ลงในกฎ 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```


**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | ชื่อหรือชื่อหลายชื่อของฟอนท์ (คั่นด้วยเครื่องหมายจุลภาค) สำหรับ FallBack |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public abstract void addFallBackFonts(String[] fontNames)
```

เพิ่มฟอนท์ใหม่ลงในรายการ FallBack fonts

--------------------

> ```
> //สร้างอินสแตนซ์ใหม่ของ FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //เพิ่มอีกสามฟอนท์ลงในกฎ 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
```

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontNames | java.lang.String[] | ชื่อหรือชื่อหลายชื่อของฟอนท์ (คั่นด้วยเครื่องหมายจุลภาค) สำหรับ FallBack |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public abstract long getRangeStartIndex()
```

รับดัชนีแรกของช่วงยูนิโค้ดต่อเนื่อง

**ผลลัพธ์:**
long

### getRangeEndIndex() {#getRangeEndIndex--}
```
public abstract long getRangeEndIndex()
```

รับดัชนีสุดท้ายของช่วงยูนิโค้ดต่อเนื่อง

**ผลลัพธ์:**
long

### getCount() {#getCount--}
```
public abstract int getCount()
```

รับจำนวนฟอนท์ที่กำหนดไว้จริงสำหรับช่วง

**ผลลัพธ์:**
int

### get_Item(int index) {#get-Item-int-}
```
public abstract String get_Item(int index)
```

รับชื่อฟอนท์ที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**ผลลัพธ์:**
java.lang.String

### clear() {#clear--}
```
public abstract void clear()
```

ลบฟอนท์ทั้งหมดออกจากรายการ

### remove(String fontName) {#remove-java.lang.String-}
```
public abstract void remove(String fontName)
```

ลบการเกิดขึ้นครั้งแรกของฟอนท์ FallBack ที่กำหนดจากรายการ

--------------------

> ```
> // Create a rule contains a list of fonts.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Removing of Tahoma from list
>  newRule.remove("Tahoma");
> ```

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | ชื่อฟอนท์ที่ต้องการลบออกจากรายการ |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

ลบฟอนท์ FallBack ที่ตำแหน่งที่ระบุในรายการ

--------------------

> ```
> // สร้างกฎที่มีรายการฟอนท์.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //ลบ Tahoma ออกจากรายการ
>  newRule.remove(2);
```

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีเริ่มต้นจากศูนย์ของฟอนท์ที่ต้องการลบ |

### toArray() {#toArray--}
```
public abstract String[] toArray()
```

สร้างและคืนอาร์เรย์ที่มีฟอนท์ FallBack ทั้งหมดสำหรับกฎนี้

--------------------

> ```
> // สร้างกฎที่มีรายการฟอนท์.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //รับชื่อฟอนท์ทั้งหมดเป็นอาร์เรย์
>  String[] fontNames = newRule.toArray();
> ```


**ผลลัพธ์:**
java.lang.String[] - Array of String

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract String[] toArray(int startIndex, int count)
```

สร้างและคืนอาร์เรย์ที่มีฟอนท์ FallBack ทั้งหมดจากช่วงที่ระบุในรายการ

--------------------

> ```
> // สร้างกฎที่มีรายการฟอนท์.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //รับชื่อฟอนท์สองรายการสุดท้ายเป็นอาร์เรย์
>  String[] fontNames = newRule.toArray(2,2);
> ```


**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | ดัชนีของฟอนท์แรกที่ต้องการเพิ่ม |
| count | int | จำนวนฟอนท์ที่ต้องการเพิ่ม |

**ผลลัพธ์:**
java.lang.String[] - Array of String

### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String fontName)
```

คืนดัชนีของกฎที่ระบุในคอลเลกชัน

--------------------

> ```
> // สร้างกฎที่มีรายการฟอนท์.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //รับดัชนีของ Tahoma
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```


**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | ชื่อฟอนท์ที่ต้องการค้นหา |

**ผลลัพธ์:**
int - ดัชนีของฟอนท์หรือ -1 หากไม่พบฟอนท์ในรายการ