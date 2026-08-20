---
title: IFontFallBackRule
second_title: Aspose.Slides for Java API Reference
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
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | เพิ่มฟอนต์ใหม่ไปยังรายการฟอนต์ FallBack. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | เพิ่มฟอนต์ใหม่ไปยังรายการฟอนต์ FallBack. |
| [getRangeStartIndex()](#getRangeStartIndex--) | รับดัชนีแรกของช่วงยูนิโค้ดต่อเนื่อง. |
| [getRangeEndIndex()](#getRangeEndIndex--) | รับดัชนีสุดท้ายของช่วงยูนิโค้ดต่อเนื่อง. |
| [getCount()](#getCount--) | รับจำนวนฟอนต์ที่กำหนดจริงสำหรับช่วง. |
| [get_Item(int index)](#get-Item-int-) | รับชื่อฟอนต์ที่ดัชนีที่ระบุ. |
| [clear()](#clear--) | ลบฟอนต์ทั้งหมดจากรายการ. |
| [remove(String fontName)](#remove-java.lang.String-) | ลบการเกิดครั้งแรกของฟอนต์ FallBack เฉพาะจากรายการ. |
| [removeAt(int index)](#removeAt-int-) | ลบฟอนต์ FallBack ที่ดัชนีที่ระบุจากรายการ. |
| [toArray()](#toArray--) | สร้างและคืนค่าอาร์เรย์ที่มีฟอนต์ FallBack ทั้งหมดสำหรับกฎนี้. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | สร้างและคืนค่าอาร์เรย์ที่มีฟอนต์ FallBack ทั้งหมดจากช่วงที่ระบุในรายการ. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | คืนค่าดัชนีของกฎที่ระบุในคอลเลกชัน. |
### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public abstract void addFallBackFonts(String fontName)
```

เพิ่มฟอนต์ใหม่ไปยังรายการฟอนต์ FallBack

--------------------

> ```
> //สร้างอินสแตนซ์ใหม่ของ FantFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //เพิ่มฟอนต์ที่สองไปยังกฎ 
>  newRule.addFallBackFonts("MS Gothic");
>  //เพิ่มฟอนต์ที่สามและสี่ไปยังกฎ 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| fontName | java.lang.String | ชื่อหรือชื่อหลายชื่อของฟอนต์ (คั่นด้วยเครื่องหมายคอมม่า) สำหรับ FallBack |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public abstract void addFallBackFonts(String[] fontNames)
```

เพิ่มฟอนต์ใหม่ไปยังรายการฟอนต์ FallBack

--------------------

> ```
> //สร้างอินสแตนซ์ใหม่ของ FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //เพิ่มอีกสามฟอนต์ไปยังกฎ 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| fontNames | java.lang.String[] | ชื่อหรือชื่อหลายชื่อของฟอนต์ (คั่นด้วยเครื่องหมายคอมม่า) สำหรับ FallBack |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public abstract long getRangeStartIndex()
```

รับดัชนีแรกของช่วงยูนิโค้ดต่อเนื่อง

**คืนค่า:**
long
### getRangeEndIndex() {#getRangeEndIndex--}
```
public abstract long getRangeEndIndex()
```

รับดัชนีสุดท้ายของช่วงยูนิโค้ดต่อเนื่อง

**คืนค่า:**
long
### getCount() {#getCount--}
```
public abstract int getCount()
```

รับจำนวนฟอนต์ที่กำหนดจริงสำหรับช่วง

**คืนค่า:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract String get_Item(int index)
```

รับชื่อฟอนต์ที่ดัชนีที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**
java.lang.String
### clear() {#clear--}
```
public abstract void clear()
```

ลบฟอนต์ทั้งหมดจากรายการ

### remove(String fontName) {#remove-java.lang.String-}
```
public abstract void remove(String fontName)
```

ลบการเกิดครั้งแรกของฟอนต์ FallBack เฉพาะจากรายการ

--------------------

> ```
> // สร้างกฎที่มีรายการฟอนต์.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //ลบ Tahoma ออกจากรายการ
>  newRule.remove("Tahoma");
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| fontName | java.lang.String | ชื่อฟอนต์ที่ต้องการลบจากรายการ. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

ลบฟอนต์ FallBack ที่ดัชนีที่ระบุจากรายการ

--------------------

> ```
> // สร้างกฎที่มีรายการฟอนต์.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //ลบ Tahoma ออกจากรายการ
>  newRule.remove(2);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีเริ่มต้นตั้งแต่ศูนย์ของฟอนต์ที่ต้องการลบ. |

### toArray() {#toArray--}
```
public abstract String[] toArray()
```

สร้างและคืนค่าอาร์เรย์ที่มีฟอนต์ FallBack ทั้งหมดสำหรับกฎนี้

--------------------

> ```
> // สร้างกฎที่มีรายการฟอนต์.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //รับชื่อฟอนต์ทั้งหมดเป็นอาร์เรย์
>  String[] fontNames = newRule.toArray();
> ```

**คืนค่า:**
java.lang.String[] - อาร์เรย์ของ String
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract String[] toArray(int startIndex, int count)
```

สร้างและคืนค่าอาร์เรย์ที่มีฟอนต์ FallBack ทั้งหมดจากช่วงที่ระบุในรายการ

--------------------

> ```
> // สร้างกฎที่มีรายการฟอนต์.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //รับชื่อฟอนต์สองตัวสุดท้ายเป็นอาร์เรย์
>  String[] fontNames = newRule.toArray(2,2);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| startIndex | int | ดัชนีของฟอนต์แรกที่เพิ่ม. |
| count | int | จำนวนฟอนต์ที่เพิ่ม. |

**คืนค่า:**
java.lang.String[] - อาร์เรย์ของ String
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String fontName)
```

คืนค่าดัชนีของกฎที่ระบุในคอลเลกชัน

--------------------

> ```
> // สร้างกฎที่มีรายการฟอนต์.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //รับดัชนีของ Tahoma
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| fontName | java.lang.String | ชื่อฟอนต์ที่ต้องการค้นหา. |

**คืนค่า:**
int - ดัชนีของฟอนต์หรือ -1 ถ้าฟอนต์ไม่พบในรายการ.