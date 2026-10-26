---
title: DocumentProperties
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงคุณสมบัติของการนำเสนอ
type: docs
url: /th/com.aspose.slides/documentproperties/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ใช้งานทั้งหมด:**
[com.aspose.slides.IDocumentProperties](../../com.aspose.slides/idocumentproperties), com.aspose.slides.IGenericCloneable, java.lang.Cloneable
```
public class DocumentProperties implements IDocumentProperties, IGenericCloneable<IDocumentProperties>, Cloneable
```

แสดงคุณสมบัติของการนำเสนอ.

--------------------

> ```
> The following example shows how to access built-in Properties of PowerPoint Presentation.
>  
>  // สร้างอินสแตนซ์ของคลาส Presentation ที่เป็นตัวแทนของการนำเสนอ
>  Presentation pres = new Presentation("AccessBuiltin Properties.pptx");
>  try {
>      // สร้างอ้างอิงไปยังอ็อบเจ็กต์ IDocumentProperties ที่เชื่อมโยงกับ Presentation
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // แสดงคุณสมบัติในตัว
>      System.out.println("Category : " + documentProperties.getCategory());
>      System.out.println("Current Status : " + documentProperties.getContentStatus());
>      System.out.println("Creation Date : " + documentProperties.getCreatedTime());
>      System.out.println("Author : " + documentProperties.getAuthor());
>      System.out.println("Description : " + documentProperties.getComments());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to modify built-in Properties of PowerPoint Presentation.
>  
>  // สร้างอินสแตนซ์ของคลาส Presentation ที่เป็นตัวแทนของการนำเสนอ
>  Presentation pres = new Presentation("ModifyBuiltinProperties.pptx");
>  try {
>      // สร้างอ้างอิงไปยังอ็อบเจ็กต์ IDocumentProperties ที่เชื่อมโยงกับ Presentation
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // ตั้งค่าคุณสมบัติในตัว
>      documentProperties.setAuthor("Aspose.Slides for Java");
>      documentProperties.setTitle("Modifying Presentation Properties");
>      documentProperties.setSubject("Aspose Subject");
>      // บันทึกการนำเสนอของคุณลงไฟล์
>      pres.save("DocumentProperties_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## ตัวสร้าง

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [DocumentProperties()](#DocumentProperties--) | สร้างอินสแตนซ์ใหม่ของคลาส [DocumentProperties](../../com.aspose.slides/documentproperties). |
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | คืนค่าเวอร์ชันของแอป. |
| [getNameOfApplication()](#getNameOfApplication--) | คืนค่า หรือ กำหนดชื่อของแอปพลิเคชัน. |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | คืนค่า หรือ กำหนดชื่อของแอปพลิเคชัน. |
| [getCompany()](#getCompany--) | คืนค่า หรือ กำหนดคุณสมบัติบริษัท. |
| [setCompany(String value)](#setCompany-java.lang.String-) | คืนค่า หรือ กำหนดคุณสมบัติบริษัท. |
| [getManager()](#getManager--) | คืนค่า หรือ กำหนดผู้จัดการ. |
| [setManager(String value)](#setManager-java.lang.String-) | คืนค่า หรือ กำหนดผู้จัดการ. |
| [getPresentationFormat()](#getPresentationFormat--) | คืนค่า หรือ กำหนดรูปแบบที่ตั้งใจของการนำเสนอ. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | คืนค่า หรือ กำหนดรูปแบบที่ตั้งใจของการนำเสนอ. |
| [getSharedDoc()](#getSharedDoc--) | ตรวจสอบว่าการนำเสนอถูกแชร์ระหว่างหลายคนหรือไม่. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | ตรวจสอบว่าการนำเสนอถูกแชร์ระหว่างหลายคนหรือไม่. |
| [getApplicationTemplate()](#getApplicationTemplate--) | คืนค่า หรือ กำหนดแม่แบบของแอปพลิเคชัน. |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | คืนค่า หรือ กำหนดแม่แบบของแอปพลิเคชัน. |
| [getTotalEditingTime()](#getTotalEditingTime--) | เวลาการแก้ไขทั้งหมดของการนำเสนอ. |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | เวลาการแก้ไขทั้งหมดของการนำเสนอ. |
| [getTitle()](#getTitle--) | คืนค่า หรือ กำหนดชื่อเรื่องของการนำเสนอ. |
| [setTitle(String value)](#setTitle-java.lang.String-) | คืนค่า หรือ กำหนดชื่อเรื่องของการนำเสนอ. |
| [getSubject()](#getSubject--) | คืนค่า หรือ กำหนดหัวเรื่องของการนำเสนอ. |
| [setSubject(String value)](#setSubject-java.lang.String-) | คืนค่า หรือ กำหนดหัวเรื่องของการนำเสนอ. |
| [getAuthor()](#getAuthor--) | คืนค่า หรือ กำหนดผู้เขียนของการนำเสนอ. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | คืนค่า หรือ กำหนดผู้เขียนของการนำเสนอ. |
| [getKeywords()](#getKeywords--) | คืนค่า หรือ กำหนดคำสำคัญของการนำเสนอ. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | คืนค่า หรือ กำหนดคำสำคัญของการนำเสนอ. |
| [getComments()](#getComments--) | คืนค่า หรือ กำหนดความคิดเห็นของการนำเสนอ. |
| [setComments(String value)](#setComments-java.lang.String-) | คืนค่า หรือ กำหนดความคิดเห็นของการนำเสนอ. |
| [getCategory()](#getCategory--) | คืนค่า หรือ กำหนดประเภทของการนำเสนอ. |
| [setCategory(String value)](#setCategory-java.lang.String-) | คืนค่า หรือ กำหนดประเภทของการนำเสนอ. |
| [getCreatedTime()](#getCreatedTime--) | คืนค่าวันที่ที่การนำเสนอถูกสร้าง. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | คืนค่าวันที่ที่การนำเสนอถูกสร้าง. |
| [getLastSavedTime()](#getLastSavedTime--) | คืนค่าวันที่ที่การนำเสนอถูกแก้ไขครั้งสุดท้าย. |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | คืนค่าวันที่ที่การนำเสนอถูกแก้ไขครั้งสุดท้าย. |
| [getLastPrinted()](#getLastPrinted--) | คืนค่าวันที่การนำเสนอถูกพิมพ์ครั้งสุดท้าย. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | คืนค่าวันที่การนำเสนอถูกพิมพ์ครั้งสุดท้าย. |
| [getLastSavedBy()](#getLastSavedBy--) | คืนค่า หรือ กำหนดชื่อของบุคคลสุดท้ายที่แก้ไขการนำเสนอ. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | คืนค่า หรือ กำหนดชื่อของบุคคลสุดท้ายที่แก้ไขการนำเสนอ. |
| [getRevisionNumber()](#getRevisionNumber--) | คืนค่า หรือ กำหนดหมายเลขการแก้ไขของการนำเสนอ. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | คืนค่า หรือ กำหนดหมายเลขการแก้ไขของการนำเสนอ. |
| [getContentStatus()](#getContentStatus--) | คืนค่า หรือ กำหนดสถานะเนื้อหาของการนำเสนอ. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | คืนค่า หรือ กำหนดสถานะเนื้อหาของการนำเสนอ. |
| [getContentType()](#getContentType--) | คืนค่า หรือ กำหนดประเภทเนื้อหาของการนำเสนอ. |
| [setContentType(String value)](#setContentType-java.lang.String-) | คืนค่า หรือ กำหนดประเภทเนื้อหาของการนำเสนอ. |
| [getHyperlinkBase()](#getHyperlinkBase--) | คืนค่า หรือ กำหนดคุณสมบัติเอกสาร HyperlinkBase. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | คืนค่า หรือ กำหนดคุณสมบัติเอกสาร HyperlinkBase. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | คืนค่าจำนวนคุณสมบัติกำหนดเองที่มีอยู่ในคอลเลกชัน. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | คืนชื่อคุณสมบัติกำหนดเองที่ตำแหน่งที่ระบุ. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | ลบคุณสมบัติกำหนดเองที่เชื่อมโยงกับชื่อที่ระบุ. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | ตรวจสอบการมีอยู่ของคุณสมบัติกำหนดเองที่ชื่อที่ระบุ. |
| [get_Item(String name)](#get-Item-java.lang.String-) | คืนค่า หรือ กำหนดคุณสมบัติกำหนดเองที่เชื่อมโยงกับชื่อที่ระบุ. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | คืนค่า หรือ กำหนดคุณสมบัติกำหนดเองที่เชื่อมโยงกับชื่อที่ระบุ. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | ดึงค่าบูลีนที่มีชื่อจากคุณสมบัติกำหนดเอง. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | ดึงค่าจำนวนเต็มที่มีชื่อจากคุณสมบัติกำหนดเอง. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | ดึงค่า DateTime ที่มีชื่อจากคุณสมบัติกำหนดเอง. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | ดึงค่าสตริงที่มีชื่อจากคุณสมบัติกำหนดเอง. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | ดึงค่าจำนวนทศนิยม (float) ที่มีชื่อจากคุณสมบัติกำหนดเอง. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | ดึงค่าจำนวนทศนิยม (double) ที่มีชื่อจากคุณสมบัติกำหนดเอง. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | ตั้งค่าคุณสมบัติกำหนดเองแบบบูลีน. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | ตั้งค่าคุณสมบัติกำหนดเองแบบจำนวนเต็ม. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | ตั้งค่าคุณสมบัติกำหนดเองแบบ DateTime. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | ตั้งค่าคุณสมบัติกำหนดเองแบบสตริง. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | ตั้งค่าคุณสมบัติกำหนดเองแบบ float. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | ตั้งค่าคุณสมบัติกำหนดเองแบบ double. |
| [clearCustomProperties()](#clearCustomProperties--) | ลบคุณสมบัติกำหนดเองทั้งหมด. |
| [getSensitivityLabels()](#getSensitivityLabels--) | ดึงอาเรย์ของป้ายกำกับความไวจากคุณสมบัติเบื้องต้นของเอกสาร (Microsoft Information Protection SDK Metadata). |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | ล้างและตั้งค่าค่าตั้งต้นสำหรับคุณสมบัติ builtIn ทั้งหมด. |
| [getScaleCrop()](#getScaleCrop--) | ระบุโหมดการแสดงผลของรูปย่อเอกสาร. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | ระบุโหมดการแสดงผลของรูปย่อเอกสาร. |
| [getLinksUpToDate()](#getLinksUpToDate--) | ระบุว่าลิงก์ภายในเอกสารเป็นข้อมูลล่าสุดหรือไม่. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | ระบุว่าลิงก์ภายในเอกสารเป็นข้อมูลล่าสุดหรือไม่. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | ระบุว่าลิงก์หนึ่งหรือหลายลิงก์ในส่วนนี้ได้รับการอัปเดตเฉพาะในส่วนนี้โดยผู้ผลิต. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | ระบุว่าลิงก์หนึ่งหรือหลายลิงก์ในส่วนนี้ได้รับการอัปเดตเฉพาะในส่วนนี้โดยผู้ผลิต. |
| [getSlides()](#getSlides--) | คืนค่าจำนวนสไลด์ทั้งหมดในเอกสารการนำเสนอ. |
| [getHiddenSlides()](#getHiddenSlides--) | คืนค่าจำนวนสไลด์ที่ซ่อนอยู่ในเอกสารการนำเสนอ. |
| [getNotes()](#getNotes--) | คืนค่าจำนวนสไลด์ที่มีโน้ตในเอกสารการนำเสนอ. |
| [getParagraphs()](#getParagraphs--) | คืนค่าจำนวนพารากราฟทั้งหมดที่พบในเอกสาร (หากมี). |
| [getWords()](#getWords--) | คืนค่าจำนวนคำทั้งหมดที่อยู่ในเอกสาร. |
| [getMultimediaClips()](#getMultimediaClips--) | คืนค่าจำนวนคลิปเสียงหรือวิดีโอที่มีอยู่ในเอกสาร. |
| [getTitlesOfParts()](#getTitlesOfParts--) | ระบุชื่อของแต่ละส่วนเอกสาร. |
| [getHeadingPairs()](#getHeadingPairs--) | แสดงการจัดกลุ่มของส่วนเอกสารและจำนวนส่วนในแต่ละกลุ่ม. |
| [deepClone()](#deepClone--) | คล clones วัตถุปัจจุบัน |
| [cloneT()](#cloneT--) | คล clones วัตถุปัจจุบัน |
### DocumentProperties() {#DocumentProperties--}
```
public DocumentProperties()
```

สร้างอินสแตนซ์ใหม่ของคลาส [DocumentProperties](../../com.aspose.slides/documentproperties).

### getAppVersion() {#getAppVersion--}
```
public final String getAppVersion()
```

คืนค่าเวอร์ชันของแอป. อ่านอย่างเดียว String.

**คืนค่า:**
java.lang.String
### getNameOfApplication() {#getNameOfApplication--}
```
public final String getNameOfApplication()
```

คืนค่า หรือ กำหนดชื่อของแอปพลิเคชัน. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public final void setNameOfApplication(String value)
```

คืนค่า หรือ กำหนดชื่อของแอปพลิเคชัน. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getCompany() {#getCompany--}
```
public final String getCompany()
```

คืนค่า หรือ กำหนดคุณสมบัติบริษัท. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```

คืนค่า หรือ กำหนดคุณสมบัติบริษัท. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getManager() {#getManager--}
```
public final String getManager()
```

คืนค่า หรือ กำหนดผู้จัดการ. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setManager(String value) {#setManager-java.lang.String-}
```
public final void setManager(String value)
```

คืนค่า หรือ กำหนดผู้จัดการ. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresentationFormat() {#getPresentationFormat--}
```
public final String getPresentationFormat()
```

คืนค่า หรือ กำหนดรูปแบบที่ตั้งใจของการนำเสนอ. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public final void setPresentationFormat(String value)
```

คืนค่า หรือ กำหนดรูปแบบที่ตั้งใจของการนำเสนอ. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getSharedDoc() {#getSharedDoc--}
```
public final boolean getSharedDoc()
```

ตรวจสอบว่าการนำเสนอถูกแชร์ระหว่างหลายคนหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public final void setSharedDoc(boolean value)
```

ตรวจสอบว่าการนำเสนอถูกแชร์ระหว่างหลายคนหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getApplicationTemplate() {#getApplicationTemplate--}
```
public final String getApplicationTemplate()
```

คืนค่า หรือ กำหนดแม่แบบของแอปพลิเคชัน. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public final void setApplicationTemplate(String value)
```

คืนค่า หรือ กำหนดแม่แบบของแอปพลิเคชัน. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getTotalEditingTime() {#getTotalEditingTime--}
```
public final double getTotalEditingTime()
```

เวลาการแก้ไขทั้งหมดของการนำเสนอ. อ่าน/เขียน double.

**คืนค่า:**
double
### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public final void setTotalEditingTime(double value)
```

เวลาการแก้ไขทั้งหมดของการนำเสนอ. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```

คืนค่า หรือ กำหนดชื่อเรื่องของการนำเสนอ. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```

คืนค่า หรือ กำหนดชื่อเรื่องของการนำเสนอ. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```

คืนค่า หรือ กำหนดหัวเรื่องของการนำเสนอ. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```

คืนค่า หรือ กำหนดหัวเรื่องของการนำเสนอ. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```

คืนค่า หรือ กำหนดผู้เขียนของการนำเสนอ. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```

คืนค่า หรือ กำหนดผู้เขียนของการนำเสนอ. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getKeywords() {#getKeywords--}
```
public final String getKeywords()
```

คืนค่า หรือ กำหนดคำสำคัญของการนำเสนอ. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public final void setKeywords(String value)
```

คืนค่า หรือ กำหนดคำสำคัญของการนำเสนอ. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public final String getComments()
```

คืนค่า หรือ กำหนดความคิดเห็นของการนำเสนอ. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```

คืนค่า หรือ กำหนดความคิดเห็นของการนำเสนอ. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getCategory() {#getCategory--}
```
public final String getCategory()
```

คืนค่า หรือ กำหนดประเภทของการนำเสนอ. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setCategory(String value) {#setCategory-java.lang.String-}
```
public final void setCategory(String value)
```

คืนค่า หรือ กำหนดประเภทของการนำเสนอ. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```
คืนค่าวันที่ที่สร้างงานนำเสนอ ค่าจะอยู่ในรูปแบบ UTC. อ่าน/เขียน java.util.Date.

**คืนค่า:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```

คืนค่าวันที่ที่สร้างงานนำเสนอ ค่าจะอยู่ในรูปแบบ UTC. อ่าน/เขียน java.util.Date.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public final Date getLastSavedTime()
```

คืนค่าวันที่ที่แก้ไขงานนำเสนอล่าสุด ค่าจะอยู่ในรูปแบบ UTC. อ่านอย่างเดียวในกรณีของ Presentation.DocumentProperties (เนื่องจากจะถูกอัปเดตภายในกระบวนการบันทึกอ็อบเจกต์ IPresentation) สามารถเปลี่ยนแปลงได้ผ่านอินสแตนซ์ DocumentProperties ที่ส่งคืนโดยวิธี [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) โปรดดูตัวอย่างในสรุปวิธี [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**คืนค่า:**
java.util.Date
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public final void setLastSavedTime(Date value)
```

คืนค่าวันที่ที่แก้ไขงานนำเสนอล่าสุด ค่าจะอยู่ในรูปแบบ UTC. อ่านอย่างเดียวในกรณีของ Presentation.DocumentProperties (เนื่องจากจะถูกอัปเดตภายในกระบวนการบันทึกอ็อบเจกต์ IPresentation) สามารถเปลี่ยนแปลงได้ผ่านอินสแตนซ์ DocumentProperties ที่ส่งคืนโดยวิธี [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) โปรดดูตัวอย่างในสรุปวิธี [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public final Date getLastPrinted()
```

คืนค่าวันที่ที่งานนำเสนอถูกพิมพ์ครั้งสุดท้าย. อ่าน/เขียน java.util.Date.

**คืนค่า:**
java.util.Date
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public final void setLastPrinted(Date value)
```

คืนค่าวันที่ที่งานนำเสนอถูกพิมพ์ครั้งสุดท้าย. อ่าน/เขียน java.util.Date.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}
```
public final String getLastSavedBy()
```

คืนค่าหรือกำหนดชื่อของบุคคลสุดท้ายที่แก้ไขงานนำเสนอ. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public final void setLastSavedBy(String value)
```

คืนค่าหรือกำหนดชื่อของบุคคลสุดท้ายที่แก้ไขงานนำเสนอ. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public final int getRevisionNumber()
```

คืนค่าหรือกำหนดหมายเลขการแก้ไขของงานนำเสนอ. อ่าน/เขียน int.

**คืนค่า:**
int
### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public final void setRevisionNumber(int value)
```

คืนค่าหรือกำหนดหมายเลขการแก้ไขของงานนำเสนอ. อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}
```
public final String getContentStatus()
```

คืนค่าหรือกำหนดสถานะเนื้อหาของงานนำเสนอ. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public final void setContentStatus(String value)
```

คืนค่าหรือกำหนดสถานะเนื้อหาของงานนำเสนอ. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentType() {#getContentType--}
```
public final String getContentType()
```

คืนค่าหรือกำหนดประเภทเนื้อหาของงานนำเสนอ. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

คืนค่าหรือกำหนดประเภทเนื้อหาของงานนำเสนอ. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getHyperlinkBase() {#getHyperlinkBase--}
```
public final String getHyperlinkBase()
```

คืนค่าหรือกำหนดคุณสมบัติ HyperlinkBase ของเอกสาร. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public final void setHyperlinkBase(String value)
```

คืนค่าหรือกำหนดคุณสมบัติ HyperlinkBase ของเอกสาร. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public final int getCountOfCustomProperties()
```

คืนค่าจำนวนคุณสมบัติกำหนดเองที่มีอยู่จริงในคอลเลกชัน. อ่านอย่างเดียว int.

**คืนค่า:**
int
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public final String getCustomPropertyName(int index)
```

คืนชื่อคุณสมบัติกำหนดเองที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีที่เริ่มจากศูนย์ของคุณสมบัติกำหนดเองที่ต้องการดึง |

**คืนค่า:**
java.lang.String - ชื่อคุณสมบัติกำหนดเองที่ตำแหน่งที่ระบุ
### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public final boolean removeCustomProperty(String name)
```

ลบคุณสมบัติกำหนดเองที่เชื่อมโยงกับชื่อที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติกำหนดเองที่จะลบ |

**คืนค่า:**
boolean - คืนค่า true หากมีการลบคุณสมบัติ, false หากไม่ |

### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public final boolean containsCustomProperty(String name)
```

ตรวจสอบการมีอยู่ของคุณสมบัติกำหนดเองที่มีชื่อที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติกำหนดเองที่ต้องการตรวจสอบ |

**คืนค่า:**
boolean - คืนค่า true หากคุณสมบัติมีอยู่, false หากไม่มี
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final Object get_Item(String name)
```

คืนค่าหรือกำหนดคุณสมบัติกำหนดเองที่เชื่อมโยงกับชื่อที่ระบุ. อ่าน/เขียน Object.

--------------------

ค่าอาจเป็น **int**, **float**, **String**, **boolean** หรือ **Date**.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String |  |

**คืนค่า:**
java.lang.Object
### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public final void set_Item(String name, Object value)
```

คืนค่าหรือกำหนดคุณสมบัติกำหนดเองที่เชื่อมโยงกับชื่อที่ระบุ. อ่าน/เขียน Object.

--------------------

ค่าอาจเป็น **int**, **float**, **String**, **boolean** หรือ **Date**.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |
### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public final void getCustomPropertyValue(String name, boolean[] value)
```

ดึงค่าบูลีนที่มีชื่อจากคุณสมบัติกำหนดเอง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติกำหนดเองที่ต้องการดึง |
| value | boolean[] | ค่าคุณสมบัติกำหนดเอง |

### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public final void getCustomPropertyValue(String name, int[] value)
```

ดึงค่าจำนวนเต็มที่มีชื่อจากคุณสมบัติกำหนดเอง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติกำหนดเองที่ต้องการดึง |
| value | int[] | ค่าคุณสมบัติกำหนดเอง |

### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public final void getCustomPropertyValue(String name, Date[] value)
```

ดึงค่ากล่าววันที่ที่มีชื่อจากคุณสมบัติกำหนดเอง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติกำหนดเองที่ต้องการดึง |
| value | java.util.Date[] | ค่าคุณสมบัติกำหนดเอง |

### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public final void getCustomPropertyValue(String name, String[] value)
```

ดึงค่าข้อความที่มีชื่อจากคุณสมบัติกำหนดเอง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติกำหนดเองที่ต้องการดึง |
| value | java.lang.String[] | ค่าคุณสมบัติกำหนดเอง |

### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public final void getCustomPropertyValue(String name, float[] value)
```

ดึงค่า float ที่มีชื่อจากคุณสมบัติกำหนดเอง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติกำหนดเองที่ต้องการดึง |
| value | float[] | ค่าคุณสมบัติกำหนดเอง |

### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public final void getCustomPropertyValue(String name, double[] value)
```

ดึงค่าดับเบิลที่มีชื่อจากคุณสมบัติกำหนดเอง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติกำหนดเองที่ต้องการดึง |
| value | double[] | ค่าคุณสมบัติกำหนดเอง |

### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public final void setCustomPropertyValue(String name, boolean value)
```

กำหนดค่าบูลีนให้กับคุณสมบัติกำหนดเองที่มีชื่อ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติกำหนดเองที่ต้องการกำหนด |
| value | boolean | ค่าคุณสมบัติกำหนดเอง |

### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public final void setCustomPropertyValue(String name, int value)
```

กำหนดค่าจำนวนเต็มให้กับคุณสมบัติกำหนดเองที่มีชื่อ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติกำหนดเองที่ต้องการกำหนด |
| value | int | ค่าคุณสมบัติกำหนดเอง |

### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public final void setCustomPropertyValue(String name, Date value)
```

กำหนดค่า DateTime ให้กับคุณสมบัติกำหนดเองที่มีชื่อ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติกำหนดเองที่ต้องการกำหนด |
| value | java.util.Date | ค่าคุณสมบัติกำหนดเอง |

### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public final void setCustomPropertyValue(String name, String value)
```

กำหนดค่าข้อความให้กับคุณสมบัติกำหนดเองที่มีชื่อ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติกำหนดเองที่ต้องการกำหนด |
| value | java.lang.String | ค่าคุณสมบัติกำหนดเอง |

### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public final void setCustomPropertyValue(String name, float value)
```

กำหนดค่า float ให้กับคุณสมบัติกำหนดเองที่มีชื่อ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติกำหนดเองที่ต้องการกำหนด |
| value | float | ค่าคุณสมบัติกำหนดเอง |

### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public final void setCustomPropertyValue(String name, double value)
```

กำหนดค่าดับเบิลให้กับคุณสมบัติกำหนดเองที่มีชื่อ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติกำหนดเองที่ต้องการกำหนด |
| value | double | ค่าคุณสมบัติกำหนดเอง |

### clearCustomProperties() {#clearCustomProperties--}
```
public final void clearCustomProperties()
```

ลบคุณสมบัติกำหนดเองทั้งหมด

### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabel[] getSensitivityLabels()
```

ดึงอาเรย์ของป้ายความอ่อนไหวจากคุณสมบัติเจ้าของเอกสารที่กำหนดเอง (Microsoft Information Protection SDK Metadata)

--------------------

> ```
> The following code shows how to move the sensitivity labels information from the custom document properties 
>   to the modern SensitivityLabels collection:
>   
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // ดึงป้ายความอ่อนไหวจากคุณสมบัติเอกสารที่กำหนดเอง
>      ISensitivityLabel[] mipSensitivityLabels = pres.getDocumentProperties().getSensitivityLabels();
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
>      for (ISensitivityLabel sensitivityLabel : mipSensitivityLabels)
>      {
>          // เพิ่มป้ายลงในคอลเลกชัน
>          // ที่นี่คุณสามารถเพิ่มการตรวจสอบความถูกต้องของข้อมูลป้าย (ป้ายมีอยู่ ฯลฯ)
>          sensitivityLabels.add(sensitivityLabel);
>      }
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**คืนค่า:**
com.aspose.slides.ISensitivityLabel[]
### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public final void clearBuiltInProperties()
```

ล้างและกำหนดค่าเริ่มต้นให้กับคุณสมบัติ builtIn ทั้งหมด

### getScaleCrop() {#getScaleCrop--}
```
public final boolean getScaleCrop()
```

บ่งบอกโหมดการแสดงผลของภาพย่อเอกสาร ตั้งค่านี้เป็น **true** เพื่อเปิดการสเกลภาพย่อเอกสารให้พอดีกับจอแสดงผล ตั้งค่านี้เป็น **false** เพื่อเปิดการครอปภาพย่อเอกสารให้แสดงเฉพาะส่วนที่พอดีกับจอแสดงผล อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public final void setScaleCrop(boolean value)
```

บ่งบอกโหมดการแสดงผลของภาพย่อเอกสาร ตั้งค่านี้เป็น **true** เพื่อเปิดการสเกลภาพย่อเอกสารให้พอดีกับจอแสดงผล ตั้งค่านี้เป็น **false** เพื่อเปิดการครอปภาพย่อเอกสารให้แสดงเฉพาะส่วนที่พอดีกับจอแสดงผล อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getLinksUpToDate() {#getLinksUpToDate--}
```
public final boolean getLinksUpToDate()
```

บ่งบอกว่าลิงก์ไฮเปอร์เท็กซ์ในเอกสารเป็นปัจจุบันหรือไม่ ตั้งค่านี้เป็น **true** เพื่อระบุว่าลิงก์ไฮเปอร์เท็กซ์ได้รับการอัปเดต ตั้งค่านี้เป็น **false** เพื่อระบุว่าลิงก์ไฮเปอร์เท็กซ์ล้าสมัย อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public final void setLinksUpToDate(boolean value)
```
บ่งชี้ว่าไฮเปอร์ลิงก์ในเอกสารเป็นข้อมูลล่าสุดหรือไม่ ตั้งค่าส่วนนี้เป็น **true** เพื่อบ่งชี้ว่าไฮเปอร์ลิงก์ได้รับการอัปเดต ตั้งค่าส่วนนี้เป็น **false** เพื่อบ่งชี้ว่าไฮเปอร์ลิงก์ล้าสมัย อ่าน/เขียน boolean.

**Parameters:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public final boolean getHyperlinksChanged()
```

ระบุว่ามีไฮเปอร์ลิงก์หนึ่งหรือหลายรายการในส่วนนี้ได้รับการอัปเดตโดยผู้ผลิตเฉพาะในส่วนนี้ ผู้ผลิตคนถัดไปที่เปิดเอกสารนี้จะต้องอัปเดตความสัมพันธ์ของไฮเปอร์ลิงก์ด้วยไฮเปอร์ลิงก์ใหม่ที่ระบุในส่วนนี้ อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public final void setHyperlinksChanged(boolean value)
```

ระบุว่ามีไฮเปอร์ลิงก์หนึ่งหรือหลายรายการในส่วนนี้ได้รับการอัปเดตโดยผู้ผลิตเฉพาะในส่วนนี้ ผู้ผลิตคนถัดไปที่เปิดเอกสารนี้จะต้องอัปเดตความสัมพันธ์ของไฮเปอร์ลิงก์ด้วยไฮเปอร์ลิงก์ใหม่ที่ระบุในส่วนนี้ อ่าน/เขียน boolean.

**Parameters:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public final int getSlides()
```

คืนค่าจำนวนสไลด์ทั้งหมดในเอกสารงานนำเสนอ อ่านอย่างเดียว int.

**คืนค่า:**
int
### getHiddenSlides() {#getHiddenSlides--}
```
public final int getSlides()
```

คืนค่าจำนวนสไลด์ที่ซ่อนอยู่ในเอกสารงานนำเสนอ อ่านอย่างเดียว int.

**คืนค่า:**
int
### getNotes() {#getNotes--}
```
public final int getHiddenSlides()
```

คืนค่าจำนวนสไลด์ในงานนำเสนอที่มีหมายเหตุ อ่านอย่างเดียว int.

**คืนค่า:**
int
### getParagraphs() {#getParagraphs--}
```
public final int getParagraphs()
```

คืนค่าจำนวนย่อหน้าทั้งหมดที่พบในเอกสาร (ถ้ามี) อ่านอย่างเดียว int.

**คืนค่า:**
int
### getWords() {#getWords--}
```
public final int getWords()
```

คืนค่าจำนวนคำทั้งหมดที่อยู่ในเอกสาร อ่านอย่างเดียว int.

**คืนค่า:**
int
### getMultimediaClips() {#getMultimediaClips--}
```
public final int getMultimediaClips()
```

คืนค่าจำนวนคลิปเสียงหรือวิดีโอทั้งหมดที่ปรากฏในเอกสาร อ่านอย่างเดียว int.

**คืนค่า:**
int
### getTitlesOfParts() {#getTitlesOfParts--}
```
public final String[] getTitlesOfParts()
```

ระบุชื่อของแต่ละส่วนของเอกสาร ส่วนเหล่านี้ไม่ได้เป็นส่วนของเอกสารจริง แต่เป็นการแทนเชิงแนวคิดของส่วนของเอกสาร อ่านอย่างเดียว String[].

**คืนค่า:**
java.lang.String[]
### getHeadingPairs() {#getHeadingPairs--}
```
public final IHeadingPair[] getHeadingPairs()
```

บ่งชี้การจัดกลุ่มของส่วนเอกสารและจำนวนส่วนในแต่ละกลุ่ม อ่านอย่างเดียว IHeadingPair[].

**คืนค่า:**
com.aspose.slides.IHeadingPair[]
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

ทำสำเนาออบเจ็กต์ปัจจุบัน

**คืนค่า:**
java.lang.Object - Clone
### cloneT() {#cloneT--}
```
public final IDocumentProperties cloneT()
```

ทำสำเนาออบเจ็กต์ปัจจุบัน

**คืนค่า:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - Clone