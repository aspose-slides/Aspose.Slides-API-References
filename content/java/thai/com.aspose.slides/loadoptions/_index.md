---
title: LoadOptions
second_title: Aspose.Slides สำหรับ Java API Reference
description: อนุญาตให้ระบุตัวเลือกเพิ่มเติม เช่น รูปแบบหรือแบบอักษรเริ่มต้นเมื่อโหลดงานนำเสนอ.
type: docs
url: /th/com.aspose.slides/loadoptions/
---
**สืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ใช้งานทั้งหมด:**
[com.aspose.slides.ILoadOptions](../../com.aspose.slides/iloadoptions)
```
public class LoadOptions implements ILoadOptions
```

อนุญาตให้ระบุตัวเลือกเพิ่มเติม (เช่น รูปแบบหรือแบบอักษรเริ่มต้น) เมื่อโหลดงานนำเสนอ.
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | สร้างตัวเลือกการโหลดแบบเริ่มต้นใหม่ |
| [LoadOptions(int loadFormat)](#LoadOptions-int-) | สร้างตัวเลือกการโหลดใหม่ |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | คืนค่า หรือกำหนดรูปแบบของงานนำเสนอที่ต้องการโหลด |
| [setLoadFormat(int value)](#setLoadFormat-int-) | คืนค่า หรือกำหนดรูปแบบของงานนำเสนอที่ต้องการโหลด |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | คืนค่า หรือกำหนดแบบอักษร Regular ที่ใช้เมื่อไม่พบแบบอักษรต้นทาง |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | คืนค่า หรือกำหนดแบบอักษร Regular ที่ใช้เมื่อไม่พบแบบอักษรต้นทาง |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | คืนค่า หรือกำหนดแบบอักษร Symbol ที่ใช้เมื่อไม่พบแบบอักษรต้นทาง |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | คืนค่า หรือกำหนดแบบอักษร Symbol ที่ใช้เมื่อไม่พบแบบอักษรต้นทาง |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | คืนค่า หรือกำหนดแบบอักษร Asian ที่ใช้เมื่อไม่พบแบบอักษรต้นทาง |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | คืนค่า หรือกำหนดแบบอักษร Asian ที่ใช้เมื่อไม่พบแบบอักษรต้นทาง |
| [getPassword()](#getPassword--) | รับหรือกำหนดรหัสผ่าน |
| [setPassword(String value)](#setPassword-java.lang.String-) | รับหรือกำหนดรหัสผ่าน |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | คุณสมบัตินี้มีความหมายเมื่อไฟล์งานนำเสนอถูกป้องกันด้วยรหัสผ่าน |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | คุณสมบัตินี้มีความหมายเมื่อไฟล์งานนำเสนอถูกป้องกันด้วยรหัสผ่าน |
| [getWarningCallback()](#getWarningCallback--) | คืนค่า หรือกำหนดอ็อบเจ็กต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือหยุด |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | คืนค่า หรือกำหนดอ็อบเจ็กต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือหยุด |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | แสดงตัวเลือกที่ใช้จัดการพฤติกรรมการจัดการ Binary Large Objects (BLOBs) เช่น การใช้ไฟล์ชั่วคราวหรือจำนวนไบต์สูงสุดของ BLOBs ในหน่วยความจำ |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | แสดงตัวเลือกที่ใช้จัดการพฤติกรรมการจัดการ Binary Large Objects (BLOBs) เช่น การใช้ไฟล์ชั่วคราวหรือจำนวนไบต์สูงสุดของ BLOBs ในหน่วยความจำ |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | ระบุแหล่งที่มาสำหรับแบบอักษรภายนอกที่จะใช้กับงานนำเสนอ |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | ระบุแหล่งที่มาสำหรับแบบอักษรภายนอกที่จะใช้กับงานนำเสนอ |
| [getInterruptionToken()](#getInterruptionToken--) | โทเค็นสำหรับตรวจสอบคำขอขัดจังหวะ |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | โทเค็นสำหรับตรวจสอบคำขอขัดจังหวะ |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | คืนค่า หรือกำหนดอินเทอร์เฟซ callback ที่จัดการการโหลดทรัพยากรภายนอก |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) |คืนค่า หรือกำหนดอินเทอร์เฟซ callback ที่จัดการการโหลดทรัพยากรภายนอก |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | รับตัวเลือกสำหรับสเปรดชีต |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | รับตัวเลือกสำหรับสเปรดชีต |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | คืนค่า หรือกำหนดภาษาตั้งต้นสำหรับข้อความในงานนำเสนอ |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | คืนค่า หรือกำหนดภาษาตั้งต้นสำหรับข้อความในงานนำเสนอ |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | กำหนดว่า Aspose.Slides จะลบอ็อบเจ็กต์ไบนารีที่ฝังอยู่ทั้งหมดขณะโหลดงานนำเสนอหรือไม่ |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | กำหนดว่า Aspose.Slides จะลบอ็อบเจ็กต์ไบนารีที่ฝังอยู่ทั้งหมดขณะโหลดงานนำเสนอหรือไม่ |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```

สร้างตัวเลือกการโหลดแบบเริ่มต้นใหม่

### LoadOptions(int loadFormat) {#LoadOptions-int-}
```
public LoadOptions(int loadFormat)
```

สร้างตัวเลือกการโหลดใหม่

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| loadFormat | int | รูปแบบของงานนำเสนอที่ต้องการโหลด |

### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

คืนค่า หรือกำหนดรูปแบบของงานนำเสนอที่ต้องการโหลด อ่าน/เขียน [LoadFormat](../../com.aspose.slides/loadformat).

**คืนค่า:**
int
### setLoadFormat(int value) {#setLoadFormat-int-}
```
public final void setLoadFormat(int value)
```

คืนค่า หรือกำหนดรูปแบบของงานนำเสนอที่ต้องการโหลด อ่าน/เขียน [LoadFormat](../../com.aspose.slides/loadformat).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```

คืนค่า หรือกำหนดแบบอักษร Regular ที่ใช้เมื่อไม่พบแบบอักษรต้นทาง อ่าน/เขียน String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // Use load options to define the default regular and asian fonts
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // Load the presentation
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // Generate slide thumbnail
>      BufferedImage slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      ImageIO.write(slideImage, "PNG", new File("output_out.png"));
>      // Generate PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // Generate XPS
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**คืนค่า:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```

คืนค่า หรือกำหนดแบบอักษร Regular ที่ใช้เมื่อไม่พบแบบอักษรต้นทาง อ่าน/เขียน String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // Use load options to define the default regular and asian fonts
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // Load the presentation
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // Generate slide thumbnail
>      BufferedImage slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      ImageIO.write(slideImage, "PNG", new File("output_out.png"));
>      // Generate PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // Generate XPS
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public final String getDefaultSymbolFont()
```

คืนค่า หรือกำหนดแบบอักษร Symbol ที่ใช้เมื่อไม่พบแบบอักษรต้นทาง อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public final void setDefaultSymbolFont(String value)
```

คืนค่า หรือกำหนดแบบอักษร Symbol ที่ใช้เมื่อไม่พบแบบอักษรต้นทาง อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public final String getDefaultAsianFont()
```

คืนค่า หรือกำหนดแบบอักษร Asian ที่ใช้เมื่อไม่พบแบบอักษรต้นทาง อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public final void setDefaultAsianFont(String value)
```

คืนค่า หรือกำหนดแบบอักษร Asian ที่ใช้เมื่อไม่พบแบบอักษรต้นทาง อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

รับหรือกำหนดรหัสผ่าน อ่าน/เขียน String.

--------------------

> ```
> โค้ดตัวอย่างต่อไปนี้แสดงวิธีเปิด PowerPoint Presentation ที่ป้องกันด้วยรหัสผ่าน.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // ทำงานกับงานนำเสนอที่ถอดรหัสแล้ว
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


ค่า: รหัสผ่าน

**คืนค่า:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

รับหรือกำหนดรหัสผ่าน อ่าน/เขียน String.

--------------------

> ```
> The following sample code shows how to open password protected PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // work with decrypted presentation
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

ค่า: รหัสผ่าน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public final boolean getOnlyLoadDocumentProperties()
```

คุณสมบัตินี้มีความหมายเมื่อไฟล์งานนำเสนอถูกป้องกันด้วยรหัสผ่าน ค่า true หมายถึงจะโหลดเฉพาะคุณสมบัติเ�เอกสารจากไฟล์งานนำเสนอที่เข้ารหัสและจะละเลยรหัสผ่าน ค่า false หมายถึงจะโหลดงานนำเสนอที่เข้ารหัสทั้งหมดโดยใช้รหัสผ่านที่ถูกต้อง หากงานนำเสนอไม่ได้เข้ารหัสค่านี้จะถูกละเลยเสมอ หากคุณสมบัติเขเอกสารของไฟล์ที่เข้ารหัสไม่เป็นสาธารณะและค่าเป็น true จะไม่สามารถโหลดคุณสมบัติเขเอกสารได้และจะเกิดข้อยกเว้น อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public final void setOnlyLoadDocumentProperties(boolean value)
```

คุณสมบัตินี้มีความหมายเมื่อไฟล์งานนำเสนอถูกป้องกันด้วยรหัสผ่าน ค่า true หมายถึงจะโหลดเฉพาะคุณสมบัติเขเอกสารจากไฟล์งานนำเสนอที่เข้ารหัสและจะละเลยรหัสผ่าน ค่า false หมายถึงจะโหลดงานนำเสนอที่เข้ารหัสทั้งหมดโดยใช้รหัสผ่านที่ถูกต้อง หากงานนำเสนอไม่ได้เข้ารหัสค่านี้จะถูกละเลยเสมอ หากคุณสมบัติเขเอกสารของไฟล์ที่เข้ารหัสไม่เป็นสาธารณะและค่าเป็น true จะไม่สามารถโหลดคุณสมบัติเขเอกสารได้และจะเกิดข้อยกเว้น อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```

คืนค่า หรือกำหนดอ็อบเจ็กต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือหยุด อ่าน/เขียน [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**คืนค่า:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```

คืนค่า หรือกำหนดอ็อบเจ็กต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือหยุด อ่าน/เขียน [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public final IBlobManagementOptions getBlobManagementOptions()
```

แสดงตัวเลือกที่ใช้จัดการพฤติกรรมการจัดการ Binary Large Objects (BLOBs) เช่น การใช้ไฟล์ชั่วคราวหรือจำนวนไบต์สูงสุดของ BLOBs ในหน่วยความจำ ตัวเลือกเหล่านี้มุ่งหมายให้ตั้งค่าสมดุลระหว่างประสิทธิภาพและการใช้หน่วยความจำสำหรับสภาพแวดล้อมหรือความต้องการเฉพาะ

--------------------

Binary Large Object (BLOB) คือข้อมูลไบนารีที่จัดเก็บเป็นเอนทิตีเดียว เช่น BLOB สามารถเป็นไฟล์เสียง วิดีโอ หรือแม้กระทั่งงานนำเสนอเอง

**คืนค่า:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public final void setBlobManagementOptions(IBlobManagementOptions value)
```

แสดงตัวเลือกที่ใช้จัดการพฤติกรรมการจัดการ Binary Large Objects (BLOBs) เช่น การใช้ไฟล์ชั่วคราวหรือจำนวนไบต์สูงสุดของ BLOBs ในหน่วยความจำ ตัวเลือกเหล่านี้มุ่งหมายให้ตั้งค่าสมดุลระหว่างประสิทธิภาพและการใช้หน่วยความจำสำหรับสภาพแวดล้อมหรือความต้องการเฉพาะ

--------------------

Binary Large Object (BLOB) คือข้อมูลไบนารีที่จัดเก็บเป็นเอนทิตีเดียว เช่น BLOB สามารถเป็นไฟล์เสียง วิดีโอ หรือแม้กระทั่งงานนำเสนอเอง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public final IFontSources getDocumentLevelFontSources()
```

ระบุแหล่งที่มาสำหรับแบบอักษรภายนอกที่จะใช้กับงานนำเสนอ แบบอักษรเหล่านี้จะใช้ได้ตลอดอายุงานของงานนำเสนอและจะไม่ถูกแชร์กับงานนำเสนออื่น

--------------------

> ```
> ตัวอย่างต่อไปนี้แสดงวิธีระบุแบบอักษรที่กำหนดเองที่ใช้กับ PowerPoint Presentation.
>  
>  byte[] memoryFont1 = Files.readAllBytes(Paths.get("customfonts\\CustomFont1.ttf"));
>  byte[] memoryFont2 = Files.readAllBytes(Paths.get("customfonts\\CustomFont2.ttf"));
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  //ทำงานกับงานนำเสนอ
>  //CustomFont1, CustomFont2 รวมถึงแบบอักษรจากโฟลเดอร์ assets\fonts & global\fonts และโฟลเดอร์ย่อยของมันสามารถใช้ได้กับงานนำเสนอ
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**คืนค่า:**
[IFontSources](../../com.aspose.slides/ifontsources)
### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public final void setDocumentLevelFontSources(IFontSources value)
```

ระบุแหล่งที่มาสำหรับแบบอักษรภายนอกที่จะใช้กับงานนำเสนอ แบบอักษรเหล่านี้จะใช้ได้ตลอดอายุงานของงานนำเสนอและจะไม่ถูกแชร์กับงานนำเสนออื่น

--------------------

> ```
> ตัวอย่างต่อไปนี้แสดงวิธีระบุแบบอักษรที่กำหนดเองที่ใช้กับ PowerPoint Presentation.
>  
>  byte[] memoryFont1 = Files.readAllBytes(Paths.get("customfonts\\CustomFont1.ttf"));
>  byte[] memoryFont2 = Files.readAllBytes(Paths.get("customfonts\\CustomFont2.ttf"));
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  //ทำงานกับงานนำเสนอ
>  //CustomFont1, CustomFont2 รวมถึงแบบอักษรจากโฟลเดอร์ assets\fonts & global\fonts และโฟลเดอร์ย่อยของมันสามารถใช้ได้กับงานนำเสนอ
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public final IInterruptionToken getInterruptionToken()
```

โทเค็นสำหรับตรวจสอบคำขอขัดจังหวะ

--------------------

โทเค็นนี้จัดการอายุของอินสแตนซ์ [IPresentation](../../com.aspose.slides/ipresentation) ทั้งหมด การดำเนินการที่ใช้เวลานาน เช่น การโหลดหรือบันทึกงานนำเสนอ จะถูกขัดจังหวะโดยการเรียกใช้เมธอด [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) ของ [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

**คืนค่า:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public final void setInterruptionToken(IInterruptionToken value)
```

โทเค็นสำหรับตรวจสอบคำขอขัดจังหวะ

--------------------

โทเค็นนี้จัดการอายุของอินสแตนซ์ [IPresentation](../../com.aspose.slides/ipresentation) ทั้งหมด การดำเนินการที่ใช้เวลานาน เช่น การโหลดหรือบันทึกงานนำเสนอ จะถูกขัดจังหวะโดยการเรียกใช้เมธอด [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) ของ [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public final IResourceLoadingCallback getResourceLoadingCallback()
```

คืนค่า หรือกำหนดอินเทอร์เฟซ callback ที่จัดการการโหลดทรัพยากรภายนอก อ่าน/เขียน [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**คืนค่า:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)
### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public final void setResourceLoadingCallback(IResourceLoadingCallback value)
```

คืนค่า หรือกำหนดอินเทอร์เฟซ callback ที่จัดการการโหลดทรัพยากรภายนอก อ่าน/เขียน [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final ISpreadsheetOptions getSpreadsheetOptions()
```

รับตัวเลือกสำหรับสเปรดชีต ตัวอย่างเช่น ตัวเลือกเหล่านี้มีผลต่อการคำนวณสูตรสำหรับแผนภูมิ

**คืนค่า:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public final void setSpreadsheetOptions(ISpreadsheetOptions value)
```

รับตัวเลือกสำหรับสเปรดชีต ตัวอย่างเช่น ตัวเลือกเหล่านี้มีผลต่อการคำนวณสูตรสำหรับแผนภูมิ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public final String getDefaultTextLanguage()
```

คืนค่า หรือกำหนดภาษาตั้งต้นสำหรับข้อความในงานนำเสนอ อ่าน/เขียน String.

--------------------

> ```
> ตัวอย่าง:
>   
>  // ใช้ตัวเลือกการโหลดเพื่อกำหนดภาษาข้อความเริ่มต้น
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // เพิ่มรูปทรงสี่เหลี่ยมใหม่พร้อมข้อความ
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
public final void setDefaultTextLanguage(String value)
```

คืนค่า หรือกำหนดภาษาตั้งต้นสำหรับข้อความในงานนำเสนอ อ่าน/เขียน String.

--------------------

> ```
> ตัวอย่าง:
>   
>  // ใช้ตัวเลือกการโหลดเพื่อกำหนดภาษาข้อความเริ่มต้น
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // เพิ่มรูปทรงสี่เหลี่ยมใหม่พร้อมข้อความ
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // ตรวจสอบภาษาของส่วนแรก
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getDeleteEmbeddedBinaryObjects() {#getDeleteEmbeddedBinaryObjects--}
```
public final boolean getDeleteEmbeddedBinaryObjects()
```

กำหนดว่ากระบวนการ Aspose.Slides จะลบอ็อบเจ็กต์ไบนารีที่ฝังอยู่ทั้งหมดขณะโหลดงานนำเสนอหรือไม่

ประเภทของอ็อบเจ็กต์ไบนารีที่ฝังอยู่:

อ่าน/เขียน boolean .

--------------------

> ```
> ตัวอย่างต่อไปนี้แสดงวิธีโหลดงานนำเสนอโดยไม่มีอ็อบเจ็กต์ไบนารีที่ฝังอยู่ใด ๆ.
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
public final void setDeleteEmbeddedBinaryObjects(boolean value)
```

กำหนดว่ากระบวนการ Aspose.Slides จะลบอ็อบเจ็กต์ไบนารีที่ฝังอยู่ทั้งหมดขณะโหลดงานนำเสนอหรือไม่

ประเภทของอ็อบเจ็กต์ไบนารีที่ฝังอยู่:

อ่าน/เขียน boolean .

--------------------

> ```
> ตัวอย่างต่อไปนี้แสดงวิธีโหลดงานนำเสนอโดยไม่มีอ็อบเจ็กต์ไบนารีที่ฝังอยู่ใด ๆ.
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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |