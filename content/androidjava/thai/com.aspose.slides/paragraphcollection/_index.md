---
title: ParagraphCollection
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: เป็นคอลเลกชันของพารากราฟ
type: docs
url: /th/com.aspose.slides/paragraphcollection/
---
**การสืบทอด:**  
java.lang.Object, com.aspose.slides.DomObject

**อินเทอร์เฟซที่ทำการดำเนินการทั้งหมด:**  
[com.aspose.slides.IParagraphCollection](../../com.aspose.slides/iparagraphcollection)  
```
public final class ParagraphCollection extends DomObject<TextFrame> implements IParagraphCollection
```

Represents a collection of a paragraphs.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getCount()](#getCount--) | รับจำนวนขององค์ประกอบที่อยู่จริงในคอลเลกชัน. |
| [isReadOnly()](#isReadOnly--) | รับค่าบ่งบอกว่า [IGenericCollection](../../com.aspose.slides/igenericcollection) เป็นแบบอ่านอย่างเดียวหรือไม่. |
| [get_Item(int index)](#get-Item-int-) | รับองค์ประกอบที่ตำแหน่งที่ระบุ. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | เพิ่ม Paragraph ไปยังท้ายของคอลเลกชัน. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | เพิ่มเนื้อหาของ ParagraphCollection ไปยังท้ายของคอลเลกชัน. |
| [indexOf(IParagraph item)](#indexOf-com.aspose.slides.IParagraph-) | กำหนดดัชนีของรายการที่ระบุใน List. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | แทรก Paragraph ลงในคอลเลกชันที่ตำแหน่งที่ระบุ. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | แทรกเนื้อหาของ ParagraphCollection ลงในคอลเลกชันที่ตำแหน่งที่ระบุ. |
| [clear()](#clear--) | ลบองค์ประกอบทั้งหมดจากคอลเลกชัน. |
| [contains(IParagraph item)](#contains-com.aspose.slides.IParagraph-) | กำหนดว่า [IGenericCollection](../../com.aspose.slides/igenericcollection) มีค่าที่ระบุหรือไม่. |
| [copyTo(IParagraph[] array, int arrayIndex)](#copyTo-com.aspose.slides.IParagraph---int-) | คัดลอกองค์ประกอบของ [IGenericCollection](../../com.aspose.slides/igenericcollection) ไปยัง Array เริ่มจากตำแหน่ง Array ที่ระบุ. |
| [removeAt(int index)](#removeAt-int-) | ลบองค์ประกอบที่ตำแหน่งที่ระบุในคอลเลกชัน. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | ลบการปรากฏครั้งแรกของอ็อบเจ็กต์ที่ระบุจาก [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [iterator()](#iterator--) | คืนค่า enumerator ที่วนรอบคอลเลกชัน. |
| [iteratorJava()](#iteratorJava--) | คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด. |
| [getSlide()](#getSlide--) | คืนค่า slide พาเรนท์ของคอลเลกชันพารากราฟ. |
| [getPresentation()](#getPresentation--) | คืนค่า presentation พาเรนท์ของคอลเลกชันพารากราฟ. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | เพิ่มข้อความจากสตริง html ที่ระบุไปยังคอลเลกชัน. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | เพิ่มข้อความจากสตริง html ที่ระบุไปยังคอลเลกชัน. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | แปลงพารากราฟที่ระบุเป็น HTML และคืนค่าเป็นอ็อบเจ็กต์ String. |

### getCount() {#getCount--}
```
public final int getCount()
```

รับจำนวนขององค์ประกอบที่อยู่จริงในคอลเลกชัน. อ่านอย่างเดียว int.

**คืนค่า:**  
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

รับค่าบ่งบอกว่า [IGenericCollection](../../com.aspose.slides/igenericcollection) เป็นแบบอ่านอย่างเดียวหรือไม่. อ่านอย่างเดียว boolean.

**คืนค่า:**  
boolean - true ถ้า [IGenericCollection](../../com.aspose.slides/igenericcollection) เป็นแบบอ่านอย่างเดียว; มิฉะนั้น false.

### get_Item(int index) {#get-Item-int-}
```
public final IParagraph get_Item(int index)
```

รับองค์ประกอบที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**  
[IParagraph](../../com.aspose.slides/iparagraph)

### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public final void add(IParagraph value)
```

เพิ่ม Paragraph ไปยังท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph ที่จะเพิ่มไปยังท้ายของคอลเลกชัน. |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public final int add(IParagraphCollection value)
```

เพิ่มเนื้อหาของ ParagraphCollection ไปยังท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | ParagraphCollection ที่จะเพิ่มไปยังท้ายของคอลเลกชัน. |

**คืนค่า:**  
int - ดัชนีที่ Paragraph ถูกเพิ่ม หรือ -1 หากไม่มีอะไรจะเพิ่ม.

### indexOf(IParagraph item) {#indexOf-com.aspose.slides.IParagraph-}
```
public final int indexOf(IParagraph item)
```

กำหนดดัชนีของรายการที่ระบุใน List.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | อ็อบเจ็กต์เพื่อค้นหาใน List. |

**คืนค่า:**  
int - ดัชนีของ item หากพบในรายการ; มิฉะนั้น -1.

### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public final void insert(int index, IParagraph value)
```

แทรก Paragraph ลงในคอลเลกชันที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีเริ่มจากศูนย์ที่ Paragraph ควรแทรก. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph ที่จะแทรก. |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public final void insert(int index, IParagraphCollection value)
```

แทรกเนื้อหาของ ParagraphCollection ลงในคอลเลกชันที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีเริ่มจากศูนย์ที่ paragraphs ควรแทรก. |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | paragraphs ที่จะแทรก. |

### clear() {#clear--}
```
public final void clear()
```

ลบองค์ประกอบทั้งหมดจากคอลเลกชัน.

### contains(IParagraph item) {#contains-com.aspose.slides.IParagraph-}
```
public final boolean contains(IParagraph item)
```

กำหนดว่า [IGenericCollection](../../com.aspose.slides/igenericcollection) มีค่าที่ระบุหรือไม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | อ็อบเจ็กต์เพื่อค้นหาใน [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**คืนค่า:**  
boolean - true หากพบ item ใน [IGenericCollection](../../com.aspose.slides/igenericcollection); มิฉะนั้น false.

### copyTo(IParagraph[] array, int arrayIndex) {#copyTo-com.aspose.slides.IParagraph---int-}
```
public final void copyTo(IParagraph[] array, int arrayIndex)
```

คัดลอกองค์ประกอบของ [IGenericCollection](../../com.aspose.slides/igenericcollection) ไปยัง Array เริ่มจากตำแหน่ง Array ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | [IParagraph\[\]](../../com.aspose.slides/iparagraph) | Array หนึ่งมิติที่เป็นปลายทางขององค์ประกอบที่คัดลอกจาก [IGenericCollection](../../com.aspose.slides/igenericcollection). Array ต้องมีการจัดทำดัชนีเริ่มจากศูนย์. |
| arrayIndex | int | ดัชนีเริ่มจากศูนย์ใน array ที่เริ่มคัดลอก. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

ลบองค์ประกอบที่ตำแหน่งที่ระบุในคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีเริ่มจากศูนย์ขององค์ประกอบที่จะลบ. |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public final boolean remove(IParagraph item)
```

ลบการปรากฏครั้งแรกของอ็อบเจ็กต์ที่ระบุจาก [IGenericCollection](../../com.aspose.slides/igenericcollection).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | อ็อบเจ็กต์ที่จะลบจาก [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**คืนค่า:**  
boolean - true หาก item ถูกลบสำเร็จจาก [IGenericCollection](../../com.aspose.slides/igenericcollection); มิฉะนั้น false. วิธีนี้ยังคืนค่า false หากไม่พบ item ใน [IGenericCollection](../../com.aspose.slides/igenericcollection) ดั้งเดิม.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iterator()
```

คืนค่า enumerator ที่วนรอบคอลเลกชัน.

**คืนค่า:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - IGenericEnumerator ที่สามารถใช้เพื่อวนรอบคอลเลกชัน.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iteratorJava()
```

คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด.

**คืนค่า:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด.

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

คืนค่า slide พาเรนท์ของคอลเลกชันพารากราฟ. อ่านอย่างเดียว [BaseSlide](../../com.aspose.slides/baseslide).

**คืนค่า:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

คืนค่า presentation พาเรนท์ของคอลเลกชันพารากราฟ. อ่านอย่างเดียว [IPresentation](../../com.aspose.slides/ipresentation).

**คืนค่า:**  
[IPresentation](../../com.aspose.slides/ipresentation)

### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public final void addFromHtml(String text)
```

เพิ่มข้อความจากสตริง html ที่ระบุไปยังคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความ HTML. |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```

เพิ่มข้อความจากสตริง html ที่ระบุไปยังคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | java.lang.String | ข้อความ HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | อ็อบเจ็กต์ callback Resolver ที่ทำการแก้ไข URI และดึงอ็อบเจ็กต์ที่อ้างอิง. |
| uri | java.lang.String | URI สำหรับเพิ่มเอกสาร HTML ใช้สำหรับแก้ไขลิงก์สัมพันธ์. |

--------------------

การระบุ resolver อาจทำให้เกิดช่องโหว่ได้ ใช้งานด้วยความระมัดระวัง.

### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public final String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```

แปลงพารากราฟที่ระบุเป็น HTML และคืนค่าเป็นอ็อบเจ็กต์ String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| firstParagraphIndex | int | ดัชนีพารากราฟแรก int |
| paragraphsCount | int | จำนวนพารากราฟ int |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | ตัวเลือกการแปลง [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**คืนค่า:**  
java.lang.String - HTML ที่สร้าง.