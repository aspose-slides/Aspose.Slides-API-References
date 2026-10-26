---
title: ILoadOptions
second_title: Aspose.Slides for Android via Java API Reference
description: อนุญาตให้ระบุตัวเลือกเพิ่มเติม เช่น รูปแบบหรือฟอนต์เริ่มต้นเมื่อโหลดงานนำเสนอ
type: docs
url: /th/com.aspose.slides/iloadoptions/
---```
public interface ILoadOptions
```

อนุญาตให้ระบุตัวเลือกเพิ่มเติม (เช่น รูปแบบหรือฟอนต์เริ่มต้น) เมื่อโหลดงานนำเสนอ
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | คืนหรือกำหนดรูปแบบของงานนำเสนอที่จะโหลด |
| [setLoadFormat(int value)](#setLoadFormat-int-) | คืนหรือกำหนดรูปแบบของงานนำเสนอที่จะโหลด |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | คืนหรือกำหนดฟอนต์ Regular ที่ใช้เมื่อไม่พบฟอนต์ต้นทาง |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | คืนหรือกำหนดฟอนต์ Regular ที่ใช้เมื่อไม่พบฟอนต์ต้นทาง |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | คืนหรือกำหนดฟอนต์ Symbol ที่ใช้เมื่อไม่พบฟอนต์ต้นทาง |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | คืนหรือกำหนดฟอนต์ Symbol ที่ใช้เมื่อไม่พบฟอนต์ต้นทาง |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | คืนหรือกำหนดฟอนต์ Asian ที่ใช้เมื่อไม่พบฟอนต์ต้นทาง |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | คืนหรือกำหนดฟอนต์ Asian ที่ใช้เมื่อไม่พบฟอนต์ต้นทาง |
| [getPassword()](#getPassword--) | รับหรือกำหนดรหัสผ่าน |
| [setPassword(String value)](#setPassword-java.lang.String-) | รับหรือกำหนดรหัสผ่าน |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | คุณสมบัตินี้มีความหมายเมื่อไฟล์งานนำเสนอถูกป้องกันด้วยรหัสผ่าน |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | คุณสมบัตินี้มีความหมายเมื่อไฟล์งานนำเสนอถูกป้องกันด้วยรหัสผ่าน |
| [getWarningCallback()](#getWarningCallback--) | คืนหรือกำหนดออบเจ็กต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือยกเลิก |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | คืนหรือกำหนดออบเจ็กต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือยกเลิก |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | แทนตัวเลือกที่ใช้จัดการพฤติกรรมการจัดการ Binary Large Objects (BLOB) เช่น การใช้ไฟล์ชั่วคราวหรือขนาดสูงสุดของ BLOB ในหน่วยความจำ |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | แทนตัวเลือกที่ใช้จัดการพฤติกรรมการจัดการ Binary Large Objects (BLOB) เช่น การใช้ไฟล์ชั่วคราวหรือขนาดสูงสุดของ BLOB ในหน่วยความจำ |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | ระบุแหล่งที่มาของฟอนต์ภายนอกที่จะใช้ในงานนำเสนอ |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | ระบุแหล่งที่มาของฟอนต์ภายนอกที่จะใช้ในงานนำเสนอ |
| [getInterruptionToken()](#getInterruptionToken--) | โทเค็นเพื่อตรวจสอบคำร้องขอการขัดจังหวะ |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | โทเค็นเพื่อตรวจสอบคำร้องขอการขัดจังหวะ |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | คืนหรือกำหนดอินเทอร์เฟซ callback ที่จัดการการโหลดทรัพยากรภายนอก |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | คืนหรือกำหนดอินเทอร์เฟซ callback ที่จัดการการโหลดทรัพยากรภายนอก |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | แทนตัวเลือกที่ใช้ระบุพฤติกรรมเพิ่มเติมของสเปรดชีต |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | แทนตัวเลือกที่ใช้ระบุพฤติกรรมเพิ่มเติมของสเปรดชีต |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | คืนหรือกำหนดภาษาตั้งต้นสำหรับข้อความในงานนำเสนอ |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | คืนหรือกำหนดภาษาตั้งต้นสำหรับข้อความในงานนำเสนอ |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | กำหนดว่า Aspose.Slides จะลบออบเจ็กต์ไบนารีที่ฝังอยู่ทั้งหมดขณะโหลดงานนำเสนอหรือไม่ |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | กำหนดว่า Aspose.Slides จะลบออบเจ็กต์ไบนารีที่ฝังอยู่ทั้งหมดขณะโหลดงานนำเสนอหรือไม่ |
### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

คืนหรือกำหนดรูปแบบของงานนำเสนอที่จะโหลด. อ่าน/เขียน [LoadFormat](../../com.aspose.slides/loadformat).

**คืนค่า:**
int
### setLoadFormat(int value) {#setLoadFormat-int-}
```
public abstract void setLoadFormat(int value)
```

คืนหรือกำหนดรูปแบบของงานนำเสนอที่จะโหลด. อ่าน/เขียน [LoadFormat](../../com.aspose.slides/loadformat).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```

คืนหรือกำหนดฟอนต์ Regular ที่ใช้เมื่อไม่พบฟอนต์ต้นทาง. อ่าน-เขียน String.

**คืนค่า:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```

คืนหรือกำหนดฟอนต์ Regular ที่ใช้เมื่อไม่พบฟอนต์ต้นทาง. อ่าน-เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public abstract String getDefaultSymbolFont()
```

คืนหรือกำหนดฟอนต์ Symbol ที่ใช้เมื่อไม่พบฟอนต์ต้นทาง. อ่าน-เขียน String.

**คืนค่า:**
java.lang.String
### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public abstract void setDefaultSymbolFont(String value)
```

คืนหรือกำหนดฟอนต์ Symbol ที่ใช้เมื่อไม่พบฟอนต์ต้นทาง. อ่าน-เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public abstract String getDefaultAsianFont()
```

คืนหรือกำหนดฟอนต์ Asian ที่ใช้เมื่อไม่พบฟอนต์ต้นทาง. อ่าน-เขียน String.

**คืนค่า:**
java.lang.String
### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public abstract void setDefaultAsianFont(String value)
```

คืนหรือกำหนดฟอนต์ Asian ที่ใช้เมื่อไม่พบฟอนต์ต้นทาง. อ่าน-เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

รับหรือกำหนดรหัสผ่าน. อ่าน-เขียน String.

ค่า: รหัสผ่าน

**คืนค่า:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

รับหรือกำหนดรหัสผ่าน. อ่าน-เขียน String.

ค่า: รหัสผ่าน

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public abstract boolean getOnlyLoadDocumentProperties()
```

คุณสมบัตินี้มีความหมายเมื่อไฟล์งานนำเสนอถูกป้องกันด้วยรหัสผ่าน. ค่า true หมายความว่าจะโหลดเฉพาะคุณสมบัติเบื้องต้นของเอกสารจากไฟล์งานนำเสนอที่เข้ารหัสและจะละเว้นรหัสผ่าน. ค่า false หมายความว่าจะโหลดงานนำเสนอที่เข้ารหัสทั้งหมดโดยใช้รหัสผ่านที่ถูกต้อง. หากงานนำเสนอไม่ได้เข้ารหัสคุณสมบัตินี้จะถูกละเว้นเสมอ. หากคุณสมบัติของไฟล์ที่เข้ารหัสไม่เป็นสาธารณะและค่าเป็น true จะไม่สามารถโหลดคุณสมบัติเบื้องต้นได้และจะเกิดข้อยกเว้น. อ่าน-เขียน boolean.

**คืนค่า:**
boolean
### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public abstract void setOnlyLoadDocumentProperties(boolean value)
```

คุณสมบัตินี้มีความหมายเมื่อไฟล์งานนำเสนอถูกป้องกันด้วยรหัสผ่าน. ค่า true หมายความว่าจะโหลดเฉพาะคุณสมบัติเบื้องต้นของเอกสารจากไฟล์งานนำเสนอที่เข้ารหัสและจะละเว้นรหัสผ่าน. ค่า false หมายความว่าจะโหลดงานนำเสนอที่เข้ารหัสทั้งหมดโดยใช้รหัสผ่านที่ถูกต้อง. หากงานนำเสนอไม่ได้เข้ารหัสคุณสมบัตินี้จะถูกละเว้นเสมอ. หากคุณสมบัติของไฟล์ที่เข้ารหัสไม่เป็นสาธารณะและค่าเป็น true จะไม่สามารถโหลดคุณสมบัติเบื้องต้นได้และจะเกิดข้อยกเว้น. อ่าน-เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```

คืนหรือกำหนดออบเจ็กต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือยกเลิก. อ่าน/เขียน [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**คืนค่า:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```

คืนหรือกำหนดออบเจ็กต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือยกเลิก. อ่าน/เขียน [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public abstract IBlobManagementOptions getBlobManagementOptions()
```

แทนตัวเลือกที่ใช้จัดการพฤติกรรมการจัดการ Binary Large Objects (BLOB) เช่น การใช้ไฟล์ชั่วคราวหรือขนาดสูงสุดของ BLOB ในหน่วยความจำ ตัวเลือกเหล่านี้ออกแบบมาเพื่อกำหนดอัตราส่วนประสิทธิภาพ/การใช้หน่วยความจำที่ดีที่สุดสำหรับสภาพแวดล้อมหรือความต้องการเฉพาะ

--------------------

Binary Large Object (BLOB) คือข้อมูลไบนารีที่เก็บเป็นเอนทิตีเดียว เช่น BLOB อาจเป็นไฟล์เสียง วิดีโอ หรือแม้กระทั่งงานนำเสนอเอง

**คืนค่า:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public abstract void setBlobManagementOptions(IBlobManagementOptions value)
```

แทนตัวเลือกที่ใช้จัดการพฤติกรรมการจัดการ Binary Large Objects (BLOB) เช่น การใช้ไฟล์ชั่วคราวหรือขนาดสูงสุดของ BLOB ในหน่วยความจำ ตัวเลือกเหล่านี้ออกแบบมาเพื่อกำหนดอัตราส่วนประสิทธิภาพ/การใช้หน่วยความจำที่ดีที่สุดสำหรับสภาพแวดล้อมหรือความต้องการเฉพาะ

--------------------

Binary Large Object (BLOB) คือข้อมูลไบนารีที่เก็บเป็นเอนทิตีเดียว เช่น BLOB อาจเป็นไฟล์เสียง วิดีโอ หรือแม้กระทั่งงานนำเสนอเอง

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public abstract IFontSources getDocumentLevelFontSources()
```

ระบุแหล่งที่มาของฟอนต์ภายนอกที่จะใช้ในงานนำเสนอ ฟอนต์เหล่านี้จะพร้อมใช้งานตลอดอายุของงานนำเสนอและจะไม่แชร์กับงานนำเสนออื่น

**คืนค่า:**
[IFontSources](../../com.aspose.slides/ifontsources)
### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public abstract void setDocumentLevelFontSources(IFontSources value)
```

ระบุแหล่งที่มาของฟอนต์ภายนอกที่จะใช้ในงานนำเสนอ ฟอนต์เหล่านี้จะพร้อมใช้งานตลอดอายุของงานนำเสนอและจะไม่แชร์กับงานนำเสนออื่น

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public abstract IInterruptionToken getInterruptionToken()
```

โทเค็นเพื่อตรวจสอบคำร้องขอการขัดจังหวะ

--------------------

โทเค็นนี้จัดการอายุการใช้งานของอินสแตนซ์ [IPresentation](../../com.aspose.slides/ipresentation) ทั้งหมด การดำเนินการที่ใช้เวลานาน เช่น การโหลดหรือบันทึกงานนำเสนอ จะถูกขัดจังหวะโดยการเรียกเมธอด [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) ของ [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource)

**คืนค่า:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public abstract void setInterruptionToken(IInterruptionToken value)
```

โทเค็นเพื่อตรวจสอบคำร้องขอการขัดจังหวะ

--------------------

โทเค็นนี้จัดการอายุการใช้งานของอินสแตนซ์ [IPresentation](../../com.aspose.slides/ipresentation) ทั้งหมด การดำเนินการที่ใช้เวลานาน เช่น การโหลดหรือบันทึกงานนำเสนอ จะถูกขัดจังหวะโดยการเรียกเมธอด [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) ของ [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource)

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public abstract IResourceLoadingCallback getResourceLoadingCallback()
```

คืนหรือกำหนดอินเทอร์เฟซ callback ที่จัดการการโหลดทรัพยากรภายนอก. อ่าน/เขียน [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**คืนค่า:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)
### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public abstract void setResourceLoadingCallback(IResourceLoadingCallback value)
```

คืนหรือกำหนดอินเทอร์เฟซ callback ที่จัดการการโหลดทรัพยากรภายนอก. อ่าน/เขียน [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public abstract ISpreadsheetOptions getSpreadsheetOptions()
```

แทนตัวเลือกที่ใช้ระบุพฤติกรรมเพิ่มเติมของสเปรดชีต

**คืนค่า:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public abstract void setSpreadsheetOptions(ISpreadsheetOptions value)
```

แทนตัวเลือกที่ใช้ระบุพฤติกรรมเพิ่มเติมของสเปรดชีต

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public abstract String getDefaultTextLanguage()
```

คืนหรือกำหนดภาษาตั้งต้นสำหรับข้อความในงานนำเสนอ. อ่าน/เขียน String.

--------------------

> ```
> Example:
>   
>  // ใช้ตัวเลือกการโหลดเพื่อกำหนดภาษาข้อความเริ่มต้น
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // เพิ่มรูปสี่เหลี่ยมผืนผ้าใหม่พร้อมข้อความ
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // ตรวจสอบภาษาของส่วนแรก
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**คืนค่า:**
java.lang.String
### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public abstract void setDefaultTextLanguage(String value)
```

คืนหรือกำหนดภาษาตั้งต้นสำหรับข้อความในงานนำเสนอ. อ่าน/เขียน String.

--------------------

> ```
> Example:
>   
>  // ใช้ตัวเลือกการโหลดเพื่อกำหนดวัฒนธรรมข้อความเริ่มต้น
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // เพิ่มรูปสี่เหลี่ยมผืนผ้าใหม่พร้อมข้อความ
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // ตรวจสอบภาษาของส่วนแรก
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getDeleteEmbeddedBinaryObjects() {#getDeleteEmbeddedBinaryObjects--}
```
public abstract boolean getDeleteEmbeddedBinaryObjects()
```

กำหนดว่า Aspose.Slides จะลบออบเจ็กต์ไบนารีที่ฝังอยู่ทั้งหมดขณะโหลดงานนำเสนอ

ประเภทของออบเจ็กต์ไบนารีที่ฝังอยู่:

 *  
 *  
 *  

อ่าน/เขียน  boolean .

--------------------

> ```
> The following example shows how to load the presentation without any embedded binary objects.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDeleteEmbeddedBinaryObjects(true);
>  Presentation pres = new Presentation("pres.ppt", loadOptions);
>  try {
>      pres.save("output_WithoutBinaryObjects.ppt", SaveFormat.Ppt);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

ค่าเริ่มต้นคือ  **false** .

**คืนค่า:**
boolean
### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public abstract void setDeleteEmbeddedBinaryObjects(boolean value)
```

กำหนดว่า Aspose.Slides จะลบออบเจ็กต์ไบนารีที่ฝังอยู่ทั้งหมดขณะโหลดงานนำเสนอ

ประเภทของออบเจ็กต์ไบนารีที่ฝังอยู่:

 *  
 *  
 *  

อ่าน/เขียน  boolean .

--------------------

> ```
> The following example shows how to load the presentation without any embedded binary objects.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDeleteEmbeddedBinaryObjects(true);
>  Presentation pres = new Presentation("pres.ppt", loadOptions);
>  try {
>      pres.save("output_WithoutBinaryObjects.ppt", SaveFormat.Ppt);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

ค่าเริ่มต้นคือ  **false** .

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |