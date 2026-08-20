---
title: ILoadOptions
second_title: Aspose.Slides for Java API Reference
description: อนุญาตให้ระบุตัวเลือกเพิ่มเติมเช่นรูปแบบหรือแบบอักษรเริ่มต้นเมื่อโหลดงานนำเสนอ
type: docs
url: /th/com.aspose.slides/iloadoptions/
---```
public interface ILoadOptions
```

อนุญาตให้ระบุตัวเลือกเพิ่มเติม (เช่นรูปแบบหรือแบบอักษรเริ่มต้น) เมื่อโหลดงานนำเสนอ
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | คืนหรือกำหนดรูปแบบของงานนำเสนอที่จะโหลด. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | คืนหรือกำหนดรูปแบบของงานนำเสนอที่จะโหลด. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | คืนหรือกำหนดแบบอักษร Regular ที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นฉบับ. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | คืนหรือกำหนดแบบอักษร Regular ที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นฉบับ. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | คืนหรือกำหนดแบบอักษร Symbol ที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นฉบับ. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | คืนหรือกำหนดแบบอักษร Symbol ที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นฉบับ. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | คืนหรือกำหนดแบบอักษร Asian ที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นฉบับ. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | คืนหรือกำหนดแบบอักษร Asian ที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นฉบับ. |
| [getPassword()](#getPassword--) | รับหรือกำหนดรหัสผ่าน. |
| [setPassword(String value)](#setPassword-java.lang.String-) | รับหรือกำหนดรหัสผ่าน. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | คุณสมบัตินี้มีความหมาย หากไฟล์งานนำเสนอถูกป้องกันด้วยรหัสผ่าน. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | คุณสมบัตินี้มีความหมาย หากไฟล์งานนำเสนอถูกป้องกันด้วยรหัสผ่าน. |
| [getWarningCallback()](#getWarningCallback--) | คืนหรือกำหนดอ็อบเจ็กต์ที่รับคำเตือนและตัดสินว่ากระบวนการโหลดจะดำเนินต่อหรือยกเลิก. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | คืนหรือกำหนดอ็อบเจ็กต์ที่รับคำเตือนและตัดสินว่ากระบวนการโหลดจะดำเนินต่อหรือยกเลิก. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | แสดงตัวเลือกที่สามารถใช้จัดการพฤติกรรมการจัดการ Binary Large Objects (BLOBs) เช่นการใช้ไฟล์ชั่วคราวหรือจำนวนไบต์สูงสุดของ BLOBs ในหน่วยความจำ. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | แสดงตัวเลือกที่สามารถใช้จัดการพฤติกรรมการจัดการ Binary Large Objects (BLOBs) เช่นการใช้ไฟล์ชั่วคราวหรือจำนวนไบต์สูงสุดของ BLOBs ในหน่วยความจำ. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | ระบุแหล่งที่มาของแบบอักษรภายนอกที่จะใช้ในงานนำเสนอ. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | ระบุแหล่งที่มาของแบบอักษรภายนอกที่จะใช้ในงานนำเสนอ. |
| [getInterruptionToken()](#getInterruptionToken--) | โทเคนเพื่อตรวจสอบคำขอการหยุดชั่วคราว. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | โทเคนเพื่อตรวจสอบคำขอการหยุดชั่วคราว. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | คืนหรือกำหนดอินเทอร์เฟซ callback ที่จัดการการโหลดทรัพยากรภายนอก. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | คืนหรือกำหนดอินเทอร์เฟซ callback ที่จัดการการโหลดทรัพยากรภายนอก. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | แสดงตัวเลือกที่สามารถใช้กำหนดพฤติกรรมเพิ่มเติมของสเปรดชีต. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | แสดงตัวเลือกที่สามารถใช้กำหนดพฤติกรรมเพิ่มเติมของสเปรดชีต. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | คืนหรือกำหนดภาษาตั้งต้นสำหรับข้อความของงานนำเสนอ. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | คืนหรือกำหนดภาษาตั้งต้นสำหรับข้อความของงานนำเสนอ. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | กำหนดว่า Aspose.Slides จะลบอ็อบเจ็กต์ไบนารีที่ฝังอยู่ทั้งหมดขณะโหลดงานนำเสนอหรือไม่. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | กำหนดว่า Aspose.Slides จะลบอ็อบเจ็กต์ไบนารีที่ฝังอยู่ทั้งหมดขณะโหลดงานนำเสนอหรือไม่. |

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

คืนหรือกำหนดแบบอักษร Regular ที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นฉบับ. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String

### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```

คืนหรือกำหนดแบบอักษร Regular ที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นฉบับ. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public abstract String getDefaultSymbolFont()
```

คืนหรือกำหนดแบบอักษร Symbol ที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นฉบับ. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String

### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public abstract void setDefaultSymbolFont(String value)
```

คืนหรือกำหนดแบบอักษร Symbol ที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นฉบับ. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public abstract String getDefaultAsianFont()
```

คืนหรือกำหนดแบบอักษร Asian ที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นฉบับ. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String

### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public abstract void setDefaultAsianFont(String value)
```

คืนหรือกำหนดแบบอักษร Asian ที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นฉบับ. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

รับหรือกำหนดรหัสผ่าน. อ่าน/เขียน String.

ค่า: รหัสผ่าน.

**คืนค่า:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

รับหรือกำหนดรหัสผ่าน. อ่าน/เขียน String.

ค่า: รหัสผ่าน.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public abstract boolean getOnlyLoadDocumentProperties()
```

คุณสมบัตินี้มีความหมาย หากไฟล์งานนำเสนอถูกป้องกันด้วยรหัสผ่าน. ค่า true หมายถึงว่าจะโหลดเฉพาะคุณสมบัติของเอกสารจากไฟล์งานนำเสนอที่เข้ารหัสและจะละเว้นรหัสผ่าน. ค่า false หมายถึงว่าจะโหลดงานนำเสนอที่เข้ารหัสทั้งหมดโดยใช้รหัสผ่านที่ถูกต้อง. หากงานนำเสนอไม่ได้เข้ารหัส ค่าคุณสมบัติจะและเว้นเสมอ. หากคุณสมบัติของไฟล์ที่เข้ารหัสไม่เป็นสาธารณะและค่าเป็น true แล้วคุณสมบัติของเอกสารจะไม่สามารถโหลดได้และจะเกิดข้อยกเว้น. อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public abstract void setOnlyLoadDocumentProperties(boolean value)
```

คุณสมบัตินี้มีความหมาย หากไฟล์งานนำเสนอถูกป้องกันด้วยรหัสผ่าน. ค่า true หมายถึงว่าจะโหลดเฉพาะคุณสมบัติของเอกสารจากไฟล์งานนำเสนอที่เข้ารหัสและจะละเว้นรหัสผ่าน. ค่า false หมายถึงว่าจะโหลดงานนำเสนอที่เข้ารหัสทั้งหมดโดยใช้รหัสผ่านที่ถูกต้อง. หากงานนำเสนอไม่ได้เข้ารหัส ค่าคุณสมบัติจะและเว้นเสมอ. หากคุณสมบัติของไฟล์ที่เข้ารหัสไม่เป็นสาธารณะและค่าเป็น true แล้วคุณสมบัติของเอกสารจะไม่สามารถโหลดได้และจะเกิดข้อยกเว้น. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```

คืนหรือกำหนดอ็อบเจ็กต์ที่รับคำเตือนและตัดสินว่ากระบวนการโหลดจะดำเนินต่อหรือยกเลิก. อ่าน/เขียน [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**คืนค่า:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```

คืนหรือกำหนดอ็อบเจ็กต์ที่รับคำเตือนและตัดสินว่ากระบวนการโหลดจะดำเนินต่อหรือยกเลิก. อ่าน/เขียน [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public abstract IBlobManagementOptions getBlobManagementOptions()
```

แสดงตัวเลือกที่สามารถใช้จัดการพฤติกรรมการจัดการ Binary Large Objects (BLOBs) เช่นการใช้ไฟล์ชั่วคราวหรือจำนวนไบต์สูงสุดของ BLOBs ในหน่วยความจำ. ตัวเลือกเหล่านี้มีจุดมุ่งหมายเพื่อกำหนดอัตราการใช้ประสิทธิภาพ/หน่วยความจำที่ดีที่สุดสำหรับสภาพแวดล้อมหรือความต้องการเฉพาะ

--------------------

Binary Large Object (BLOB) คือข้อมูลไบนารีที่จัดเก็บเป็นหน่วยเดียว - เช่น BLOB อาจเป็นไฟล์เสียง วิดีโอ หรือแม้กระทั่งงานนำเสนอเอง

**คืนค่า:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)

### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public abstract void setBlobManagementOptions(IBlobManagementOptions value)
```

แสดงตัวเลือกที่สามารถใช้จัดการพฤติกรรมการจัดการ Binary Large Objects (BLOBs) เช่นการใช้ไฟล์ชั่วคราวหรือจำนวนไบต์สูงสุดของ BLOBs ในหน่วยความจำ. ตัวเลือกเหล่านี้มีจุดมุ่งหมายเพื่อกำหนดอัตราการใช้ประสิทธิภาพ/หน่วยความจำที่ดีที่สุดสำหรับสภาพแวดล้อมหรือความต้องการเฉพาะ

--------------------

Binary Large Object (BLOB) คือข้อมูลไบนารีที่จัดเก็บเป็นหน่วยเดียว - เช่น BLOB อาจเป็นไฟล์เสียง วิดีโอ หรือแม้กระทั่งงานนำเสนอเอง

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public abstract IFontSources getDocumentLevelFontSources()
```

ระบุแหล่งที่มาของแบบอักษรภายนอกที่จะใช้ในงานนำเสนอ. แบบอักษรเหล่านี้จะใช้ได้ตลอดอายุของงานนำเสนอและไม่ถูกแชร์กับงานนำเสนออื่น

**คืนค่า:**
[IFontSources](../../com.aspose.slides/ifontsources)

### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public abstract void setDocumentLevelFontSources(IFontSources value)
```

ระบุแหล่งที่มาของแบบอักษรภายนอกที่จะใช้ในงานนำเสนอ. แบบอักษรเหล่านี้จะใช้ได้ตลอดอายุของงานนำเสนอและไม่ถูกแชร์กับงานนำเสนออื่น

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public abstract IInterruptionToken getInterruptionToken()
```

โทเคนเพื่อตรวจสอบคำขอการหยุดชั่วคราว.

--------------------

โทเคนนี้จัดการอายุการใช้งานทั้งหมดของอินสแตนซ์ [IPresentation](../../com.aspose.slides/ipresentation). การทำงานที่ใช้เวลานานใด ๆ เช่นการโหลดหรือการบันทึกงานนำเสนอ จะถูกหยุดโดยการเรียกเมธอด [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) ของ [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**คืนค่า:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)

### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public abstract void setInterruptionToken(IInterruptionToken value)
```

โทเคนเพื่อตรวจสอบคำขอการหยุดชั่วคราว.

--------------------

โทเคนนี้จัดการอายุการใช้งานทั้งหมดของอินสแตนซ์ [IPresentation](../../com.aspose.slides/ipresentation). การทำงานที่ใช้เวลานานใด ๆ เช่นการโหลดหรือการบันทึกงานนำเสนอ จะถูกหยุดโดยการเรียกเมธอด [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) ของ [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

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

แสดงตัวเลือกที่สามารถใช้กำหนดพฤติกรรมเพิ่มเติมของสเปรดชีต.

**คืนค่า:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)

### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public abstract void setSpreadsheetOptions(ISpreadsheetOptions value)
```

แสดงตัวเลือกที่สามารถใช้กำหนดพฤติกรรมเพิ่มเติมของสเปรดชีต.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public abstract String getDefaultTextLanguage()
```

คืนหรือกำหนดภาษาตั้งต้นสำหรับข้อความของงานนำเสนอ. อ่าน/เขียน String.

--------------------

> ```
> Example:
>   
>  // ใช้ตัวเลือกการโหลดเพื่อกำหนดวัฒนธรรมข้อความเริ่มต้น
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // เพิ่มรูปร่างสี่เหลี่ยมจัตุรัสใหม่พร้อมข้อความ
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

คืนหรือกำหนดภาษาตั้งต้นสำหรับข้อความของงานนำเสนอ. อ่าน/เขียน String.

--------------------

> ```
> Example:
>   
>  // ใช้ตัวเลือกการโหลดเพื่อกำหนดวัฒนธรรมข้อความเริ่มต้น
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // เพิ่มรูปร่างสี่เหลี่ยมจัตุรัสใหม่พร้อมข้อความ
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

กำหนดว่า Aspose.Slides จะลบอ็อบเจ็กต์ไบนารีที่ฝังอยู่ทั้งหมดขณะโหลดงานนำเสนอหรือไม่.

The types of the embedded binary objects:

 *  
 *  
 *  

อ่าน/เขียน boolean.

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

ค่าเริ่มต้นคือ **false** .

**คืนค่า:**
boolean

### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public abstract void setDeleteEmbeddedBinaryObjects(boolean value)
```

กำหนดว่า Aspose.Slides จะลบอ็อบเจ็กต์ไบนารีที่ฝังอยู่ทั้งหมดขณะโหลดงานนำเสนอหรือไม่.

The types of the embedded binary objects:

 *  
 *  
 *  

อ่าน/เขียน boolean.

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

ค่าเริ่มต้นคือ **false** .

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |