---
title: IParagraphCollection
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แทนคอลเลกชันของย่อหน้า.
type: docs
url: /th/com.aspose.slides/iparagraphcollection/
---
**อินเทอร์เฟซที่ทำทั้งหมด:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraphCollection extends System.Collections.Generic.IGenericEnumerable<IParagraph>, ISlideComponent
```

แสดงคอลเลกชันของย่อหน้า.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ดึงเอาองค์ประกอบที่ตำแหน่งที่ระบุ |
| [getCount()](#getCount--) | ดึงจำนวนขององค์ประกอบที่มีอยู่จริงในคอลเลกชัน |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | เพิ่ม Paragraph ไปยังส่วนท้ายของคอลเลกชัน |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | เพิ่มเนื้อหาของ ParagraphCollection ไปยังส่วนท้ายของคอลเลกชัน |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | แทรก Paragraph เข้าสู่คอลเลกชันที่ตำแหน่งที่ระบุ |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | แทรกเนื้อหาของ ParagraphCollection เข้าสู่คอลเลกชันที่ตำแหน่งที่ระบุ |
| [clear()](#clear--) | ลบทุกองค์ประกอบจากคอลเลกชัน |
| [removeAt(int index)](#removeAt-int-) | ลบองค์ประกอบที่ตำแหน่งที่ระบุในคอลเลกชัน |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | ลบการปรากฏครั้งแรกของย่อหน้าที่ระบุ |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | เพิ่มข้อความจากสตริง html ที่ระบุไปยังคอลเลกชัน |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | เพิ่มข้อความจากสตริง html ที่ระบุไปยังคอลเลกชัน |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | แปลงย่อหน้าที่ระบุเป็น HTML และส่งคืนเป็นอ็อบเจ็กต์ String |

### get_Item(int index) {#get-Item-int-}
```
public abstract IParagraph get_Item(int index)
```

ดึงเอาองค์ประกอบที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ผลลัพธ์:**
[IParagraph](../../com.aspose.slides/iparagraph)

### getCount() {#getCount--}
```
public abstract int getCount()
```

ดึงจำนวนขององค์ประกอบที่มีอยู่จริงในคอลเลกชัน. int แบบอ่านอย่างเดียว

**ผลลัพธ์:**
int

### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public abstract void add(IParagraph value)
```

เพิ่ม Paragraph ไปยังส่วนท้ายของคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph ที่จะถูกเพิ่มไปยังส่วนท้ายของคอลเลกชัน |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public abstract int add(IParagraphCollection value)
```

เพิ่มเนื้อหาของ ParagraphCollection ไปยังส่วนท้ายของคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | ParagraphCollection ที่จะถูกเพิ่มไปยังส่วนท้ายของคอลเลกชัน |

**ผลลัพธ์:**
int - ดัชนีที่ Paragraph ถูกเพิ่ม หรือ -1 หากไม่มีอะไรให้เพิ่ม

### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public abstract void insert(int index, IParagraph value)
```

แทรก Paragraph เข้าสู่คอลเลกชันที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีฐานศูนย์ที่ Paragraph ควรจะแทรก |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph ที่จะทำการแทรก |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public abstract void insert(int index, IParagraphCollection value)
```

แทรกเนื้อหของ ParagraphCollection เข้าสู่คอลเลกชันที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีฐานศูนย์ที่ย่อหน้าควรจะแทรก |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | ย่อหน้าที่จะทำการแทรก |

### clear() {#clear--}
```
public abstract void clear()
```

ลบทุกองค์ประกอบจากคอลเลกชัน

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

ลบองค์ประกอบที่ตำแหน่งที่ระบุในคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีฐานศูนย์ขององค์ประกอบที่ต้องการลบ |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public abstract boolean remove(IParagraph item)
```

ลบการปรากฏครั้งแรกของย่อหน้าที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | ย่อหน้าที่จะลบออกจากคอลเลกชัน |

**ผลลัพธ์:**
boolean - true หากรายการถูกลบสำเร็จ; มิฉะนั้น false.

### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public abstract void addFromHtml(String text)
```

เพิ่มข้อความจากสตริง html ที่ระบุไปยังคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความ HTML |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```

เพิ่มข้อความจากสตริง html ที่ระบุไปยังคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความ HTML |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | อ็อบเจ็กต์ callback resolver ที่ทำการ resolve URI และดึงอ็อบเจ็กต์ที่อ้างอิง |
| uri | java.lang.String | URI สำหรับเพิ่มเอกสาร HTML. ใช้สำหรับ resolve ลิงก์สัมพันธ์ |

การระบุ resolver อาจทำให้เกิดช่องโหว่. ใช้ด้วยความระมัดระวัง.

--------------------

### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public abstract String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```

แปลงย่อหน้าที่ระบุเป็น HTML และส่งคืนเป็นอ็อบเจ็กต์ String

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| firstParagraphIndex | int | ดัชนีย่อหน้าตัวแรก |
| paragraphsCount | int | จำนวนย่อหน้า |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | ตัวเลือกการแปลง [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**ผลลัพธ์:**
java.lang.String - HTML ที่สร้างขึ้น