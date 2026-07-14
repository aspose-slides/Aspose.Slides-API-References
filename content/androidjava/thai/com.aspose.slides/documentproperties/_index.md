---
title: DocumentProperties
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง Java API
description: แสดงคุณสมบัติของการนำเสนอ.
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

แสดงคุณสมบัติของการนำเสนอ

--------------------

> ```
> The following example shows how to access built-in Properties of PowerPoint Presentation.
>  
>  // สร้างอินสแตนซ์ของคลาส Presentation ที่เป็นตัวแทนของการนำเสนอ
>  Presentation pres = new Presentation("AccessBuiltin Properties.pptx");
>  try {
>      // สร้างอ้างอิงไปยังวัตถุ IDocumentProperties ที่เชื่อมโยงกับ Presentation
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // แสดงคุณสมบัติ built-in
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
>  // สร้างอินสแตนซ์ของคลาส Presentation ที่เป็นตัวแทนของ Presentation
>  Presentation pres = new Presentation("ModifyBuiltinProperties.pptx");
>  try {
>      // สร้างอ้างอิงไปยังวัตถุ IDocumentProperties ที่เชื่อมโยงกับ Presentation
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // ตั้งค่าคุณสมบัติ built-in
>      documentProperties.setAuthor("Aspose.Slides for Android via Java");
>      documentProperties.setTitle("Modifying Presentation Properties");
>      documentProperties.setSubject("Aspose Subject");
>      // บันทึกการนำเสนอของคุณลงไฟล์
>      pres.save("DocumentProperties_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [DocumentProperties()](#DocumentProperties--) | สร้างอินสแตนซ์ใหม่ของคลาส [DocumentProperties](../../com.aspose.slides/documentproperties). |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | คืนค่าเวอร์ชันของแอปพลิเคชัน. |
| [getNameOfApplication()](#getNameOfApplication--) | คืนค่าหรือกำหนดชื่อของแอปพลิเคชัน. |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | คืนค่าหรือกำหนดชื่อของแอปพลิเคชัน. |
| [getCompany()](#getCompany--) | คืนค่าหรือกำหนดคุณสมบัติบริษัท. |
| [setCompany(String value)](#setCompany-java.lang.String-) | คืนค่าหรือกำหนดคุณสมบัติบริษัท. |
| [getManager()](#getManager--) | คืนค่าหรือกำหนดคุณสมบัติผู้จัดการ. |
| [setManager(String value)](#setManager-java.lang.String-) | คืนค่าหรือกำหนดคุณสมบัติผู้จัดการ. |
| [getPresentationFormat()](#getPresentationFormat--) | คืนค่าหรือกำหนดรูปแบบที่ตั้งใจของการนำเสนอ. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | คืนค่าหรือกำหนดรูปแบบที่ตั้งใจของการนำเสนอ. |
| [getSharedDoc()](#getSharedDoc--) | ตรวจสอบว่าการนำเสนอถูกแชร์ระหว่างหลายคนหรือไม่. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | ตรวจสอบว่าการนำเสนอถูกแชร์ระหว่างหลายคนหรือไม่. |
| [getApplicationTemplate()](#getApplicationTemplate--) | คืนค่าหรือกำหนดเทมเพลตของแอปพลิเคชัน. |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | คืนค่าหรือกำหนดเทมเพลตของแอปพลิเคชัน. |
| [getTotalEditingTime()](#getTotalEditingTime--) | เวลาการแก้ไขทั้งหมดของการนำเสนอ. |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | เวลาการแก้ไขทั้งหมดของการนำเสนอ. |
| [getTitle()](#getTitle--) | คืนค่าหรือกำหนดชื่อเรื่องของการนำเสนอ. |
| [setTitle(String value)](#setTitle-java.lang.String-) | คืนค่าหรือกำหนดชื่อเรื่องของการนำเสนอ. |
| [getSubject()](#getSubject--) | คืนค่าหรือกำหนดหัวเรื่องของการนำเสนอ. |
| [setSubject(String value)](#setSubject-java.lang.String-) | คืนค่าหรือกำหนดหัวเรื่องของการนำเสนอ. |
| [getAuthor()](#getAuthor--) | คืนค่าหรือกำหนดผู้เขียนของการนำเสนอ. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | คืนค่าหรือกำหนดผู้เขียนของการนำเสนอ. |
| [getKeywords()](#getKeywords--) | คืนค่าหรือกำหนดคำสำคัญของการนำเสนอ. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | คืนค่าหรือกำหนดคำสำคัญของการนำเสนอ. |
| [getComments()](#getComments--) | คืนค่าหรือกำหนดความคิดเห็นของการนำเสนอ. |
| [setComments(String value)](#setComments-java.lang.String-) | คืนค่าหรือกำหนดความคิดเห็นของการนำเสนอ. |
| [getCategory()](#getCategory--) | คืนค่าหรือกำหนดประเภทของการนำเสนอ. |
| [setCategory(String value)](#setCategory-java.lang.String-) | คืนค่าหรือกำหนดประเภทของการนำเสนอ. |
| [getCreatedTime()](#getCreatedTime--) | คืนค่าวันที่การนำเสนอถูกสร้างขึ้น. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | คืนค่าวันที่การนำเสนอถูกสร้างขึ้น. |
| [getLastSavedTime()](#getLastSavedTime--) | คืนค่าวันที่การนำเสนอถูกแก้ไขครั้งสุดท้าย. |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | คืนค่าวันที่การนำเสนอถูกแก้ไขครั้งสุดท้าย. |
| [getLastPrinted()](#getLastPrinted--) | คืนค่าวันที่การนำเสนอถูกพิมพ์ครั้งสุดท้าย. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | คืนค่าวันที่การนำเสนอถูกพิมพ์ครั้งสุดท้าย. |
| [getLastSavedBy()](#getLastSavedBy--) | คืนค่าหรือกำหนดชื่อของผู้ที่แก้ไขการนำเสนอครั้งสุดท้าย. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | คืนค่าหรือกำหนดชื่อของผู้ที่แก้ไขการนำเสนอครั้งสุดท้าย. |
| [getRevisionNumber()](#getRevisionNumber--) | คืนค่าหรือกำหนดหมายเลขรุ่นของการนำเสนอ. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | คืนค่าหรือกำหนดหมายเลขรุ่นของการนำเสนอ. |
| [getContentStatus()](#getContentStatus--) | คืนค่าหรือกำหนดสถานะเนื้อหาของการนำเสนอ. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | คืนค่าหรือกำหนดสถานะเนื้อหาของการนำเสนอ. |
| [getContentType()](#getContentType--) | คืนค่าหรือกำหนดประเภทเนื้อหาของการนำเสนอ. |
| [setContentType(String value)](#setContentType-java.lang.String-) | คืนค่าหรือกำหนดประเภทเนื้อหาของการนำเสนอ. |
| [getHyperlinkBase()](#getHyperlinkBase--) | คืนค่าหรือกำหนดคุณสมบัติ HyperlinkBase ของเอกสาร. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | คืนค่าหรือกำหนดคุณสมบัติ HyperlinkBase ของเอกสาร. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | คืนค่าจำนวนคุณสมบัติแบบกำหนดเองที่มีอยู่จริงในคอลเลกชัน. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | คืนชื่อคุณสมบัติแบบกำหนดเองที่ตำแหน่ง index ที่ระบุ. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | ลบคุณสมบัติแบบกำหนดเองที่สัมพันธ์กับชื่อที่ระบุ. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | ตรวจสอบการมีอยู่ของคุณสมบัติแบบกำหนดเองที่ชื่อที่ระบุ. |
| [get_Item(String name)](#get-Item-java.lang.String-) | คืนค่าหรือกำหนดคุณสมบัติแบบกำหนดเองที่สัมพันธ์กับชื่อที่ระบุ. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | คืนค่าหรือกำหนดคุณสมบัติแบบกำหนดเองที่สัมพันธ์กับชื่อที่ระบุ. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | ดึงค่าบูลีนที่มีชื่อจากคุณสมบัติแบบกำหนดเอง. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | ดึงค่าจำนวนเต็มที่มีชื่อจากคุณสมบัติแบบกำหนดเอง. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | ดึงค่า DateTime ที่มีชื่อจากคุณสมบัติแบบกำหนดเอง. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | ดึงค่าข้อความที่มีชื่อจากคุณสมบัติแบบกำหนดเอง. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | ดึงค่า float ที่มีชื่อจากคุณสมบัติแบบกำหนดเอง. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | ดึงค่า double ที่มีชื่อจากคุณสมบัติแบบกำหนดเอง. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | ตั้งค่าคุณสมบัติแบบกำหนดเองประเภทบูลีนที่มีชื่อ. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | ตั้งค่าคุณสมบัติแบบกำหนดเองประเภทจำนวนเต็มที่มีชื่อ. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | ตั้งค่าคุณสมบัติแบบกำหนดเองประเภท DateTime ที่มีชื่อ. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | ตั้งค่าคุณสมบัติแบบกำหนดเองประเภทสตริงที่มีชื่อ. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | ตั้งค่าคุณสมบัติแบบกำหนดเองประเภท float ที่มีชื่อ. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | ตั้งค่าคุณสมบัติแบบกำหนดเองประเภท double ที่มีชื่อ. |
| [clearCustomProperties()](#clearCustomProperties--) | ลบคุณสมบัติแบบกำหนดเองทั้งหมด. |
| [getSensitivityLabels()](#getSensitivityLabels--) | ดึงอาร์เรย์ของป้ายกำกับความละเอียดจากคุณสมบัติเอกสารแบบกำหนดเอง (Microsoft Information Protection SDK Metadata). |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | ล้างและตั้งค่าค่าตั้งต้นสำหรับคุณสมบัติ builtIn ทั้งหมด. |
| [getScaleCrop()](#getScaleCrop--) | ระบุโหมดการแสดงผลของภาพย่อเอกสาร. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | ระบุโหมดการแสดงผลของภาพย่อเอกสาร. |
| [getLinksUpToDate()](#getLinksUpToDate--) | ระบุว่าลิงก์ในเอกสารเป็นปัจจุบันหรือไม่. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | ระบุว่าลิงก์ในเอกสารเป็นปัจจุบันหรือไม่. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | ระบุว่าลิงก์หนึ่งหรือหลายลิงก์ในส่วนนี้ได้รับการอัปเดตโดยผู้ผลิตในส่วนนี้เท่านั้น. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | ระบุว่าลิงก์หนึ่งหรือหลายลิงก์ในส่วนนี้ได้รับการอัปเดตโดยผู้ผลิตในส่วนนี้เท่านั้น. |
| [getSlides()](#getSlides--) | คืนค่าจำนวนสไลด์ทั้งหมดในเอกสารการนำเสนอ. |
| [getHiddenSlides()](#getHiddenSlides--) | คืนค่าจำนวนสไลด์ที่ซ่อนอยู่ในเอกสารการนำเสนอ. |
| [getNotes()](#getNotes--) | คืนค่าจำนวนสไลด์ที่มีโน้ตในเอกสารการนำเสนอ. |
| [getParagraphs()](#getParagraphs--) | คืนค่าจำนวนย่อหน้าทั้งหมดที่พบในเอกสาร (ถ้ามี). |
| [getWords()](#getWords--) | คืนค่าจำนวนคำทั้งหมดที่อยู่ในเอกสาร. |
| [getMultimediaClips()](#getMultimediaClips--) | คืนค่าจำนวนคลิปเสียงหรือวิดีโอที่อยู่ในเอกสาร. |
| [getTitlesOfParts()](#getTitlesOfParts--) | ระบุตัวเรื่องของแต่ละส่วนของเอกสาร. |
| [getHeadingPairs()](#getHeadingPairs--) | ระบุกลุ่มของส่วนเอกสารและจำนวนส่วนในแต่ละกลุ่ม. |
| [deepClone()](#deepClone--) | ทำสำเนาวัตถุปัจจุบัน |
| [cloneT()](#cloneT--) | ทำสำเนาวัตถุปัจจุบัน |

### DocumentProperties() {#DocumentProperties--}
```
public DocumentProperties()
```

สร้างอินสแตนซ์ใหม่ของคลาส [DocumentProperties](../../com.aspose.slides/documentproperties).

### getAppVersion() {#getAppVersion--}
```
public final String getAppVersion()
```

คืนค่าเวอร์ชันของแอปพลิเคชัน. อ่านอย่างเดียว String.

**คืนค่า:**  
java.lang.String

### getNameOfApplication() {#getNameOfApplication--}
```
public final String getNameOfApplication()
```

คืนค่าหรือกำหนดชื่อของแอปพลิเคชัน. อ่าน/เขียน String.

**คืนค่า:**  
java.lang.String

### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public final void setNameOfApplication(String value)
```

คืนค่าหรือกำหนดชื่อของแอปพลิเคชัน. อ่าน/เขียน String.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getCompany() {#getCompany--}
```
public final String getCompany()
```

คืนค่าหรือกำหนดคุณสมบัติบริษัท. อ่าน/เขียน String.

**คืนค่า:**  
java.lang.String

### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```

คืนค่าหรือกำหนดคุณสมบัติบริษัท. อ่าน/เขียน String.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getManager() {#getManager--}
```
public final String getManager()
```

คืนค่าหรือกำหนดคุณสมบัติผู้จัดการ. อ่าน/เขียน String.

**คืนค่า:**  
java.lang.String

### setManager(String value) {#setManager-java.lang.String-}
```
public final void setManager(String value)
```

คืนค่าหรือกำหนดคุณสมบัติผู้จัดการ. อ่าน/เขียน String.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresentationFormat() {#getPresentationFormat--}
```
public final String getPresentationFormat()
```

คืนค่าหรือกำหนดรูปแบบที่ตั้งใจของการนำเสนอ. อ่าน/เขียน String.

**คืนค่า:**  
java.lang.String

### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public final void setPresentationFormat(String value)
```

คืนค่าหรือกำหนดรูปแบบที่ตั้งใจของการนำเสนอ. อ่าน/เขียน String.

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

คืนค่าหรือกำหนดเทมเพลตของแอปพลิเคชัน. อ่าน/เขียน String.

**คืนค่า:**  
java.lang.String

### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public final void setApplicationTemplate(String value)
```

คืนค่าหรือกำหนดเทมเพลตของแอปพลิเคชัน. อ่าน/เขียน String.

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

คืนค่าหรือกำหนดชื่อเรื่องของการนำเสนอ. อ่าน/เขียน String.

**คืนค่า:**  
java.lang.String

### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```

คืนค่าหรือกำหนดชื่อเรื่องของการนำเสนอ. อ่าน/เขียน String.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```

คืนค่าหรือกำหนดหัวเรื่องของการนำเสนอ. อ่าน/เขียน String.

**คืนค่า:**  
java.lang.String

### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```

คืนค่าหรือกำหนดหัวเรื่องของการนำเสนอ. อ่าน/เขียน String.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```

คืนค่าหรือกำหนดผู้เขียนของการนำเสนอ. อ่าน/เขียน String.

**คืนค่า:**  
java.lang.String

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```

คืนค่าหรือกำหนดผู้เขียนของการนำเสนอ. อ่าน/เขียน String.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getKeywords() {#getKeywords--}
```
public final String getKeywords()
```

คืนค่าหรือกำหนดคำสำคัญของการนำเสนอ. อ่าน/เขียน String.

**คืนค่า:**  
java.lang.String

### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public final void setKeywords(String value)
```

คืนค่าหรือกำหนดคำสำคัญของการนำเสนอ. อ่าน/เขียน String.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public final String getComments()
```

คืนค่าหรือกำหนดความคิดเห็นของการนำเสนอ. อ่าน/เขียน String.

**คืนค่า:**  
java.lang.String

### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```

คืนค่าหรือกำหนดความคิดเห็นของการนำเสนอ. อ่าน/เขียน String.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getCategory() {#getCategory--}
```
public final String getCategory()
```

คืนค่าหรือกำหนดประเภทของการนำเสนอ. อ่าน/เขียน String.

**คืนค่า:**  
java.lang.String

### setCategory(String value) {#setCategory-java.lang.String-}
```
public final void setCategory(String value)
```

คืนค่าหรือกำหนดประเภทของการนำเสนอ. อ่าน/เขียน String.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```

คืนค่าวันที่การนำเสนอถูกสร้างขึ้น. ค่าจะอยู่ในรูปแบบ UTC. อ่าน/เขียน java.util.Date.

**คืนค่า:**  
java.util.Date

### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```

คืนค่าวันที่การนำเสนอถูกสร้างขึ้น. ค่าจะอยู่ในรูปแบบ UTC. อ่าน/เขียน java.util.Date.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public final Date getLastSavedTime()
```

คืนค่าวันที่การนำเสนอถูกแก้ไขครั้งสุดท้าย. ค่าจะอยู่ในรูปแบบ UTC. อ่านอย่างเดียวในกรณีของ Presentation.DocumentProperties (เพราะค่าจะอัปเดตโดยอัตโนมัติในระหว่างกระบวนการบันทึกวัตถุ IPresentation) สามารถเปลี่ยนแปลงได้ผ่านอินสแตนซ์ DocumentProperties ที่คืนจากเมธอด [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) ดูตัวอย่างในสรุปเมธอด [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**คืนค่า:**  
java.util.Date

### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public final void setLastSavedTime(Date value)
```

คืนค่าวันที่การนำเสนอถูกแก้ไขครั้งสุดท้าย. ค่าจะอยู่ในรูปแบบ UTC. อ่านอย่างเดียวในกรณีของ Presentation.DocumentProperties (เพราะค่าจะอัปเดตโดยอัตโนมัติในระหว่างกระบวนการบันทึกวัตถุ IPresentation) สามารถเปลี่ยนแปลงได้ผ่านอินสแตนซ์ DocumentProperties ที่คืนจากเมธอด [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) ดูตัวอย่างในสรุปเมธอด [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public final Date getLastPrinted()
```

คืนค่าวันที่การนำเสนอถูกพิมพ์ครั้งสุดท้าย. อ่าน/เขียน java.util.Date.

**คืนค่า:**  
java.util.Date

### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public final void setLastPrinted(Date value)
```

คืนค่าวันที่การนำเสนอถูกพิมพ์ครั้งสุดท้าย. อ่าน/เขียน java.util.Date.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}
```
public final String getLastSavedBy()
```

คืนค่าหรือกำหนดชื่อของผู้ที่แก้ไขการนำเสนอครั้งสุดท้าย. อ่าน/เขียน String.

**คืนค่า:**  
java.lang.String

### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public final void setLastSavedBy(String value)
```

คืนค่าหรือกำหนดชื่อของผู้ที่แก้ไขการนำเสนอครั้งสุดท้าย. อ่าน/เขียน String.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public final int getRevisionNumber()
```

คืนค่าหรือกำหนดหมายเลขรุ่นของการนำเสนอ. อ่าน/เขียน int.

**คืนค่า:**  
int

### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public final void setRevisionNumber(int value)
```

คืนค่าหรือกำหนดหมายเลขรุ่นของการนำเสนอ. อ่าน/เขียน int.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}
```
public     S   –  è s Z P f N I 

```

คืนค่าหรือกำหนดสถานะเนื้อหาของการนำเสนอ. อ่าน/เขียน String.

**คืนค่า:**  
java.lang.String

### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public final void setContentStatus(String value)
```

คืนค่าหรือกำหนดสถานะเนื้อหาของการนำเสนอ. อ่าน/เขียน String.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentType() {#getContentType--}
```
public final String getContentType()
```

คืนค่าหรือกำหนดประเภทเนื้อหาของการนำเสนอ. อ่าน/เขียน String.

**คืนค่า:**  
java.lang.String

### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

คืนค่าหรือกำหนดประเภทเนื้อหาของการนำเสนอ. อ่าน/เขียน String.

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

คืนค่าจำนวนคุณสมบัติแบบกำหนดเองที่มีอยู่จริงในคอลเลกชัน. อ่านอย่างเดียว int.

**คืนค่า:**  
int

### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public final String getCustomPropertyName(int index)
```

คืนชื่อคุณสมบัติแบบกำหนดเองที่ตำแหน่ง index ที่ระบุ.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีเริ่มจากศูนย์ของคุณสมบัติแบบกำหนดเองที่ต้องการดึง. |

**คืนค่า:**  
java.lang.String - ชื่อคุณสมบัติแบบกำหนดเองที่ตำแหน่งที่ระบุ

### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public final boolean removeCustomProperty(String name)
```

ลบคุณสมบัติแบบกำหนดเองที่สัมพันธ์กับชื่อที่ระบุ.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติแบบกำหนดเองที่ต้องการลบ. |

**คืนค่า:**  
boolean - คืนค่า true หากลบสำเร็จ, false หากไม่สำเร็จ

### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public final boolean containsCustomProperty(String name)
```

ตรวจสอบการมีอยู่ของคุณสมบัติแบบกำหนดเองที่ชื่อที่ระบุ.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติแบบกำหนดเองที่ต้องการตรวจสอบ. |

**คืนค่า:**  
boolean - คืนค่า true หากมี, false หากไม่มี

### get_Item(String name) {#get-Item-java.lang.String-}
```
public final Object get_Item(String name)
```

คืนค่าหรือกำหนดคุณสมบัติแบบกำหนดเองที่สัมพันธ์กับชื่อที่ระบุ. อ่าน/เขียน Object.

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

คืนค่าหรือกำหนดคุณสมบัติแบบกำหนดเองที่สัมพันธ์กับชื่อที่ระบุ. อ่าน/เขียน Object.

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

ดึงค่าบูลีนที่มีชื่อจากคุณสมบัติแบบกำหนดเอง.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติแบบกำหนดเองที่ต้องการดึง |
| value | boolean[] | ค่าไฟล์ของคุณสมบัติแบบกำหนดเอง |

### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public final void getCustomPropertyValue(String name, int[] value)
```

ดึงค่าจำนวนเต็มที่มีชื่อจากคุณสมบัติแบบกำหนดเอง.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติแบบกำหนดเองที่ต้องการดึง |
| value | int[] | ค่าไฟล์ของคุณสมบัติแบบกำหนดเอง |

### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public final void getCustomPropertyValue(String name, Date[] value)
```

ดึงค่า DateTime ที่มีชื่อจากคุณสมบัติแบบกำหนดเอง.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติแบบกำหนดเองที่ต้องการดึง |
| value | java.util.Date[] | ค่าไฟล์ของคุณสมบัติแบบกำหนดเอง |

### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public final void getCustomPropertyValue(String name, String[] value)
```

ดึงค่าข้อความที่มีชื่อจากคุณสมบัติแบบกำหนดเอง.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติแบบกำหนดเองที่ต้องการดึง |
| value | java.lang.String[] | ค่าไฟล์ของคุณสมบัติแบบกำหนดเอง |

### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public final void getCustomPropertyValue(String name, float[] value)
```

ดึงค่า float ที่มีชื่อจากคุณสมบัติแบบกำหนดเอง.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติแบบกำหนดเองที่ต้องการดึง |
| value | float[] | ค่าไฟล์ของคุณสมบัติแบบกำหนดเอง |

### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public final void getCustomPropertyValue(String name, double[] value)
```

ดึงค่า double ที่มีชื่อจากคุณสมบัติแบบกำหนดเอง.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติแบบกำหนดเองที่ต้องการดึง. |
| value | double[] | ค่าไฟล์ของคุณสมบัติแบบกำหนดเอง |

### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public final void setCustomPropertyValue(String name, boolean value)
```

ตั้งค่าคุณสมบัติแบบกำหนดเองประเภทบูลีนที่มีชื่อ.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติแบบกำหนดเองที่ต้องการตั้งค่า |
| value | boolean | ค่าไฟล์ของคุณสมบัติแบบกำหนดเอง |

### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public final void setCustomPropertyValue(String name, int value)
```

ตั้งค่าคุณสมบัติแบบกำหนดเองประเภทจำนวนเต็มที่มีชื่อ.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติแบบกำหนดเองที่ต้องการตั้งค่า |
| value | int | ค่าไฟล์ของคุณสมบัติแบบกำหนดเอง |

### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public final void setCustomPropertyValue(String name, Date value)
```

ตั้งค่าคุณสมบัติแบบกำหนดเองประเภท DateTime ที่มีชื่อ.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติแบบกำหนดเองที่ต้องการตั้งค่า |
| value | java.util.Date | ค่าไฟล์ของคุณสมบัติแบบกำหนดเอง |

### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public final void setCustomPropertyValue(String name, String value)
```

ตั้งค่าคุณสมบัติแบบกำหนดเองประเภทสตริงที่มีชื่อ.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติแบบกำหนดเองที่ต้องการตั้งค่า |
| value | java.lang.String | ค่าไฟล์ของคุณสมบัติแบบกำหนดเอง |

### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public final void setCustomPropertyValue(String name, float value)
```

ตั้งค่าคุณสมบัติแบบกำหนดเองประเภท float ที่มีชื่อ.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติแบบกำหนดเองที่ต้องการตั้งค่า |
| value | float | ค่าไฟล์ของคุณสมบัติแบบกำหนดเอง |

### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public final void setCustomPropertyValue(String name, double value)
```

ตั้งค่าคุณสมบัติแบบกำหนดเองประเภท double ที่มีชื่อ.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติแบบกำหนดเองที่ต้องการตั้งค่า |
| value | double | ค่าไฟล์ของคุณสมบัติแบบกำหนดเอง |

### clearCustomProperties() {#clearCustomProperties--}
```
public final void clearCustomProperties()
```

ลบคุณสมบัติแบบกำหนดเองทั้งหมด.

### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabel[] getSensitivityLabels()
```

ดึงอาร์เรย์ของป้ายกำกับความละเอียดจากคุณสมบัติเอกสารแบบกำหนดเอง (Microsoft Information Protection SDK Metadata).

> ```
> The following code shows how to move the sensitivity labels information from the custom document properties 
>   to the modern SensitivityLabels collection:
>   
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // ดึงป้ายกำกับความละเอียดจากคุณสมบัติเอกสารแบบกำหนดเอง
>      ISensitivityLabel[] mipSensitivityLabels = pres.getDocumentProperties().getSensitivityLabels();
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
>      for (ISensitivityLabel sensitivityLabel : mipSensitivityLabels)
>      {
>          // เพิ่มป้ายกำกับลงในคอลเลกชัน
>          // ที่นี่คุณสามารถเพิ่มการตรวจสอบความถูกต้องของข้อมูลป้ายกำกับ (ป้ายกำกับมีอยู่, เป็นต้น)
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
public     S   –  è s Z P f N I 

```

ล้างและตั้งค่าค่าตั้งต้นสำหรับคุณสมบัติ builtIn ทั้งหมด.

### getScaleCrop() {#getScaleCrop--}
```
public final boolean getScaleCrop()
```

ระบุโหมดการแสดงผลของภาพย่อเอกสาร. ตั้งค่าส่วนนี้เป็น **true** เพื่อเปิดการปรับสเกลของภาพย่อให้พอดีกับหน้าจอ. ตั้งเป็น **false** เพื่อเปิดการครอบตัดภาพย่อให้แสดงเฉพาะส่วนที่เหมาะกับหน้าจอ. อ่าน/เขียน boolean.

**คืนค่า:**  
boolean

### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public final void setScaleCrop(boolean value)
```

ระบุโหมดการแสดงผลของภาพย่อเอกสาร. ตั้งค่าส่วนนี้เป็น **true** เพื่อเปิดการปรับสเกลของภาพย่อให้พอดีกับหน้าจอ. ตั้งเป็น **false** เพื่อเปิดการครอบตัดภาพย่อให้แสดงเฉพาะส่วนที่เหมาะกับหน้าจอ. อ่าน/เขียน boolean.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getLinksUpToDate() {#getLinksUpToDate--}
```
public final boolean getLinksUpToDate()
```

ระบุว่าลิงก์ในเอกสารเป็นปัจจุบันหรือไม่. ตั้งค่าส่วนนี้เป็น **true** เพื่อบ่งบอกว่าลิงก์ได้รับการอัปเดต. ตั้งเป็น **false** เพื่อบ่งบอกว่าลิงก์ล้าสมัย. อ่าน/เขียน boolean.

**คืนค่า:**  
boolean

### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public final void setLinksUpToDate(boolean value)
```

ระบุว่าลิงก์ในเอกสารเป็นปัจจุบันหรือไม่. ตั้งค่าส่วนนี้เป็น **true** เพื่อบ่งบอกว่าลิงก์ได้รับการอัปเดต. ตั้งเป็น **false** เพื่อบ่งบอกว่าลิงก์ล้าสมัย. อ่าน/เขียน boolean.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public final boolean getHyperlinksChanged()
```

ระบุว่าลิงก์หนึ่งหรือหลายลิงก์ในส่วนนี้ได้รับการอัปเดตโดยผู้ผลิตในส่วนนี้เท่านั้น. ผู้ผลิตคนต่อไปที่เปิดเอกสารนี้จะต้องอัปเดตความสัมพันธ์ของลิงก์ด้วยลิงก์ใหม่ที่ระบุในส่วนนี้. อ่าน/เขียน boolean.

**คืนค่า:**  
boolean

### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public final void setHyperlinksChanged(boolean value)
```

ระบุว่าลิงก์หนึ่งหรือหลายลิงก์ในส่วนนี้ได้รับการอัปเดตโดยผู้ผลิตในส่วนนี้เท่านั้น. ผู้ผลิตคนต่อไปที่เปิดเอกสารนี้จะต้องอัปเดตความสัมพันธ์ของลิงก์ด้วยลิงก์ใหม่ที่ระบุในส่วนนี้. อ่าน/เขียน boolean.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public     K     e d N g C 

```

คืนค่าจำนวนสไลด์ทั้งหมดในเอกสารการนำเสนอ. อ่านอย่างเดียว int.

**คืนค่า:**  
int

### getHiddenSlides() {#getHiddenSlides--}
```
public final int getHiddenSlides()
```

คืนค่าจำนวนสไลด์ที่ซ่อนอยู่ในเอกสารการนำเสนอ. อ่านอย่างเดียว int.

**คืนค่า:**  
int

### getNotes() {#getNotes--}
```
public final int getNotes()
```

คืนค่าจำนวนสไลด์ที่มีโน้ตในเอกสารการนำเสนอ. อ่านอย่างเดียว int.

**คืนค่า:**  
int

### getParagraphs() {#getParagraphs--}
```
public final int getParagraphs()
```

คืนค่าจำนวนย่อหน้าทั้งหมดที่พบในเอกสาร (ถ้ามี). อ่านอย่างเดียว int.

**คืนค่า:**  
int

### getWords() {#getWords--}
```
public final int getWords()
```

คืนค่าจำนวนคำทั้งหมดที่อยู่ในเอกสาร. อ่านอย่างเดียว int.

**คืนค่า:**  
int

### getMultimediaClips() {#getMultimediaClips--}
```
public final int getMultimediaClips()
```

คืนค่าจำนวนคลิปเสียงหรือวิดีโอที่อยู่ในเอกสาร. อ่านอย่างเดียว int.

**คืนค่า:**  
int

### getTitlesOfParts() {#getTitlesOfParts--}
```
public final String[] getTitlesOfParts()
```

ระบุตัวเรื่องของแต่ละส่วนของเอกสาร. ส่วนเหล่านี้ไม่ใช่ส่วนของเอกสารจริง แต่เป็นการแทนส่วนของเอกสารเชิงแนวคิด. อ่านอย่างเดียว String[].

**คืนค่า:**  
java.lang.String[]

### getHeadingPairs() {#getHeadingPairs--}
```
public final IHeadingPair[] getHeadingPairs()
```

ระบุกลุ่มของส่วนเอกสารและจำนวนส่วนในแต่ละกลุ่ม. อ่านอย่างเดียว IHeadingPair[].

**คืนค่า:**  
com.aspose.slides.IHeadingPair[]

### deepClone() {#deepClone--}
```
public final Object deepClone()
```

ทำสำเนาวัตถุปัจจุบัน

**คืนค่า:**  
java.lang.Object - Clone

### cloneT() {#cloneT--}
```
public final IDocumentProperties cloneT()
```

ทำสำเนาวัตถุปัจจุบัน

**คืนค่า:**  
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - Clone