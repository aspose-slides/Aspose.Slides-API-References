---
title: FontFallBackRule
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงกฎการสำรองแบบอักษร
type: docs
url: /th/com.aspose.slides/fontfallbackrule/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)  
```
public class FontFallBackRule implements IFontFallBackRule
```

แสดงกฎการสำรองแบบอักษร
## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [FontFallBackRule(long startIndex, long endIndex, String fontNames)](#FontFallBackRule-long-long-java.lang.String-) | สร้างอินสแตนซ์ใหม่. |
| [FontFallBackRule(long startIndex, long endIndex, String[] fontNames)](#FontFallBackRule-long-long-java.lang.String---) | สร้างอินสแตนซ์ใหม่. |
## วิธีการ

| วิธีการ | คำอธิบาย |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | เพิ่มแบบอักษรใหม่(s) ลงในรายการแบบอักษรสำรอง. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | เพิ่มแบบอักษรใหม่ลงในรายการแบบอักษรสำรอง. |
| [getRangeStartIndex()](#getRangeStartIndex--) | รับดัชนีแรกของช่วงยูนิโค้ดต่อเนื่อง. |
| [setRangeStartIndex(long value)](#setRangeStartIndex-long-) | รับดัชนีแรกของช่วงยูนิโค้ดต่อเนื่อง. |
| [getRangeEndIndex()](#getRangeEndIndex--) | รับดัชนีสุดท้ายของช่วงยูนิโค้ดต่อเนื่อง. |
| [setRangeEndIndex(long value)](#setRangeEndIndex-long-) | รับดัชนีสุดท้ายของช่วงยูนิโค้ดต่อเนื่อง. |
| [getCount()](#getCount--) | รับจำนวนแบบอักษรที่กำหนดจริงสำหรับช่วง. |
| [get_Item(int index)](#get-Item-int-) | รับชื่อแบบอักษรที่ตำแหน่งที่ระบุ. |
| [clear()](#clear--) | ลบแบบอักษรทั้งหมดออกจากรายการ. |
| [remove(String fontName)](#remove-java.lang.String-) | ลบการพบครั้งแรกของแบบอักษรสำรองที่ระบุออกจากรายการ. |
| [removeAt(int index)](#removeAt-int-) | ลบแบบอักษรสำรองที่ตำแหน่งที่ระบุในรายการ. |
| [toArray()](#toArray--) | สร้างและคืนอาเรย์ที่มีแบบอักษรสำรองทั้งหมดสำหรับกฎนี้. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | สร้างและคืนอาเรย์ที่มีแบบอักษรสำรองทั้งหมดจากช่วงที่ระบุในรายการ. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | คืนดัชนีของกฎที่ระบุในคอลเลกชัน. |
### FontFallBackRule(long startIndex, long endIndex, String fontNames) {#FontFallBackRule-long-long-java.lang.String-}
```
public FontFallBackRule(long startIndex, long endIndex, String fontNames)
```

สร้างอินสแตนซ์ใหม่.

--------------------

> ```
> // สร้างอินสแตนซ์ใหม่ของ FantFallBackRule ด้วยแบบอักษรหนึ่งตัว.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  // สร้างอินสแตนซ์ใหม่ของ FantFallBackRule ด้วยแบบอักษรหลายตัว.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma");
```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| startIndex | long | ดัชนีเริ่มต้นของช่วงยูนิโค้ด |
| endIndex | long | ดัชนีสุดท้ายของช่วงยูนิโค้ด |
| fontNames | java.lang.String | ชื่อหรือชื่อหลาย ๆ แบบอักษร (คั่นด้วยเครื่องหมายจุลภาค) สำหรับแบบอักษรสำรอง |

### FontFallBackRule(long startIndex, long endIndex, String[] fontNames) {#FontFallBackRule-long-long-java.lang.String---}
```
public FontFallBackRule(long startIndex, long endIndex, String[] fontNames)
```

สร้างอินสแตนซ์ใหม่.

--------------------

> ```
> // สร้างอินสแตนซ์ใหม่ของ FantFallBackRule ด้วยแบบอักษรสองตัว
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Mincho", "MS Gothic"});
>  // สร้างอินสแตนซ์ใหม่ของ FantFallBackRule ด้วยแบบอักษรหลายตัว.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Gothic", "Tahoma, Times New Roman" });
```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| startIndex | long | ดัชนีเริ่มต้นของช่วงยูนิโค้ด |
| endIndex | long | ดัชนีสุดท้ายของช่วงยูนิโค้ด |
| fontNames | java.lang.String[] | ชื่อหรือชื่อหลาย ๆ แบบอักษร (คั่นด้วยเครื่องหมายจุลภาค) สำหรับแบบอักษรสำรอง |

### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public final void addFallBackFonts(String fontName)
```

เพิ่มแบบอักษรใหม่(s) ลงในรายการแบบอักษรสำรอง.

--------------------

> ```
> // สร้างอินสแตนซ์ใหม่ของ FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //เพิ่มแบบอักษรตัวที่สองลงในกฎ 
>  newRule.addFallBackFonts("MS Gothic");
>  //เพิ่มแบบอักษรตัวที่สามและสี่ลงในกฎ 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| fontName | java.lang.String | ชื่อหรือชื่อหลาย ๆ แบบอักษร (คั่นด้วยเครื่องหมายจุลภาค) สำหรับแบบอักษรสำรอง |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public final void addFallBackFonts(String[] fontNames)
```

เพิ่มแบบอักษรใหม่ลงในรายการแบบอักษรสำรอง.

--------------------

> ```
> //สร้างอินสแตนซ์ใหม่ของ FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //เพิ่มแบบอักษรอีกสามตัวลงในกฎ 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| fontNames | java.lang.String[] | ชื่อหรือชื่อหลาย ๆ แบบอักษร (คั่นด้วยเครื่องหมายจุลภาค) สำหรับแบบอักษรสำรอง |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public final long getRangeStartIndex()
```

รับดัชนีแรกของช่วงยูนิโค้ดต่อเนื่อง.

**คืนค่า:**
long
### setRangeStartIndex(long value) {#setRangeStartIndex-long-}
```
public final void setRangeStartIndex(long value)
```

รับดัชนีแรกของช่วงยูนิโค้ดต่อเนื่อง.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | long |  |

### getRangeEndIndex() {#getRangeEndIndex--}
```
public final long getRangeEndIndex()
```

รับดัชนีสุดท้ายของช่วงยูนิโค้ดต่อเนื่อง.

**คืนค่า:**
long
### setRangeEndIndex(long value) {#setRangeEndIndex-long-}
```
public final void setRangeEndIndex(long value)
```

รับดัชนีสุดท้ายของช่วงยูนิโค้ดต่อเนื่อง.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | long |  |

### getCount() {#getCount--}
```
public final int getCount()
```

รับจำนวนแบบอักษรที่กำหนดจริงสำหรับช่วง. อ่านอย่างเดียว int.

**คืนค่า:**
int
### get_Item(int index) {#get-Item-int-}
```
public final String get_Item(int index)
```

รับชื่อแบบอักษรที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**
java.lang.String
### clear() {#clear--}
```
public final void clear()
```

ลบแบบอักษรทั้งหมดออกจากรายการ.

### remove(String fontName) {#remove-java.lang.String-}
```
public final void remove(String fontName)
```

ลบการพบครั้งแรกของแบบอักษรสำรองที่ระบุออกจากรายการ.

--------------------

> ```
> // สร้างกฎที่มีรายการแบบอักษร.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // ลบ Tahoma ออกจากรายการ.
>  newRule.remove("Tahoma");
```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| fontName | java.lang.String | ชื่อแบบอักษรที่ต้องการลบจากรายการ. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

ลบแบบอักษรสำรองที่ตำแหน่งที่ระบุในรายการ.

--------------------

> ```
> // สร้างกฎที่มีรายการแบบอักษร.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //กำลังลบ Tahoma จากรายการ.
>  newRule.remove(2);
```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีเริ่มต้นจากศูนย์ของแบบอักษรที่ต้องการลบ. |

### toArray() {#toArray--}
```
public final String[] toArray()
```

สร้างและคืนอาเรย์ที่มีแบบอักษรสำรองทั้งหมดสำหรับกฎนี้.

--------------------

> ```
> // สร้างกฎที่มีรายการแบบอักษร.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // รับชื่อแบบอักษรทั้งหมดเป็นอาเรย์.
>  String[] fontNames = newRule.toArray();
> ```

**คืนค่า:**
java.lang.String[] - Array of String
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final String[] toArray(int startIndex, int count)
```

สร้างและคืนอาเรย์ที่มีแบบอักษรสำรองทั้งหมดจากช่วงที่ระบุในรายการ.

```
// สร้างกฎที่มีรายการแบบอักษร.
 IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
 // รับชื่อแบบอักษรสองตัวสุดท้ายเป็นอาเรย์.
 String[] fontNames = newRule.toArray(2, 2);
```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| startIndex | int | ดัชนีของแบบอักษรแรกที่ต้องการเพิ่ม. |
| count | int | จำนวนแบบอักษรที่ต้องการเพิ่ม. |

**คืนค่า:**
java.lang.String[] - Array of String
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public final int indexOf(String fontName)
```

คืนดัชนีของกฎที่ระบุในคอลเลกชัน.

--------------------

> ```
> // สร้างกฎที่มีรายการแบบอักษร.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // รับดัชนีของ Tahoma.
>  int tahomaIndex = newRule.indexOf("Tahoma");
```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| fontName | java.lang.String | ชื่อแบบอักษรที่ต้องการค้นหา. |

**คืนค่า:**
int - Index of a font or -1 if font not found in list.