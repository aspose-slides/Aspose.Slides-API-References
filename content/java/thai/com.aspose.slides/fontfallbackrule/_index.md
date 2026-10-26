---
title: FontFallBackRule
second_title: Aspose.Slides สำหรับอ้างอิง API ของ Java
description: แสดงกฎการสำรองฟอนต์
type: docs
url: /th/com.aspose.slides/fontfallbackrule/
---
**การสืบทอด:**
java.lang.Object

**ทุกอินเทอร์เฟซที่ทำการนำไปใช้:**
[com.aspose.slides.IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
```
public class FontFallBackRule implements IFontFallBackRule
```

แสดงกฎการสำรองฟอนต์
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [FontFallBackRule(long startIndex, long endIndex, String fontNames)](#FontFallBackRule-long-long-java.lang.String-) | สร้างอินสแตนซ์ใหม่. |
| [FontFallBackRule(long startIndex, long endIndex, String[] fontNames)](#FontFallBackRule-long-long-java.lang.String---) | สร้างอินสแตนซ์ใหม่. |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | เพิ่มฟอนต์ใหม่(s) ไปยังรายการฟอนต์ FallBack. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | เพิ่มฟอนต์ใหม่ไปยังรายการฟอนต์ FallBack. |
| [getRangeStartIndex()](#getRangeStartIndex--) | รับค่า index แรกของช่วงยูนิโค้ดต่อเนื่อง. |
| [setRangeStartIndex(long value)](#setRangeStartIndex-long-) | รับค่า index แรกของช่วงยูนิโค้ดต่อเนื่อง. |
| [getRangeEndIndex()](#getRangeEndIndex--) | รับค่า index สุดท้ายของช่วงยูนิโค้ดต่อเนื่อง. |
| [setRangeEndIndex(long value)](#setRangeEndIndex-long-) | รับค่า index สุดท้ายของช่วงยูนิโค้ดต่อเนื่อง. |
| [getCount()](#getCount--) | รับจำนวนฟอนต์ที่กำหนดไว้จริงในช่วง. |
| [get_Item(int index)](#get-Item-int-) | รับชื่อฟอนต์ที่ index ที่กำหนด. |
| [clear()](#clear--) | ลบฟอนต์ทั้งหมดจากรายการ. |
| [remove(String fontName)](#remove-java.lang.String-) | ลบการเกิดครั้งแรกของฟอนต์ FallBack ที่ระบุจากรายการ. |
| [removeAt(int index)](#removeAt-int-) | ลบฟอนต์ FallBack ที่ index ที่กำหนดของรายการ. |
| [toArray()](#toArray--) | สร้างและคืนค่าอาเรย์ที่มีฟอนต์ FallBack ทั้งหมดสำหรับกฎนี้. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | สร้างและคืนค่าอาเรย์ที่มีฟอนต์ FallBack ทั้งหมดจากช่วงที่ระบุในรายการ. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | คืนค่า index ของกฎที่ระบุในคอลเลกชัน. |
### FontFallBackRule(long startIndex, long endIndex, String fontNames) {#FontFallBackRule-long-long-java.lang.String-}
```
public FontFallBackRule(long startIndex, long endIndex, String fontNames)
```

สร้างอินสแตนซ์ใหม่.

--------------------

> ```
> // สร้างอินสแตนซ์ใหม่ของ FantFallBackRule ด้วยฟอนต์หนึ่งตัว.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  // สร้างอินสแตนซ์ใหม่ของ FantFallBackRule ด้วยหลายฟอนต์.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma");
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| startIndex | long | Index เริ่มต้นของช่วงยูนิโค้ด |
| endIndex | long | Index สิ้นสุดของช่วงยูนิโค้ด |
| fontNames | java.lang.String | ชื่อหรือชื่อหลายของฟอนต์ (คั่นด้วยเครื่องหมายคอมม่า) สำหรับ FallBack |

### FontFallBackRule(long startIndex, long endIndex, String[] fontNames) {#FontFallBackRule-long-long-java.lang.String---}
```
public FontFallBackRule(long startIndex, long endIndex, String[] fontNames)
```

สร้างอินสแตนซ์ใหม่.

--------------------

> ```
> // สร้างอินสแตนซ์ใหม่ของ FantFallBackRule ด้วยฟอนต์สองตัว
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Mincho", "MS Gothic"});
>  // สร้างอินสแตนซ์ใหม่ของ FantFallBackRule ด้วยหลายฟอนต์.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Gothic", "Tahoma, Times New Roman" });
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| startIndex | long | Index เริ่มต้นของช่วงยูนิโค้ด |
| endIndex | long | Index สิ้นสุดของช่วงยูนิโค้ด |
| fontNames | java.lang.String[] | ชื่อหรือชื่อหลายของฟอนต์ (คั่นด้วยเครื่องหมายคอมม่า) สำหรับ FallBack |

### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public final void addFallBackFonts(String fontName)
```

เพิ่มฟอนต์ใหม่(s) ไปยังรายการฟอนต์ FallBack.

--------------------

> ```
> // สร้างอินสแตนซ์ใหม่ของ FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  // เพิ่มฟอนต์ที่สองไปยังกฎ 
>  newRule.addFallBackFonts("MS Gothic");
>  // เพิ่มฟอนต์ที่สามและสี่ไปยังกฎ 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fontName | java.lang.String | ชื่อหรือชื่อหลายของฟอนต์ (คั่นด้วยเครื่องหมายคอมม่า) สำหรับ FallBack |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public final void addFallBackFonts(String[] fontNames)
```

เพิ่มฟอนต์ใหม่ไปยังรายการฟอนต์ FallBack.

--------------------

> ```
> // สร้างอินสแตนซ์ใหม่ของ FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  // เพิ่มอีกสามฟอนต์ไปยังกฎ 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fontNames | java.lang.String[] | ชื่อหรือชื่อหลายของฟอนต์ (คั่นด้วยเครื่องหมายคอมม่า) สำหรับ FallBack |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public final long getRangeStartIndex()
```

รับค่า index แรกของช่วงยูนิโค้ดต่อเนื่อง.

**คืนค่า:**
long
### setRangeStartIndex(long value) {#setRangeStartIndex-long-}
```
public final void setRangeStartIndex(long value)
```

รับค่า index แรกของช่วงยูนิโค้ดต่อเนื่อง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | long |  |

### getRangeEndIndex() {#getRangeEndIndex--}
```
public final long getRangeEndIndex()
```

รับค่า index สุดท้ายของช่วงยูนิโค้ดต่อเนื่อง.

**คืนค่า:**
long
### setRangeEndIndex(long value) {#setRangeEndIndex-long-}
```
public final void setRangeEndIndex(long value)
```

รับค่า index สุดท้ายของช่วงยูนิโค้ดต่อเนื่อง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | long |  |

### getCount() {#getCount--}
```
public final int getCount()
```

รับจำนวนฟอนต์ที่กำหนดไว้จริงในช่วง อ่านอย่างเดียว int.

**คืนค่า:**
int
### get_Item(int index) {#get-Item-int-}
```
public final String get_Item(int index)
```

รับชื่อฟอนต์ที่ index ที่กำหนด อ่านอย่างเดียว [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**
java.lang.String
### clear() {#clear--}
```
public final void clear()
```

ลบฟอนต์ทั้งหมดจากรายการ.

### remove(String fontName) {#remove-java.lang.String-}
```
public final void remove(String fontName)
```

ลบการเกิดครั้งแรกของฟอนต์ FallBack ที่ระบุจากรายการ.

--------------------

> ```
> // สร้างกฎที่มีรายการฟอนต์.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // ลบ Tahoma จากรายการ.
>  newRule.remove("Tahoma");
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fontName | java.lang.String | ชื่อฟอนต์ที่ต้องการลบจากรายการ. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

ลบฟอนต์ FallBack ที่ index ที่กำหนดของรายการ.

--------------------

> ```
> // สร้างกฎที่มีรายการฟอนต์.
>  //กำลังลบ Tahoma จากรายการ.
>  newRule.remove(2);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | Index เริ่มต้นจากศูนย์ของฟอนต์ที่ต้องการลบ. |

### toArray() {#toArray--}
```
public final String[] toArray()
```

สร้างและคืนค่าอาเรย์ที่มีฟอนต์ FallBack ทั้งหมดสำหรับกฎนี้.

--------------------

> ```
> // สร้างกฎที่มีรายการฟอนต์.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // รับชื่อฟอนต์ทั้งหมดเป็นอาร์เรย์.
>  String[] fontNames = newRule.toArray();
> ```


**คืนค่า:**
java.lang.String[] - Array of String
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final String[] toArray(int startIndex, int count)
```

สร้างและคืนค่าอาเรย์ที่มีฟอนต์ FallBack ทั้งหมดจากช่วงที่ระบุในรายการ.

```
// สร้างกฎที่มีรายการฟอนต์.
 IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
 // รับชื่อฟอนต์สองตัวสุดท้ายเป็นอาร์เรย์.
 String[] fontNames = newRule.toArray(2, 2);
```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| startIndex | int | Index ของฟอนต์แรกที่จะเพิ่ม. |
| count | int | จำนวนฟอนต์ที่จะเพิ่ม. |

**คืนค่า:**
java.lang.String[] - Array of String
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public final int indexOf(String fontName)
```

คืนค่า index ของกฎที่ระบุในคอลเลกชัน.

--------------------

> ```
> // สร้างกฎที่มีรายการฟอนต์.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // รับตำแหน่งของ Tahoma.
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fontName | java.lang.String | ชื่อฟอนต์ที่ต้องการค้นหา. |

**คืนค่า:**
int - Index of a font or -1 if font not found in list.