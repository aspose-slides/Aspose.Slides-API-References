---
title: IDocumentProperties
second_title: Aspose.Slides for Java API Reference
description: แสดงคุณสมบัติของการนำเสนอ
type: docs
url: /th/com.aspose.slides/idocumentproperties/
---```
public interface IDocumentProperties
```

แสดงคุณสมบัติของการนำเสนอ
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | คืนค่าเวอร์ชันของแอป. |
| [getNameOfApplication()](#getNameOfApplication--) | คืนค่า หรือกำหนดชื่อของแอปพลิเคชัน. |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | คืนค่า หรือกำหนดชื่อของแอปพลิเคชัน. |
| [getCompany()](#getCompany--) | คืนค่า หรือกำหนดคุณสมบัติบริษัท. |
| [setCompany(String value)](#setCompany-java.lang.String-) | คืนค่า หรือกำหนดคุณสมบัติบริษัท. |
| [getManager()](#getManager--) | คืนค่า หรือกำหนดคุณสมบัติเจ้าหน้าที่. |
| [setManager(String value)](#setManager-java.lang.String-) | คืนค่า หรือกำหนดคุณสมบัติเจ้าหน้าที่. |
| [getPresentationFormat()](#getPresentationFormat--) | คืนค่า หรือกำหนดรูปแบบที่ตั้งใจของการนำเสนอ. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | คืนค่า หรือกำหนดรูปแบบที่ตั้งใจของการนำเสนอ. |
| [getSharedDoc()](#getSharedDoc--) | ตรวจสอบว่าการนำเสนอถูกแชร์ระหว่างหลายคนหรือไม่. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | ตรวจสอบว่าการนำเสนอถูกแชร์ระหว่างหลายคนหรือไม่. |
| [getApplicationTemplate()](#getApplicationTemplate--) | คืนค่า หรือกำหนดเทมเพลตของแอปพลิเคชัน. |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | คืนค่า หรือกำหนดเทมเพลตของแอปพลิเคชัน. |
| [getTotalEditingTime()](#getTotalEditingTime--) | เวลาการแก้ไขทั้งหมดของการนำเสนอ. |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | เวลาการแก้ไขทั้งหมดของการนำเสนอ. |
| [getTitle()](#getTitle--) | คืนค่า หรือกำหนดชื่อเรื่องของการนำเสนอ. |
| [setTitle(String value)](#setTitle-java.lang.String-) | คืนค่า หรือกำหนดชื่อเรื่องของการนำเสนอ. |
| [getSubject()](#getSubject--) | คืนค่า หรือกำหนดหัวข้อของการนำเสนอ. |
| [setSubject(String value)](#setSubject-java.lang.String-) | คืนค่า หรือกำหนดหัวข้อของการนำเสนอ. |
| [getAuthor()](#getAuthor--) | คืนค่า หรือกำหนดผู้เขียนของการนำเสนอ. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | คืนค่า หรือกำหนดผู้เขียนของการนำเสนอ. |
| [getKeywords()](#getKeywords--) | คืนค่า หรือกำหนดคีย์เวิร์ดของการนำเสนอ. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | คืนค่า หรือกำหนดคีย์เวิร์ดของการนำเสนอ. |
| [getComments()](#getComments--) | คืนค่า หรือกำหนดความคิดเห็นของการนำเสนอ. |
| [setComments(String value)](#setComments-java.lang.String-) | คืนค่า หรือกำหนดความคิดเห็นของการนำเสนอ. |
| [getCategory()](#getCategory--) | คืนค่า หรือกำหนดประเภทของการนำเสนอ. |
| [setCategory(String value)](#setCategory-java.lang.String-) | คืนค่า หรือกำหนดประเภทของการนำเสนอ. |
| [getCreatedTime()](#getCreatedTime--) | คืนค่าวันที่ที่การนำเสนอถูกสร้าง. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | คืนค่าวันที่ที่การนำเสนอถูกสร้าง. |
| [getLastSavedTime()](#getLastSavedTime--) | คืนค่าวันที่ที่การนำเสนอถูกแก้ไขล่าสุด. |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | คืนค่าวันที่ที่การนำเสนอถูกแก้ไขล่าสุด. |
| [getLastPrinted()](#getLastPrinted--) | คืนค่าวันที่ที่การนำเสนอถูกพิมพ์ครั้งสุดท้าย. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | คืนค่าวันที่ที่การนำเสนอถูกพิมพ์ครั้งสุดท้าย. |
| [getLastSavedBy()](#getLastSavedBy--) | คืนค่า หรือกำหนดชื่อของผู้ที่แก้ไขการนำเสนอเป็นครั้งสุดท้าย. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | คืนค่า หรือกำหนดชื่อของผู้ที่แก้ไขการนำเสนอเป็นครั้งสุดท้าย. |
| [getRevisionNumber()](#getRevisionNumber--) | คืนค่า หรือกำหนดหมายเลขรุ่นของการนำเสนอ. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | คืนค่า หรือกำหนดหมายเลขรุ่นของการนำเสนอ. |
| [getContentStatus()](#getContentStatus--) | คืนค่า หรือกำหนดสถานะเนื้อหาของการนำเสนอ. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | คืนค่า หรือกำหนดสถานะเนื้อหาของการนำเสนอ. |
| [getContentType()](#getContentType--) | คืนค่า หรือกำหนดประเภทเนื้อหาของการนำเสนอ. |
| [setContentType(String value)](#setContentType-java.lang.String-) | คืนค่า หรือกำหนดประเภทเนื้อหาของการนำเสนอ. |
| [getHyperlinkBase()](#getHyperlinkBase--) | คืนค่า หรือกำหนดคุณสมบัติ HyperlinkBase ของเอกสาร. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | คืนค่า หรือกำหนดคุณสมบัติ HyperlinkBase ของเอกสาร. |
| [getScaleCrop()](#getScaleCrop--) | บ่งชี้โหมดการแสดงผลของภาพย่อเอกสาร. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | บ่งชี้โหมดการแสดงผลของภาพย่อเอกสาร. |
| [getLinksUpToDate()](#getLinksUpToDate--) | บ่งชี้ว่าลิงก์ในเอกสารเป็นปัจจุบันหรือไม่. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | บ่งชี้ว่าลิงก์ในเอกสารเป็นปัจจุบันหรือไม่. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | ระบุว่าลิงก์หนึ่งหรือหลายลิงก์ในส่วนนี้ได้รับการอัปเดตโดยผู้ผลิตเฉพาะในส่วนนี้. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | ระบุว่าลิงก์หนึ่งหรือหลายลิงก์ในส่วนนี้ได้รับการอัปเดตโดยผู้ผลิตเฉพาะในส่วนนี้. |
| [getSlides()](#getSlides--) | ระบุจำนวนสไลด์ทั้งหมดในเอกสารการนำเสนอ. |
| [getHiddenSlides()](#getHiddenSlides--) | ระบุจำนวนสไลด์ที่ซ่อนอยู่ในเอกสารการนำเสนอ. |
| [getNotes()](#getNotes--) | ระบุจำนวนสไลด์ในการนำเสนอที่มีบันทึก. |
| [getParagraphs()](#getParagraphs--) | ระบุจำนวนย่อหน้าทั้งหมดที่พบในเอกสารหากมี. |
| [getWords()](#getWords--) | ระบุจำนวนคำทั้งหมดในเอกสาร. |
| [getMultimediaClips()](#getMultimediaClips--) | ระบุจำนวนคลิปเสียงหรือวิดีโอทั้งหมดที่อยู่ในเอกสาร. |
| [getTitlesOfParts()](#getTitlesOfParts--) | ระบุชื่อของแต่ละส่วนของเอกสาร. |
| [getHeadingPairs()](#getHeadingPairs--) | บ่งชี้การจัดกลุ่มของส่วนเอกสารและจำนวนส่วนในแต่ละกลุ่ม. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | คืนค่าจำนวนของคุณสมบัติกำหนดเองที่มีอยู่จริงในคอลเลกชัน. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | คืนชื่อของคุณสมบัติกำหนดเองที่ตำแหน่งที่ระบุ. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | ลบคุณสมบัติกำหนดเองที่เชื่อมโยงกับชื่อที่ระบุ. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | ตรวจสอบการมีอยู่ของคุณสมบัติกำหนดเองด้วยชื่อที่ระบุ. |
| [get_Item(String name)](#get-Item-java.lang.String-) | คืนค่า หรือกำหนดคุณสมบัติกำหนดเองที่เชื่อมโยงกับชื่อที่ระบุ. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | คืนค่า หรือกำหนดคุณสมบัติกำหนดเองที่เชื่อมโยงกับชื่อที่ระบุ. |
| [clearCustomProperties()](#clearCustomProperties--) | ลบคุณสมบัติกำหนดเองทั้งหมด. |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | ล้างและตั้งค่าตั้งต้นสำหรับคุณสมบัติกำหนดสร้างทั้งหมด. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Gets a named boolean value from the custom properties. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Gets a named integer value from the custom properties. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Gets a named DateTime value from the custom properties. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Gets a named string value from the custom properties. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Gets a named float value from the custom properties. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Gets a named double value from the custom properties. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | ตั้งค่าคุณสมบัติกำหนดเองแบบบูลีนที่มีชื่อ. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | ตั้งค่าคุณสมบัติกำหนดเองแบบจำนวนเต็มที่มีชื่อ. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | ตั้งค่าคุณสมบัติกำหนดเองแบบ DateTime ที่มีชื่อ. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | ตั้งค่าคุณสมบัติกำหนดเองแบบสตริงที่มีชื่อ. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | ตั้งค่าคุณสมบัติกำหนดเองแบบ float ที่มีชื่อ. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | ตั้งค่าคุณสมบัติกำหนดเองแบบ double ที่มีชื่อ. |
| [getSensitivityLabels()](#getSensitivityLabels--) | รับอาร์เรย์ของป้ายกำกับความไวต่อความละเอียดจากคุณสมบัติกำหนดเองของเอกสาร (Microsoft Information Protection SDK Metadata). |

### getAppVersion() {#getAppVersion--}
```
public abstract String getAppVersion()
```

คืนค่าเวอร์ชันของแอป. อ่านอย่างเดียว String.

เนื้อหาขององค์ประกอบนี้ควรอยู่ในรูปแบบ XX.YYYY โดย X และ Y เป็นค่าตัวเลข; หากไม่เป็นเช่นนั้นเอกสารจะถูกถือว่าไม่สอดคล้อง. Aspose.Slides แสดงเวอร์ชันของมันในรูปแบบ XX.YY.ZZ โดย: XX - เวอร์ชันหลัก YY - เวอร์ชันรอง ZZ - เวอร์ชันแก้ไข ตัวอย่างเช่น ค่า 23.0105 หมายถึงเวอร์ชัน Aspose.Slides 23.1.5.

**ส่งคืน:**  
java.lang.String

### getNameOfApplication() {#getNameOfApplication--}
```
public abstract String getNameOfApplication()
```

คืนค่า หรือกำหนดชื่อของแอปพลิเคชัน. อ่าน/เขียน String.

**ส่งคืน:**  
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

**ส่งคืน:**  
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

**ส่งคืน:**  
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

คืนค่า หรือกำหนดรูปแบบที่ตั้งใจของการนำเสนอ. อ่าน/เขียน String.

**ส่งคืน:**  
java.lang.String

### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public abstract void setPresentationFormat(String value)
```

คืนค่า หรือกำหนดรูปแบบที่ตั้งใจของการนำเสนอ. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getSharedDoc() {#getSharedDoc--}
```
public abstract boolean getSharedDoc()
```

ตรวจสอบว่าการนำเสนอถูกแชร์ระหว่างหลายคนหรือไม่. อ่าน/เขียน boolean.

**ส่งคืน:**  
boolean

### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public abstract void setSharedDoc(boolean value)
```

ตรวจสอบว่าการนำเสนอถูกแชร์ระหว่างหลายคนหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getApplicationTemplate() {#getApplicationTemplate--}
```
public abstract String getApplicationTemplate()
```

คืนค่า หรือกำหนดเทมเพลตของแอปพลิเคชัน. อ่าน/เขียน String.

**ส่งคืน:**  
java.lang.String

### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public abstract void setApplicationTemplate(String value)
```

คืนค่า หรือกำหนดเทมเพลตของแอปพลิเคชัน. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getTotalEditingTime() {#getTotalEditingTime--}
```
public abstract double getTotalEditingTime()
```

เวลาการแก้ไขทั้งหมดของการนำเสนอ. อ่าน/เขียน double.

**ส่งคืน:**  
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

**ส่งคืน:**  
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

**ส่งคืน:**  
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

**ส่งคืน:**  
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

คืนค่า หรือกำหนดคีย์เวิร์ดของการนำเสนอ. อ่าน/เขียน String.

**ส่งคืน:**  
java.lang.String

### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public abstract void setKeywords(String value)
```

คืนค่า หรือกำหนดคีย์เวิร์ดของการนำเสนอ. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public abstract String getComments()
```

คืนค่า หรือกำหนดความคิดเห็นของการนำเสนอ. อ่าน/เขียน String.

**ส่งคืน:**  
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

**ส่งคืน:**  
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
| ค่า | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

คืนค่าวันที่ที่สร้างงานนำเสนอ ค่าจะอยู่ในรูปแบบ UTC. อ่าน/เขียน java.util.Date.

**คืนค่า:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

คืนค่าวันที่ที่สร้างงานนำเสนอ ค่าจะอยู่ในรูปแบบ UTC. อ่าน/เขียน java.util.Date.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public abstract Date getLastSavedTime()
```

คืนค่าวันที่ที่แก้ไขงานนำเสนอครั้งล่าสุด ค่าจะอยู่ในรูปแบบ UTC. อ่านอย่างเดียวในกรณีของ Presentation.DocumentProperties (เพราะจะถูกอัปเดตภายในขณะกระบวนการบันทึกวัตถุ IPresentation) สามารถเปลี่ยนแปลงได้ผ่านอินสแตนซ์ DocumentProperties ที่คืนค่ามาจากเมธอด [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) โปรดดูตัวอย่างในเมธอดสรุป [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**คืนค่า:**
java.util.Date
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public abstract void setLastSavedTime(Date value)
```

คืนค่าวันที่ที่แก้ไขงานนำเสนอครั้งล่าสุด ค่าจะอยู่ในรูปแบบ UTC. อ่านอย่างเดียวในกรณีของ Presentation.DocumentProperties (เพราะจะถูกอัปเดตภายในขณะกระบวนการบันทึกวัตถุ IPresentation) สามารถเปลี่ยนแปลงได้ผ่านอินสแตนซ์ DocumentProperties ที่คืนค่ามาจากเมธอด [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) โปรดดูตัวอย่างในเมธอดสรุป [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public abstract Date getLastPrinted()
```

คืนค่าวันที่ที่พิมพ์งานนำเสนอครั้งสุดท้าย อ่าน/เขียน java.util.Date.

**คืนค่า:**
java.util.Date
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public abstract void setLastPrinted(Date value)
```

คืนค่าวันที่ที่พิมพ์งานนำเสนอครั้งสุดท้าย อ่าน/เขียน java.util.Date.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}
```
public abstract String getLastSavedBy()
```

คืนหรือกำหนดชื่อของผู้ที่แก้ไขงานนำเสนอล่าสุด อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public abstract void setLastSavedBy(String value)
```

คืนหรือกำหนดชื่อของผู้ที่แก้ไขงานนำเสนอล่าสุด อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public abstract int getRevisionNumber()
```

คืนหรือกำหนดหมายเลขเวอร์ชันของงานนำเสนอ อ่าน/เขียน int.

**คืนค่า:**
int
### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public abstract void setRevisionNumber(int value)
```

คืนหรือกำหนดหมายเลขเวอร์ชันของงานนำเสนอ อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}
```
public abstract String getContentStatus()
```

คืนหรือกำหนดสถานะเนื้อหาของงานนำเสนอ อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public abstract void setContentStatus(String value)
```

คืนหรือกำหนดสถานะเนื้อหาของงานนำเสนอ อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

คืนหรือกำหนดประเภทเนื้อหาของงานนำเสนอ อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public abstract void setContentType(String value)
```

คืนหรือกำหนดประเภทเนื้อหาของงานนำเสนอ อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getHyperlinkBase() {#getHyperlinkBase--}
```
public abstract String getHyperlinkBase()
```

คืนหรือกำหนดคุณสมบัติ HyperlinkBase ของเอกสาร อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public abstract void setHyperlinkBase(String value)
```

คืนหรือกำหนดคุณสมบัติ HyperlinkBase ของเอกสาร อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getScaleCrop() {#getScaleCrop--}
```
public abstract boolean getScaleCrop()
```

ระบุโหมดการแสดงผลของรูปย่อเอกสาร ตั้งค่าส่วนนี้เป็น **true** เพื่อเปิดการปรับสเกลของรูปย่อให้พอดีหน้าจอ ตั้งค่าส่วนนี้เป็น **false** เพื่อเปิดการครอบตัดของรูปย่อให้แสดงเฉพาะส่วนที่พอดีกับหน้าจอ อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public abstract void setScaleCrop(boolean value)
```

ระบุโหมดการแสดงผลของรูปย่อเอกสาร ตั้งค่าส่วนนี้เป็น **true** เพื่อเปิดการปรับสเกลของรูปย่อให้พอดีหน้าจอ ตั้งค่าส่วนนี้เป็น **false** เพื่อเปิดการครอบตัดของรูปย่อให้แสดงเฉพาะส่วนที่พอดีกับหน้าจอ อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getLinksUpToDate() {#getLinksUpToDate--}
```
public abstract boolean getLinksUpToDate()
```

ระบุว่าลิงก์ไฮเปอร์ในเอกสารเป็นข้อมูลล่าสุดหรือไม่ ตั้งค่าส่วนนี้เป็น **true** เพื่อบ่งบอกว่าลิงก์ไฮเปอร์ได้รับการอัปเดต ตั้งค่าส่วนนี้เป็น **false** เพื่อบ่งบอกว่าลิงก์ไฮเปอร์ล้าสมัย อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public abstract void setLinksUpToDate(boolean value)
```

ระบุว่าลิงก์ไฮเปอร์ในเอกสารเป็นข้อมูลล่าสุดหรือไม่ ตั้งค่าส่วนนี้เป็น **true** เพื่อบ่งบอกว่าลิงก์ไฮเปอร์ได้รับการอัปเดต ตั้งค่าส่วนนี้เป็น **false** เพื่อบ่งบอกว่าลิงก์ไฮเปอร์ล้าสมัย อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public abstract boolean getHyperlinksChanged()
```

ระบุว่าลิงก์ไฮเปอร์หนึ่งหรือหลายรายการในส่วนนี้ถูกอัปเดตโดยผู้ผลิตที่เป็นเจ้าของส่วนนี้เท่านั้น ผู้ผลิตคนต่อไปที่เปิดเอกสารนี้จะต้องอัปเดตความสัมพันธ์ของลิงก์ไฮเปอร์ด้วยลิงก์ใหม่ที่ระบุในส่วนนี้ อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public abstract void setHyperlinksChanged(boolean value)
```

ระบุว่าลิงก์ไฮเปอร์หนึ่งหรือหลายรายการในส่วนนี้ถูกอัปเดตโดยผู้ผลิตที่เป็นเจ้าของส่วนนี้เท่านั้น ผู้ผลิตคนต่อไปที่เปิดเอกสารนี้จะต้องอัปเดตความสัมพันธ์ของลิงก์ไฮเปอร์ด้วยลิงก์ใหม่ที่ระบุในส่วนนี้ อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public abstract int getSlides()
```

ระบุจำนวนสไลด์ทั้งหมดในเอกสารงานนำเสนอ อ่านอย่างเดียว int.

**คืนค่า:**
int
### getHiddenSlides() {#getHiddenSlides--}
```
public abstract int getHiddenSlides()
```

ระบุจำนวนสไลด์ที่ซ่อนอยู่ในเอกสารงานนำเสนอ อ่านอย่างเดียว int.

**คืนค่า:**
int
### getNotes() {#getNotes--}
```
public abstract int getNotes()
```

ระบุจำนวนสไลด์ในงานนำเสนอที่มีโน้ต อ่านอย่างเดียว int.

**คืนค่า:**
int
### getParagraphs() {#getParagraphs--}
```
public abstract int getParagraphs()
```

ระบุจำนวนย่อหน้าทั้งหมดที่พบในเอกสาร (ถ้ามี) อ่านอย่างเดียว int.

**คืนค่า:**
int
### getWords() {#getWords--}
```
public abstract int getWords()
```

ระบุจำนวนคำทั้งหมดที่อยู่ในเอกสาร อ่านอย่างเดียว int.

**คืนค่า:**
int
### getMultimediaClips() {#getMultimediaClips--}
```
public abstract int getMultimediaClips()
```

ระบุจำนวนคลิปเสียงหรือวิดีโอที่อยู่ในเอกสาร อ่านอย่างเดียว int.

**คืนค่า:**
int
### getTitlesOfParts() {#getTitlesOfParts--}
```
public abstract String[] getTitlesOfParts()
```

ระบุชื่อของแต่ละส่วนของเอกสาร ส่วนเหล่านี้ไม่ใช่ส่วนของเอกสารจริง แต่เป็นการแทนส่วนของเอกสารแบบเชิงแนวคิด อ่านอย่างเดียว String[].

**คืนค่า:**
java.lang.String[]
### getHeadingPairs() {#getHeadingPairs--}
```
public abstract IHeadingPair[] getHeadingPairs()
```

ระบุการจัดกลุ่มของส่วนเอกสารและจำนวนส่วนในแต่ละกลุ่ม อ่านอย่างเดียว IHeadingPair[].

**คืนค่า:**
com.aspose.slides.IHeadingPair[]
### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public abstract int getCountOfCustomProperties()
```

คืนจำนวนคุณสมบัติกำหนดเองที่มีอยู่จริงในคอลเลกชัน อ่านอย่างเดียว int.

**คืนค่า:**
int
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public abstract String getCustomPropertyName(int index)
```

คืนชื่อคุณสมบัติกำหนดเองที่ตำแหน่งที่กำหนด

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีเริ่มจากศูนย์ของคุณสมบัติกำหนดเองที่ต้องการดึง |

**คืนค่า:**
java.lang.String - ชื่อคุณสมบัติกำหนดเองที่ตำแหน่งที่กำหนด
### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public abstract boolean removeCustomProperty(String name)
```

ลบคุณสมบัติกำหนดเองที่สัมพันธ์กับชื่อที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติกำหนดเองที่ต้องการลบ |

**คืนค่า:**
boolean - คืนค่า true หากมีการลบคุณสมบัติ, false หากไม่ลบ
### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public abstract boolean containsCustomProperty(String name)
```

ตรวจสอบการมีอยู่ของคุณสมบัติกำหนดเองที่มีชื่อระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติกำหนดเองที่ต้องการตรวจสอบ |

**คืนค่า:**
boolean - คืนค่า true หากมีคุณสมบัตินั้น, false หากไม่มี
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract Object get_Item(String name)
```

คืนหรือกำหนดคุณสมบัติกำหนดเองที่สัมพันธ์กับชื่อที่ระบุ อ่าน/เขียน Object.

--------------------

ค่าอาจเป็น **int**, **float**, **double**, **String**, **boolean** หรือ **Date**.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String |  |

**คืนค่า:**
java.lang.Object
### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public abstract void set_Item(String name, Object value)
```

คืนหรือกำหนดคุณสมบัติกำหนดเองที่สัมพันธ์กับชื่อที่ระบุ อ่าน/เขียน Object.

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

ลบคุณสมบัติกำหนดเองทั้งหมด

### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public abstract void clearBuiltInProperties()
```

ล้างและตั้งค่าเริ่มต้นสำหรับคุณสมบัติกำหนดเองทั้งหมด

### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public abstract void getCustomPropertyValue(String name, boolean[] value)
```

ดึงค่าบูลีนที่ระบุชื่อจากคุณสมบัติกำหนดเอง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติกำหนดเองที่ต้องการดึง |
| value | boolean[] | ค่าโดยอ้างอิงของคุณสมบัติ |

### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public abstract void getCustomPropertyValue(String name, int[] value)
```

ดึงค่าจำนวนเต็มที่ระบุชื่อจากคุณสมบัติกำหนดเอง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติกำหนดเองที่ต้องการดึง |
| value | int[] | ค่าโดยอ้างอิงของคุณสมบัติ |

### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public abstract void getCustomPropertyValue(String name, Date[] value)
```

ดึงค่าประเภท DateTime ที่ระบุชื่อจากคุณสมบัติกำหนดเอง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติกำหนดเองที่ต้องการดึง |
| value | java.util.Date[] | ค่าโดยอ้างอิงของคุณสมบัติ |

### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public abstract void getCustomPropertyValue(String name, String[] value)
```

ดึงค่าข้อความที่ระบุชื่อจากคุณสมบัติกำหนดเอง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติกำหนดเองที่ต้องการดึง |
| value | java.lang.String[] | ค่าโดยอ้างอิงของคุณสมบัติ |

### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public abstract void getCustomPropertyValue(String name, float[] value)
```

ดึงค่าจำนวนจริงแบบ float ที่ระบุชื่อจากคุณสมบัติกำหนดเอง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติกำหนดเองที่ต้องการดึง |
| value | float[] | ค่าโดยอ้างอิงของคุณสมบัติ |

### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public abstract void getCustomPropertyValue(String name, double[] value)
```

ดึงค่าจำนวนจริงแบบ double ที่ระบุชื่อจากคุณสมบัติกำหนดเอง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
...
| ชื่อ | java.lang.String | ชื่อของคุณสมบัติกำหนดเองที่ต้องการรับ |
| ค่า | double[] | ค่าของคุณสมบัติกำหนดเอง |

### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public abstract void setCustomPropertyValue(String name, boolean value)
```

ตั้งค่าคุณสมบัติกำหนดเองประเภทบูลีนที่มีชื่อ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติกำหนดเองที่ต้องตั้งค่า |
| value | boolean | ค่าของคุณสมบัติกำหนดเอง |

### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public abstract void setCustomPropertyValue(String name, int value)
```

ตั้งค่าคุณสมบัติกำหนดเองประเภทจำนวนเต็มที่มีชื่อ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติกำหนดเองที่ต้องตั้งค่า |
| value | int | ค่าของคุณสมบัติกำหนดเอง |

### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public abstract void setCustomPropertyValue(String name, Date value)
```

ตั้งค่าคุณสมบัติกำหนดเองประเภทวัน\-เวลา (DateTime) ที่มีชื่อ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติกำหนดเองที่ต้องตั้งค่า |
| value | java.util.Date | ค่าของคุณสมบัติกำหนดเอง |

### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public abstract void setCustomPropertyValue(String name, String value)
```

ตั้งค่าคุณสมบัติกำหนดเองประเภทสตริงที่มีชื่อ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติกำหนดเองที่ต้องตั้งค่า |
| value | java.lang.String | ค่าของคุณสมบัติกำหนดเอง |

### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public abstract void setCustomPropertyValue(String name, float value)
```

ตั้งค่าคุณสมบัติกำหนดเองประเภทฟลตที่มีชื่อ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติกำหนดเองที่ต้องตั้งค่า |
| value | float | ค่าของคุณสมบัติกำหนดเอง |

### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public abstract void setCustomPropertyValue(String name, double value)
```

ตั้งค่าคุณสมบัติกำหนดเองประเภทดับเบิลที่มีชื่อ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติกำหนดเองที่ต้องตั้งค่า |
| value | double | ค่าของคุณสมบัติกำหนดเอง |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabel[] getSensitivityLabels()
```

ดึงอาเรย์ของป้ายความไวจากคุณสมบัติกำหนดเองของเอกสาร (Microsoft Information Protection SDK Metadata)

--------------------

> ```
> The following code shows how to move the sensitivity labels information from the custom document properties 
>   to the modern SensitivityLabels collection:
>   
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // ดึงฉลากความอ่อนไหวจากคุณสมบัติเอกสารที่กำหนดเอง
>      ISensitivityLabel[] mipSensitivityLabels = pres.getDocumentProperties().getSensitivityLabels();
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
>      for (ISensitivityLabel sensitivityLabel : mipSensitivityLabels)
>      {
>          // เพิ่มฉลากลงในคอลเลคชัน
>          // ที่นี่คุณสามารถเพิ่มการตรวจสอบความถูกต้องของข้อมูลฉลาก (ฉลากมีอยู่ เป็นต้น)
>          sensitivityLabels.add(sensitivityLabel);
>      }
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**คืนค่า:**
com.aspose.slides.ISensitivityLabel[]