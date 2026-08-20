---
title: IParagraphCollection
second_title: Aspose.Slides สำหรับ Java API Reference
description: เป็นตัวแทนของคอลเลกชันของย่อหน้า
type: docs
url: /th/com.aspose.slides/iparagraphcollection/
---
**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraphCollection extends System.Collections.Generic.IGenericEnumerable<IParagraph>, ISlideComponent
```

เป็นตัวแทนของคอลเลกชันของย่อหน้า.
## วิธีการ

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ดึงองค์ประกอบที่ตำแหน่งที่ระบุ |
| [getCount()](#getCount--) | รับจำนวนขององค์ประกอบที่มีอยู่จริงในคอลเลกชัน |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | เพิ่ม Paragraph ไปยังส่วนท้ายของคอลเลกชัน |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | เพิ่มเนื้อหาของ ParagraphCollection ไปยังส่วนท้ายของคอลเลกชัน |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | แทรก Paragraph ลงในคอลเลกชันที่ตำแหน่งที่ระบุ |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | แทรกเนื้อหาของ ParagraphCollection ลงในคอลเลกชันที่ตำแหน่งที่ระบุ |
| [clear()](#clear--) | ลบทุกองค์ประกอบออกจากคอลเลกชัน |
| [removeAt(int index)](#removeAt-int-) | ลบองค์ประกอบที่ตำแหน่งที่ระบุในคอลเลกชัน |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | ลบการพบครั้งแรกของย่อหน้าที่กำหนด |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | เพิ่มข้อความจากสตริง HTML ที่ระบุไปยังคอลเลกชัน |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | เพิ่มข้อความจากสตริง HTML ที่ระบุไปยังคอลเลกชัน |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | แปลงย่อหน้าที่ระบุเป็น HTML และส่งคืนเป็นอ็อบเจกต์ String |
### get_Item(int index) {#get-Item-int-}
```
public abstract IParagraph get_Item(int index)
```


ดึงองค์ประกอบที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**ผลลัพธ์:**
[IParagraph](../../com.aspose.slides/iparagraph)
### getCount() {#getCount--}
```
public abstract int getCount()
```


รับจำนวนขององค์ประกอบที่มีอยู่จริงในคอลเลกชัน. อ่านอย่างเดียว int.

**ผลลัพธ์:**
int
### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public abstract void add(IParagraph value)
```


เพิ่ม Paragraph ไปยังส่วนท้ายของคอลเลกชัน

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph ที่จะถูกเพิ่มไปยังส่วนท้ายของคอลเลกชัน |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public abstract int add(IParagraphCollection value)
```


เพิ่มเนื้อหาของ ParagraphCollection ไปยังส่วนท้ายของคอลเลกชัน

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | ParagraphCollection ที่จะถูกเพิ่มไปยังส่วนท้ายของคอลเลกชัน |

**ผลลัพธ์:**
int - ดัชนีที่ Paragraph ถูกเพิ่ม หรือ -1 หากไม่มีสิ่งใดให้เพิ่ม
### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public abstract void insert(int index, IParagraph value)
```


แทรก Paragraph ลงในคอลเลกชันที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีที่เริ่มจากศูนย์ที่ Paragraph ควรแทรก |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph ที่จะทำการแทรก |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public abstract void insert(int index, IParagraphCollection value)
```


แทรกเนื้อหาของ ParagraphCollection ลงในคอลเลกชันที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีที่เริ่มจากศูนย์ที่ย่อหน้าจะถูกแทรก |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | ย่อหน้าที่จะทำการแทรก |

### clear() {#clear--}
```
public abstract void clear()
```


ลบทุกองค์ประกอบออกจากคอลเลกชัน

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


ลบองค์ประกอบที่ตำแหน่งที่ระบุในคอลเลกชัน

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีที่เริ่มจากศูนย์ขององค์ประกอบที่ต้องการลบ |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public abstract boolean remove(IParagraph item)
```


ลบการเกิดครั้งแรกของย่อหน้าที่กำหนด

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | ย่อหน้าที่จะลบออกจากคอลเลกชัน |

**ผลลัพธ์:**
boolean - true หาก item ถูกลบสำเร็จ; มิฉะนั้น false.
### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public abstract void addFromHtml(String text)
```


เพิ่มข้อความจากสตริง HTML ที่ระบุไปยังคอลเลกชัน

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | ข้อความ HTML |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```


เพิ่มข้อความจากสตริง HTML ที่ระบุไปยังคอลเลกชัน

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | ข้อความ HTML |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | อ็อบเจกต์ callback Resolver ที่ทำการแก้ไข URI และดึงอ็อบเจกต์ที่อ้างอิง |
| uri | java.lang.String | URI สำหรับการเพิ่มเอกสาร HTML. ใช้สำหรับแก้ไขลิงก์สัมพัทธ์ |

---

การระบุ resolver อาจทำให้เกิดช่องโหว่าได้. ใช้ด้วยความระมัดระวัง.

### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public abstract String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```


แปลงย่อหน้าที่ระบุเป็น HTML และส่งคืนเป็นอ็อบเจกต์ String

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| firstParagraphIndex | int | ดัชนีย่อหน้าแรก int |
| paragraphsCount | int | จำนวนย่อหน้า int |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | ตัวเลือกการแปลง [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**ผลลัพธ์:**
java.lang.String - HTML ที่สร้างขึ้น