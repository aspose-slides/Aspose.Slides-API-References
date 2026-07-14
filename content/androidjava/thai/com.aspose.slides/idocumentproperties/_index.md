---
title: IDocumentProperties
second_title: Aspose.Slides for Android via Java API Reference
description: แสดงคุณสมบัติของการนำเสนอ.
type: docs
url: /th/com.aspose.slides/idocumentproperties/
---```
public interface IDocumentProperties
```

แสดงคุณสมบัติของการนำเสนอ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | คืนค่ารุ่นของแอปฯ. |
| [getNameOfApplication()](#getNameOfApplication--) | คืนค่า หรือกำหนดชื่อของแอปพลิเคชัน. |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | คืนค่า หรือกำหนดชื่อของแอปพลิเคชัน. |
| [getCompany()](#getCompany--) | คืนค่า หรือกำหนดคุณสมบัติบริษัท. |
| [setCompany(String value)](#setCompany-java.lang.String-) | คืนค่า หรือกำหนดคุณสมบัติบริษัท. |
| [getManager()](#getManager--) | คืนค่า หรือกำหนดคุณสมบัติเจ้าหน้าที่. |
| [setManager(String value)](#setManager-java.lang.String-) | คืนค่า หรือกำหนดคุณสมบัติเจ้าหน้าที่. |
| [getPresentationFormat()](#getPresentationFormat--) | คืนค่า หรือกำหนดรูปแบบที่คาดว่าจะใช้ของการนำเสนอ. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | คืนค่า หรือกำหนดรูปแบบที่คาดว่าจะใช้ของการนำเสนอ. |
| [getSharedDoc()](#getSharedDoc--) | กำหนดว่าการนำเสนอถูกแชร์ระหว่างหลายคนหรือไม่. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | กำหนดว่าการนำเสนอถูกแชร์ระหว่างหลายคนหรือไม่. |
| [getApplicationTemplate()](#getApplicationTemplate--) | คืนค่า หรือกำหนดแม่แบบของแอปพลิเคชัน. |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | คืนค่า หรือกำหนดแม่แบบของแอปพลิเคชัน. |
| [getTotalEditingTime()](#getTotalEditingTime--) | เวลาการแก้ไขทั้งหมดของการนำเสนอ. |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | เวลาการแก้ไขทั้งหมดของการนำเสนอ. |
| [getTitle()](#getTitle--) | คืนค่า หรือกำหนดชื่อเรื่องของการนำเสนอ. |
| [setTitle(String value)](#setTitle-java.lang.String-) | คืนค่า หรือกำหนดชื่อเรื่องของการนำเสนอ. |
| [getSubject()](#getSubject--) | คืนค่า หรือกำหนดหัวข้อของการนำเสนอ. |
| [setSubject(String value)](#setSubject-java.lang.String-) | คืนค่า หรือกำหนดหัวข้อของการนำเสนอ. |
| [getAuthor()](#getAuthor--) | คืนค่า หรือกำหนดผู้เขียนของการนำเสนอ. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | คืนค่า หรือกำหนดผู้เขียนของการนำเสนอ. |
| [getKeywords()](#getKeywords--) | คืนค่า หรือกำหนดคำสำคัญของการนำเสนอ. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | คืนค่า หรือกำหนดคำสำคัญของการนำเสนอ. |
| [getComments()](#getComments--) | คืนค่า หรือกำหนดความคิดเห็นของการนำเสนอ. |
| [setComments(String value)](#setComments-java.lang.String-) | คืนค่า หรือกำหนดความคิดเห็นของการนำเสนอ. |
| [getCategory()](#getCategory--) | คืนค่า หรือกำหนดประเภทของการนำเสนอ. |
| [setCategory(String value)](#setCategory-java.lang.String-) | คืนค่า หรือกำหนดประเภทของการนำเสนอ. |
| [getCreatedTime()](#getCreatedTime--) | คืนค่าวันที่การนำเสนอถูกสร้างขึ้น. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | คืนค่าวันที่การนำเสนอถูกสร้างขึ้น. |
| [getLastSavedTime()](#getLastSavedTime--) | คืนค่าวันที่การนำเสนอถูกแก้ไขครั้งล่าสุด. |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | คืนค่าวันที่การนำเสนอถูกแก้ไขครั้งล่าสุด. |
| [getLastPrinted()](#getLastPrinted--) | คืนค่าวันที่การนำเสนอถูกพิมพ์ครั้งสุดท้าย. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | คืนค่าวันที่การนำเสนอถูกพิมพ์ครั้งสุดท้าย. |
| [getLastSavedBy()](#getLastSavedBy--) | คืนค่า หรือกำหนดชื่อของบุคคลสุดท้ายที่แก้ไขการนำเสนอ. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | คืนค่า หรือกำหนดชื่อของบุคคลสุดท้ายที่แก้ไขการนำเสนอ. |
| [getRevisionNumber()](#getRevisionNumber--) | คืนค่า หรือกำหนดหมายเลขรุ่นของการนำเสนอ. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | คืนค่า หรือกำหนดหมายเลขรุ่นของการนำเสนอ. |
| [getContentStatus()](#getContentStatus--) | คืนค่า หรือกำหนดสถานะเนื้อหาของการนำเสนอ. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | คืนค่า หรือกำหนดสถานะเนื้อหาของการนำเสนอ. |
| [getContentType()](#getContentType--) | คืนค่า หรือกำหนดประเภทเนื้อหาของการนำเสนอ. |
| [setContentType(String value)](#setContentType-java.lang.String-) | คืนค่า หรือกำหนดประเภทเนื้อหาของการนำเสนอ. |
| [getHyperlinkBase()](#getHyperlinkBase--) | คืนค่า หรือกำหนดคุณสมบัติเอกสาร HyperlinkBase. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | คืนค่า หรือกำหนดคุณสมบัติเอกสาร HyperlinkBase. |
| [getScaleCrop()](#getScaleCrop--) | ระบุโหมดการแสดงผลของรูปย่อเอกสาร. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | ระบุโหมดการแสดงผลของรูปย่อเอกสาร. |
| [getLinksUpToDate()](#getLinksUpToDate--) | ระบุว่าลิงก์ในเอกสารเป็นข้อมูลล่าสุดหรือไม่. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | ระบุว่าลิงก์ในเอกสารเป็นข้อมูลล่าสุดหรือไม่. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | ระบุว่าลิงก์หนึ่งหรือหลายลิงก์ในส่วนนี้ได้รับการอัปเดตโดยผู้ผลิตเฉพาะในส่วนนี้. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | ระบุว่าลิงก์หนึ่งหรือหลายลิงก์ในส่วนนี้ได้รับการอัปเดตโดยผู้ผลิตเฉพาะในส่วนนี้. |
| [getSlides()](#getSlides--) | ระบุจำนวนทั้งหมดของสไลด์ในเอกสารการนำเสนอ. |
| [getHiddenSlides()](#getHiddenSlides--) | ระบุจำนวนสไลด์ที่ซ่อนอยู่ในเอกสารการนำเสนอ. |
| [getNotes()](#getNotes--) | ระบุจำนวนสไลด์ที่มีโน้ตในการนำเสนอ. |
| [getParagraphs()](#getParagraphs--) | ระบุจำนวนย่อหน้าในเอกสารทั้งหมดหากมี. |
| [getWords()](#getWords--) | ระบุจำนวนคำทั้งหมดในเอกสาร. |
| [getMultimediaClips()](#getMultimediaClips--) | ระบุจำนวนคลิปเสียงหรือวิดีโอที่อยู่ในเอกสาร. |
| [getTitlesOfParts()](#getTitlesOfParts--) | ระบุชื่อของแต่ละส่วนของเอกสาร. |
| [getHeadingPairs()](#getHeadingPairs--) | ระบุการจัดกลุ่มของส่วนเอกสารและจำนวนส่วนในแต่ละกลุ่ม. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | คืนค่าจำนวนคุณสมบัติงานที่มีจริงในคอลเลกชัน. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | คืนชื่อคุณสมบัติงานที่ตำแหน่งที่ระบุ. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | ลบคุณสมบัติงานที่สัมพันธ์กับชื่อที่ระบุ. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | ตรวจสอบการมีอยู่ของคุณสมบัติงานด้วยชื่อที่ระบุ. |
| [get_Item(String name)](#get-Item-java.lang.String-) | คืนค่า หรือกำหนดคุณสมบัติงานที่สัมพันธ์กับชื่อที่ระบุ. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | คืนค่า หรือกำหนดคุณสมบัติงานที่สัมพันธ์กับชื่อที่ระบุ. |
| [clearCustomProperties()](#clearCustomProperties--) | ลบคุณสมบัติงานทั้งหมด. |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | ล้างและกำหนดค่าเริ่มต้นสำหรับคุณสมบัติ builtIn ทั้งหมด. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | รับค่าบูลีนที่ระบุจากคุณสมบัติงาน. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | รับค่าจำนวนเต็มที่ระบุจากคุณสมบัติงาน. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | รับค่าประเภท DateTime ที่ระบุจากคุณสมบัติงาน. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | รับค่าสตริงที่ระบุจากคุณสมบัติงาน. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | รับค่าจำนวนทศนิยมแบบ float ที่ระบุจากคุณสมบัติงาน. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | รับค่าจำนวนทศนิยมแบบ double ที่ระบุจากคุณสมบัติงาน. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | กำหนดคุณสมบัติงานบูลีนที่ระบุ. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | กำหนดคุณสมบัติงานจำนวนเต็มที่ระบุ. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | กำหนดคุณสมบัติงาน DateTime ที่ระบุ. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | กำหนดคุณสมบัติงานสตริงที่ระบุ. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | กำหนดคุณสมบัติงาน float ที่ระบุ. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | กำหนดคุณสมบัติงาน double ที่ระบุ. |
| [getSensitivityLabels()](#getSensitivityLabels--) | รับอาร์เรย์ของป้ายกำกับความละเอียดจากคุณสมบัติโดกเมนต์กำหนดเอง (Microsoft Information Protection SDK Metadata). |

### getAppVersion() {#getAppVersion--}
```
public abstract String getAppVersion()
```

คืนค่ารุ่นของแอปฯ. อ่านอย่างเดียว String.

--------------------

เนื้อหาขององค์ประกอบนี้ต้องอยู่ในรูปแบบ XX.YYYY โดยที่ X และ Y เป็นค่าตัวเลข; หากไม่เป็นเช่นนั้นเอกสารจะถือว่าไม่เป็นไปตามมาตรฐาน. Aspose.Slides แสดงเวอร์ชันในรูปแบบ XX.YY.ZZ โดย: XX - เวอร์ชันหลัก YY - เวอร์ชันรอง ZZ - เวอร์ชันแพตช์ ตัวอย่างเช่น ค่า 23.0105 หมายถึง Aspose.Slides เวอร์ชัน 23.1.5.

**ผลลัพธ์:**
java.lang.String

### getNameOfApplication() {#getNameOfApplication--}
```
public abstract String getNameOfApplication()
```

คืนค่า หรือกำหนดชื่อของแอปพลิเคชัน. อ่าน/เขียน String.

**ผลลัพธ์:**
java.lang.String

### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public abstract void setNameOfApplication(String value)
```

คืนค่า หรือกำหนดชื่อของแอปพลิเคชัน. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getCompany() {#getCompany--}
```
public abstract String getCompany()
```

คืนค่า หรือกำหนดคุณสมบัติบริษัท. อ่าน/เขียน String.

**ผลลัพธ์:**
java.lang.String

### setCompany(String value) {#setCompany-java.lang.String-}
```
public abstract void setCompany(String value)
```

คืนค่า หรือกำหนดคุณสมบัติบริษัท. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getManager() {#getManager--}
```
public abstract String getManager()
```

คืนค่า หรือกำหนดคุณสมบัติเจ้าหน้าที่. อ่าน/เขียน String.

**ผลลัพธ์:**
java.lang.String

### setManager(String value) {#setManager-java.lang.String-}
```
public abstract void setManager(String value)
```

คืนค่า หรือกำหนดคุณสมบัติเจ้าหน้าที่. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresentationFormat() {#getPresentationFormat--}
```
public abstract String getPresentationFormat()
```

คืนค่า หรือกำหนดรูปแบบที่คาดว่าจะใช้ของการนำเสนอ. อ่าน/เขียน String.

**ผลลัพธ์:**
java.lang.String

### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public abstract void setPresentationFormat(String value)
```

คืนค่า หรือกำหนดรูปแบบที่คาดว่าจะใช้ของการนำเสนอ. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getSharedDoc() {#getSharedDoc--}
```
public abstract boolean getSharedDoc()
```

กำหนดว่าการนำเสนอถูกแชร์ระหว่างหลายคนหรือไม่. อ่าน/เขียน boolean.

**ผลลัพธ์:**
boolean

### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public abstract void setSharedDoc(boolean value)
```

กำหนดว่าการนำเสนอถูกแชร์ระหว่างหลายคนหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getApplicationTemplate() {#getApplicationTemplate--}
```
public abstract String getApplicationTemplate()
```

คืนค่า หรือกำหนดแม่แบบของแอปพลิเคชัน. อ่าน/เขียน String.

**ผลลัพธ์:**
java.lang.String

### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public abstract void setApplicationTemplate(String value)
```

คืนค่า หรือกำหนดแม่แบบของแอปพลิเคชัน. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getTotalEditingTime() {#getTotalEditingTime--}
```
public abstract double getTotalEditingTime()
```

เวลาการแก้ไขทั้งหมดของการนำเสนอ. อ่าน/เขียน double.

**ผลลัพธ์:**
double

### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public abstract void setTotalEditingTime(double value)
```

เวลาการแก้ไขทั้งหมดของการนำเสนอ. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getTitle() {#getTitle--}
```
public abstract String getTitle()
```

คืนค่า หรือกำหนดชื่อเรื่องของการนำเสนอ. อ่าน/เขียน String.

**ผลลัพธ์:**
java.lang.String

### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
```

คืนค่า หรือกำหนดชื่อเรื่องของการนำเสนอ. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public abstract String getSubject()
```

คืนค่า หรือกำหนดหัวข้อของการนำเสนอ. อ่าน/เขียน String.

**ผลลัพธ์:**
java.lang.String

### setSubject(String value) {#setSubject-java.lang.String-}
```
public abstract void setSubject(String value)
```

คืนค่า หรือกำหนดหัวข้อของการนำเสนอ. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getAuthor() {#getAuthor--}
```
public abstract String getAuthor()
```

คืนค่า หรือกำหนดผู้เขียนของการนำเสนอ. อ่าน/เขียน String.

**ผลลัพธ์:**
java.lang.String

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public abstract void setAuthor(String value)
```

คืนค่า หรือกำหนดผู้เขียนของการนำเสนอ. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getKeywords() {#getKeywords--}
```
public abstract String getKeywords()
```

คืนค่า หรือกำหนดคำสำคัญของการนำเสนอ. อ่าน/เขียน String.

**ผลลัพธ์:**
java.lang.String

### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public abstract void setKeywords(String value)
```

คืนค่า หรือกำหนดคำสำคัญของการนำเสนอ. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public abstract String getComments()
```

คืนค่า หรือกำหนดความคิดเห็นของการนำเสนอ. อ่าน/เขียน String.

**ผลลัพธ์:**
java.lang.String

### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```

คืนค่า หรือกำหนดความคิดเห็นของการนำเสนอ. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getCategory() {#getCategory--}
```
public abstract String getCategory()
```

คืนค่า หรือกำหนดประเภทของการนำเสนอ. อ่าน/เขียน String.

**ผลลัพธ์:**
java.lang.String

### setCategory(String value) {#setCategory-java.lang.String-}
```
public abstract void setCategory(String value)
```

คืนค่า หรือกำหนดประเภทของการนำเสนอ. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

คืนค่าวันที่การนำเสนอถูกสร้างขึ้น. ค่าตรงตาม UTC. อ่าน/เขียน java.util.Date.

**ผลลัพธ์:**
java.util.Date

### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

คืนค่าวันที่การนำเสนอถูกสร้างขึ้น. ค่าตรงตาม UTC. อ่าน/เขียน java.util.Date.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public abstract Date getLastSavedTime()
```

คืนค่าวันที่การนำเสนอถูกแก้ไขครั้งล่าสุด. ค่าตรงตาม UTC.P อ่านอย่างเดียวในกรณีของ Presentation.DocumentProperties (เพราะจะถูกอัปเดตโดยอัตโนมัติในกระบวนการบันทึก IPresentation) สามารถเปลี่ยนได้ผ่านอินสแตนซ์ DocumentProperties ที่คืนจากเมธอด [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) โปรดดูตัวอย่างในเมธอดสรุป [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**ผลลัพธ์:**
java.util.Date

### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public abstract void setLastSavedTime(Date value)
```

คืนค่าวันที่การนำเสนอถูกแก้ไขครั้งล่าสุด. ค่าตรงตาม UTC.P อ่านอย่างเดียวในกรณีของ Presentation.DocumentProperties (เพราะจะถูกอัปเดตโดยอัตโนมัติในกระบวนการบันทึก IPresentation) สามารถเปลี่ยนได้ผ่านอินสแตนซ์ DocumentProperties ที่คืนจากเมธอด [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) โปรดดูตัวอย่างในเมธอดสรุป [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public abstract Date getLastPrinted()
```

คืนค่าวันที่การนำเสนอถูกพิมพ์ครั้งสุดท้าย. อ่าน/เขียน java.util.Date.

**ผลลัพธ์:**
java.util.Date

### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public abstract void setLastPrinted(Date value)
```

คืนค่าวันที่การนำเสนอถูกพิมพ์ครั้งสุดท้าย. อ่าน/เขียน java.util.Date.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}
```
public abstract String getLastSavedBy()
```

คืนค่า หรือกำหนดชื่อของบุคคลสุดท้ายที่แก้ไขการนำเสนอ. อ่าน/เขียน String.

**ผลลัพธ์:**
java.lang.String

### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public abstract void setLastSavedBy(String value)
```

คืนค่า หรือกำหนดชื่อของบุคคลสุดท้ายที่แก้ไขการนำเสนอ. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public abstract int getRevisionNumber()
```

คืนค่า หรือกำหนดหมายเลขรุ่นของการนำเสนอ. อ่าน/เขียน int.

**ผลลัพธ์:**
int

### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public abstract void setRevisionNumber(int value)
```

คืนค่า หรือกำหนดหมายเลขรุ่นของการนำเสนอ. อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}
```
public abstract String getContentStatus()
```

คืนค่า หรือกำหนดสถานะเนื้อหาของการนำเสนอ. อ่าน/เขียน String.

**ผลลัพธ์:**
java.lang.String

### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public abstract void setContentStatus(String value)
```

คืนค่า หรือกำหนดสถานะเนื้อหาของการนำเสนอ. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

คืนค่า หรือกำหนดประเภทเนื้อหาของการนำเสนอ. อ่าน/เขียน String.

**ผลลัพธ์:**
java.lang.String

### setContentType(String value) {#setContentType-java.lang.String-}
```
public abstract void setContentType(String value)
```

คืนค่า หรือกำหนดประเภทเนื้อหาของการนำเสนอ. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getHyperlinkBase() {#getHyperlinkBase--}
```
public abstract String getHyperlinkBase()
```

คืนค่า หรือกำหนดคุณสมบัติเอกสาร HyperlinkBase. อ่าน/เขียน String.

**ผลลัพธ์:**
java.lang.String

### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public abstract void setHyperlinkBase(String value)
```

คืนค่า หรือกำหนดคุณสมบัติเอกสาร HyperlinkBase. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getScaleCrop() {#getScaleCrop--}
```
public abstract boolean getScaleCrop()
```

ระบุโหมดการแสดงผลของรูปย่อเอกสาร. ตั้งค่าเป็น **true** เพื่อเปิดใช้งานการสเกลรูปย่อเอกสารให้พอดีกับหน้าจอ. ตั้งค่าเป็น **false** เพื่อเปิดใช้งานการครอบรูปย่อเอกสารให้แสดงเฉพาะส่วนที่พอดีกับหน้าจอ. อ่าน/เขียน boolean.

**ผลลัพธ์:**
boolean

### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public abstract void setScaleCrop(boolean value)
```

ระบุโหมดการแสดงผลของรูปย่อเอกสาร. ตั้งค่าเป็น **true** เพื่อเปิดใช้งานการสเกลรูปย่อเอกสารให้พอดีกับหน้าจอ. ตั้งค่าเป็น **false** เพื่อเปิดใช้งานการครอบรูปย่อเอกสารให้แสดงเฉพาะส่วนที่พอดีกับหน้าจอ. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getLinksUpToDate() {#getLinksUpToDate--}
```
public abstract boolean getLinksUpToDate()
```

ระบุว่าลิงก์ในเอกสารเป็นข้อมูลล่าสุดหรือไม่. ตั้งค่าเป็น **true** เพื่อระบุว่าลิงก์ได้รับการอัปเดต. ตั้งค่าเป็น **false** เพื่อระบุว่าลิงก์ล้าสมัย. อ่าน/เขียน boolean.

**ผลลัพธ์:**
boolean

### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public abstract void setLinksUpToDate(boolean value)
```

ระบุว่าลิงก์ในเอกสารเป็นข้อมูลล่าสุดหรือไม่. ตั้งค่าเป็น **true** เพื่อระบุว่าลิงก์ได้รับการอัปเดต. ตั้งค่าเป็น **false** เพื่อระบุว่าลิงก์ล้าสมัย. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public abstract boolean getHyperlinksChanged()
```

ระบุว่าลิงก์หนึ่งหรือหลายลิงก์ในส่วนนี้ได้รับการอัปเดตโดยผู้ผลิตเฉพาะในส่วนนี้. ผู้ผลิตคนถัดไปที่เปิดเอกสารนี้จะต้องอัปเดตความสัมพันธ์ของลิงก์ด้วยลิงก์ใหม่ที่ระบุในส่วนนี้. อ่าน/เขียน boolean.

**ผลลัพธ์:**
boolean

### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public abstract void setHyperlinksChanged(boolean value)
```

ระบุว่าลิงก์หนึ่งหรือหลายลิงก์ในส่วนนี้ได้รับการอัปเดตโดยผู้ผลิตเฉพาะในส่วนนี้. ผู้ผลิตคนถัดไปที่เปิดเอกสารนี้จะต้องอัปเดตความสัมพันธ์ของลิงก์ด้วยลิงก์ใหม่ที่ระบุในส่วนนี้. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public abstract int getSlides()
```

ระบุจำนวนทั้งหมดของสไลด์ในเอกสารการนำเสนอ. อ่านอย่างเดียว int.

**ผลลัพธ์:**
int

### getHiddenSlides() {#getHiddenSlides--}
```
public abstract int getHiddenSlides()
```

ระบุจำนวนสไลด์ที่ซ่อนอยู่ในเอกสารการนำเสนอ. อ่านอย่างเดียว int.

**ผลลัพธ์:**
int

### getNotes() {#getNotes--}
```
public abstract int getNotes()
```

ระบุจำนวนสไลด์ที่มีโน้ตในการนำเสนอ. อ่านอย่างเดียว int.

**ผลลัพธ์:**
int

### getParagraphs() {#getParagraphs--}
```
public abstract int getParagraphs()
```

ระบุจำนวนย่อหน้าในเอกสารทั้งหมดหากมี. อ่านอย่างเดียว int.

**ผลลัพธ์:**
int

### getWords() {#getWords--}
```
public abstract int getWords()
```

ระบุจำนวนคำทั้งหมดในเอกสาร. อ่านอย่างเดียว int.

**ผลลัพธ์:**
int

### getMultimediaClips() {#getMultimediaClips--}
```
public abstract int getMultimediaClips()
```

ระบุจำนวนคลิปเสียงหรือวิดีโอที่อยู่ในเอกสาร. อ่านอย่างเดียว int.

**ผลลัพธ์:**
int

### getTitlesOfParts() {#getTitlesOfParts--}
```
public abstract String[] getTitlesOfParts()
```

ระบุชื่อของแต่ละส่วนของเอกสาร. ส่วนเหล่านี้ไม่ใช่ส่วนเอกสารจริง แต่เป็นการแทนส่วนของเอกสารในเชิงแนวคิด. อ่านอย่างเดียว String[].

**ผลลัพธ์:**
java.lang.String[]

### getHeadingPairs() {#getHeadingPairs--}
```
public abstract IHeadingPair[] getHeadingPairs()
```

ระบุการจัดกลุ่มของส่วนเอกสารและจำนวนส่วนในแต่ละกลุ่ม. อ่านอย่างเดียว IHeadingPair[].

**ผลลัพธ์:**
com.aspose.slides.IHeadingPair[]

### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public abstract int getCountOfCustomProperties()
```

คืนค่าจำนวนคุณสมบัติงานที่มีจริงในคอลเลกชัน. อ่านอย่างเดียว int.

**ผลลัพธ์:**
int

### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public abstract String getCustomPropertyName(int index)
```

คืนชื่อคุณสมบัติงานที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีแบบศูนย์ฐานของคุณสมบัติงานที่ต้องการดึง. |

**ผลลัพธ์:**
java.lang.String - ชื่อคุณสมบัติงานที่ตำแหน่งที่ระบุ.

### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public abstract boolean removeCustomProperty(String name)
```

ลบคุณสมบัติงานที่สัมพันธ์กับชื่อที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติงานที่ต้องการลบ. |

**ผลลัพธ์:**
boolean - คืนค่า true หากมีการลบคุณสมบัติ, false หากไม่. 

### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public abstract boolean containsCustomProperty(String name)
```

ตรวจสอบการมีอยู่ของคุณสมบัติงานด้วยชื่อที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติงานที่ต้องการตรวจสอบ. |

**ผลลัพธ์:**
boolean - คืนค่า true หากมีคุณสมบัติ, false หากไม่มี.

### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract Object get_Item(String name)
```

คืนค่า หรือกำหนดคุณสมบัติงานที่สัมพันธ์กับชื่อที่ระบุ. อ่าน/เขียน Object.

--------------------

ค่าอาจเป็น **int**, **float**, **double**, **String**, **boolean** หรือ **Date**.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String |  |

**ผลลัพธ์:**
java.lang.Object

### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public abstract void set_Item(String name, Object value)
```

คืนค่า หรือกำหนดคุณสมบัติงานที่สัมพันธ์กับชื่อที่ระบุ. อ่าน/เขียน Object.

--------------------

ค่าอาจเป็น **int**, **float**, **double**, **String**, **boolean** หรือ **Date**.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |

### clearCustomProperties() {#clearCustomProperties--}
```
public abstract void clearCustomProperties()
```

ลบคุณสมบัติงานทั้งหมด.

### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public abstract void clearBuiltInProperties()
```

ล้างและกำหนดค่าเริ่มต้นสำหรับคุณสมบัติ builtIn ทั้งหมด.

### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public abstract void getCustomPropertyValue(String name, boolean[] value)
```

รับค่าบูลีนที่ระบุจากคุณสมบัติงาน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติงานที่ต้องการดึง |
| value | boolean[] | ค่าคุณสมบัติงาน |

### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public abstract void getCustomPropertyValue(String name, int[] value)
```

รับค่าจำนวนเต็มที่ระบุจากคุณสมบัติงาน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติงานที่ต้องการดึง |
| value | int[] | ค่าคุณสมบัติงาน |

### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public abstract void getCustomPropertyValue(String name, Date[] value)
```

รับค่าประเภท DateTime ที่ระบุจากคุณสมบัติงาน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติงานที่ต้องการดึง |
| value | java.util.Date[] | ค่าคุณสมบัติงาน |

### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public abstract void getCustomPropertyValue(String name, String[] value)
```

รับค่าสตริงที่ระบุจากคุณสมบัติงาน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติงานที่ต้องการดึง |
| value | java.lang.String[] | ค่าคุณสมบัติงาน |

### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public abstract void getCustomPropertyValue(String name, float[] value)
```

รับค่าจำนวนทศนิยมแบบ float ที่ระบุจากคุณสมบัติงาน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติงานที่ต้องการดึง |
| value | float[] | ค่าคุณสมบัติงาน |

### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public abstract void getCustomPropertyValue(String name, double[] value)
```

รับค่าจำนวนทศนิยมแบบ double ที่ระบุจากคุณสมบัติงาน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติงานที่ต้องการดึง. |
| value | double[] | ค่าคุณสมบัติงาน |

### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public abstract void setCustomPropertyValue(String name, boolean value)
```

กำหนดคุณสมบัติงานบูลีนที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติงานที่ต้องการกำหนด |
| value | boolean | ค่าคุณสมบัติงาน |

### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public abstract void setCustomPropertyValue(String name, int value)
```

กำหนดคุณสมบัติงานจำนวนเต็มที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติงานที่ต้องการกำหนด |
| value | int | ค่าคุณสมบัติงาน |

### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public abstract void setCustomPropertyValue(String name, Date value)
```

กำหนดคุณสมบัติงาน DateTime ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติงานที่ต้องการกำหนด |
| value | java.util.Date | ค่าคุณสมบัติงาน |

### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public abstract void setCustomPropertyValue(String name, String value)
```

กำหนดคุณสมบัติงานสตริงที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติงานที่ต้องการกำหนด |
| value | java.lang.String | ค่าคุณสมบัติงาน |

### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public abstract void setCustomPropertyValue(String name, float value)
```

กำหนดคุณสมบัติงาน float ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติงานที่ต้องการกำหนด |
| value | float | ค่าคุณสมบัติงาน |

### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public abstract void setCustomPropertyValue(String name, double value)
```

กำหนดคุณสมบัติงาน double ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติงานที่ต้องการกำหนด |
| value | double | ค่าคุณสมบัติงาน |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabel[] getSensitivityLabels()
```

รับอาร์เรย์ของป้ายกำกับความละเอียดจากคุณสมบัติเอกสารกำหนดเอง (Microsoft Information Protection SDK Metadata).

--------------------

> ```
> The following code shows how to move the sensitivity labels information from the custom document properties 
>   to the modern SensitivityLabels collection:
>   
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Get sensitivity labels from the custom document properties
>      ISensitivityLabel[] mipSensitivityLabels = pres.getDocumentProperties().getSensitivityLabels();
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
>      for (ISensitivityLabel sensitivityLabel : mipSensitivityLabels)
>      {
>          // Add label to the collection
>          // Here you can add a check for the validity of the label information (the label is available, etc)
>          sensitivityLabels.add(sensitivityLabel);
>      }
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**ผลลัพธ์:**
com.aspose.slides.ISensitivityLabel[]