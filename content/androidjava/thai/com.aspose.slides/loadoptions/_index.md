---
title: LoadOptions
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: อนุญาตให้ระบุตัวเลือกเพิ่มเติม เช่น รูปแบบหรือแบบอักษรเริ่มต้นเมื่อโหลดงานนำเสนอ.
type: docs
url: /th/com.aspose.slides/loadoptions/
---
**การสืบทอด:**
java.lang.Object

**ทุกอินเทอร์เฟซที่ทำการ Implement:**
[com.aspose.slides.ILoadOptions](../../com.aspose.slides/iloadoptions)
```
public class LoadOptions implements ILoadOptions
```

อนุญาตระบุตัวเลือกเพิ่มเติม (เช่น รูปแบบหรือแบบอักษรเริ่มต้น) เมื่อโหลดงานนำเสนอ
## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | สร้างตัวเลือกการโหลดเริ่มต้นใหม่ |
| [LoadOptions(int loadFormat)](#LoadOptions-int-) | สร้างตัวเลือกการโหลดใหม่ |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | คืนค่า หรือกำหนดรูปแบบของงานนำเสนอที่ต้องการโหลด |
| [setLoadFormat(int value)](#setLoadFormat-int-) | คืนค่า หรือกำหนดรูปแบบของงานนำเสนอที่ต้องการโหลด |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | คืนค่า หรือกำหนดแบบอักษร Regular ที่ใช้เมื่อไม่พบแบบอักษรต้นฉบับ |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | คืนค่า หรือกำหนดแบบอักษร Regular ที่ใช้เมื่อไม่พบแบบอักษรต้นฉบับ |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | คืนค่า หรือกำหนดแบบอักษร Symbol ที่ใช้เมื่อไม่พบแบบอักษรต้นฉบับ |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | คืนค่า หรือกำหนดแบบอักษร Symbol ที่ใช้เมื่อไม่พบแบบอักษรต้นฉบับ |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | คืนค่า หรือกำหนดแบบอักษร Asian ที่ใช้เมื่อไม่พบแบบอักษรต้นฉบับ |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | คืนค่า หรือกำหนดแบบอักษร Asian ที่ใช้เมื่อไม่พบแบบอักษรต้นฉบับ |
| [getPassword()](#getPassword--) | รับหรือกำหนดรหัสผ่าน |
| [setPassword(String value)](#setPassword-java.lang.String-) | รับหรือกำหนดรหัสผ่าน |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | คุณสมบัตินี้มีความหมาย หากไฟล์งานนำเสนอถูกป้องกันด้วยรหัสผ่าน |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | คุณสมบัตินี้มีความหมาย หากไฟล์งานนำเสนอถูกป้องกันด้วยรหัสผ่าน |
| [getWarningCallback()](#getWarningCallback--) | คืนค่า หรือกำหนดอ็อบเจกต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือยกเลิก |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | คืนค่า หรือกำหนดอ็อบเจกต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือยกเลิก |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | แสดงตัวเลือกที่ใช้จัดการพฤติกรรมการจัดการ Binary Large Objects (BLOBs) เช่น การใช้ไฟล์ชั่วคราวหรือจำนวนไบต์สูงสุดของ BLOBs ในหน่วยความจำ |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | แสดงตัวเลือกที่ใช้จัดการพฤติกรรมการจัดการ Binary Large Objects (BLOBs) เช่น การใช้ไฟล์ชั่วคราวหรือจำนวนไบต์สูงสุดของ BLOBs ในหน่วยความจำ |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | ระบุแหล่งที่มาของแบบอักษรภายนอกที่จะใช้ในงานนำเสนอ |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | ระบุแหล่งที่มาของแบบอักษรภายนอกที่จะใช้ในงานนำเสนอ |
| [getInterruptionToken()](#getInterruptionToken--) | โทเคนที่ใช้ตรวจสอบการขอการขัดจังหวะ |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | โทเคนที่ใช้ตรวจสอบการขอการขัดจังหวะ |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | คืนค่า หรือกำหนดอินเทอร์เฟซ callback ที่จัดการการโหลดทรัพยากรภายนอก |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | คืนค่า หรือกำหนดอินเทอร์เฟซ callback ที่จัดการการโหลดทรัพยากรภายนอก |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | รับตัวเลือกสำหรับสเปรดชีต |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | รับตัวเลือกสำหรับสเปรดชีต |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | คืนค่า หรือกำหนดภาษาตั้งต้นสำหรับข้อความในงานนำเสนอ |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | คืนค่า หรือกำหนดภาษาตั้งต้นสำหรับข้อความในงานนำเสนอ |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | กำหนดว่า Aspose.Slides จะลบวัตถุไบนารีฝังทั้งหมดขณะโหลดงานนำเสนอหรือไม่ |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | กำหนดว่า Aspose.Slides จะลบวัตถุไบนารีฝังทั้งหมดขณะโหลดงานนำเสนอหรือไม่ |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


สร้างตัวเลือกการโหลดเริ่มต้นใหม่

### LoadOptions(int loadFormat) {#LoadOptions-int-}
```
public LoadOptions(int loadFormat)
```


สร้างตัวเลือกการโหลดใหม่

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
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
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```


คืนค่า หรือกำหนดแบบอักษร Regular ที่ใช้เมื่อไม่พบแบบอักษรต้นฉบับ อ่าน/เขียน String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // ใช้ตัวเลือกการโหลดเพื่อกำหนดแบบอักษรปกติและแบบอักษรเอเชียเริ่มต้น
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // โหลดงานนำเสนอ
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // สร้างภาพย่อสไลด์
>      android.graphics.Bitmap slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      FileOutputStream fos = null;
>      try {
>          fos = new FileOutputStream("output_out.png");
>          slideImage.compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
>      } catch (IOException e) {
>          throw new RuntimeException(e);
>      } finally {
>          if (fos != null) {
>              try {
>                  fos.close();
>              } catch (IOException e) {
>                  e.printStackTrace();
>              }
>          }
>      }
>      // สร้าง PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // สร้าง XPS
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


คืนค่า หรือกำหนดแบบอักษร Regular ที่ใช้เมื่อไม่พบแบบอักษรต้นฉบับ อ่าน/เขียน String.

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
>      android.graphics.Bitmap slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      FileOutputStream fos = null;
>      try {
>          fos = new FileOutputStream("output_out.png");
>          slideImage.compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
>      } catch (IOException e) {
>          throw new RuntimeException(e);
>      } finally {
>          if (fos != null) {
>              try {
>                  fos.close();
>              } catch (IOException e) {
>                  e.printStackTrace();
>              }
>          }
>      }
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
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public final String getDefaultSymbolFont()
```


คืนค่า หรือกำหนดแบบอักษร Symbol ที่ใช้เมื่อไม่พบแบบอักษรต้นฉบับ อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public final void setDefaultSymbolFont(String value)
```


คืนค่า หรือกำหนดแบบอักษร Symbol ที่ใช้เมื่อไม่พบแบบอักษรต้นฉบับ อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public final String getDefaultAsianFont()
```


คืนค่า หรือกำหนดแบบอักษร Asian ที่ใช้เมื่อไม่พบแบบอักษรต้นฉบับ อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public final void setDefaultAsianFont(String value)
```


คืนค่า หรือกำหนดแบบอักษร Asian ที่ใช้เมื่อไม่พบแบบอักษรต้นฉบับ อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
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
>  // ทำงานกับงานนำเสนอที่ถูกถอดรหัส
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
>  // ทำงานกับงานนำเสนอที่ถอดรหัส
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


ค่า: รหัสผ่าน

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public final boolean getOnlyLoadDocumentProperties()
```


คุณสมบัตินี้มีความหมาย หากไฟล์งานนำเสนอมิได้รับการป้องกันด้วยรหัสผ่าน ค่า true หมายถึงจะโหลดเพียงคุณสมบัติเ�เอกสารจากไฟล์งานนำเสนอที่เข้ารหัส และจะละเว้นรหัสผ่าน ค่า false หมายถึงจะโหลดงานนำเสนอที่เข้ารหัสทั้งหมดโดยใช้รหัสผ่านที่ถูกต้อง หากไฟล์ไม่ได้เข้ารหัส ค่าคุณสมบัติจะแสดงผลตามค่าเริ่มต้น หากคุณสมบัติเข้าถึงได้ของไฟล์ที่เข้ารหัสไม่ได้เป็นสาธารณะและค่าเป็น true จะไม่สามารถโหลดคุณสมบัติเข้าไปได้และจะเกิดข้อยกเว้น อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public final void setOnlyLoadDocumentProperties(boolean value)
```


คุณสมบัตินี้มีความหมาย หากไฟล์งานนำเสนอมิได้รับการป้องกันด้วยรหัสผ่าน ค่า true หมายถึงจะโหลดเพียงคุณสมบัติเข้าเอกสารจากไฟล์งานนำเสนอที่เข้ารหัส และจะละเว้นรหัสผ่าน ค่า false หมายถึงจะโหลดงานนำเสนอที่เข้ารหัสทั้งหมดโดยใช้รหัสผ่านที่ถูกต้อง หากไฟล์ไม่ได้เข้ารหัส ค่าคุณสมบัติจะแสดงผลตามค่าเริ่มต้น หากคุณสมบัติเข้าถึงได้ของไฟล์ที่เข้ารหัสไม่ได้เป็นสาธารณะและค่าเป็น true จะไม่สามารถโหลดคุณสมบัติเข้าไปได้และจะเกิดข้อยกเว้น อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```


คืนค่า หรือกำหนดอ็อบเจกต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือยกเลิก อ่าน/เขียน [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**คืนค่า:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```


คืนค่า หรือกำหนดอ็อบเจกต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือยกเลิก อ่าน/เขียน [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public final IBlobManagementOptions getBlobManagementOptions()
```


แสดงตัวเลือกที่ใช้จัดการพฤติกรรมการจัดการ Binary Large Objects (BLOBs) เช่น การใช้ไฟล์ชั่วคราวหรือจำนวนไบต์สูงสุดของ BLOBs ในหน่วยความจำ ตัวเลือกเหล่านี้ออกแบบมาเพื่อกำหนดอัตราส่วนการทำงาน/การใช้หน่วยความจำที่ดีที่สุดสำหรับสภาพแวดล้อมหรือความต้องการที่เฉพาะเจาะจง

--------------------

Binary Large Object (BLOB) คือข้อมูลไบนารีที่เก็บเป็นเอนทิตีเดียว เช่น เสียง วิดีโอ หรืองานนำเสนอเอง

**คืนค่า:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public final void setBlobManagementOptions(IBlobManagementOptions value)
```


แสดงตัวเลือกที่ใช้จัดการพฤติกรรมการจัดการ Binary Large Objects (BLOBs) เช่น การใช้ไฟล์ชั่วคราวหรือจำนวนไบต์สูงสุดของ BLOBs ในหน่วยความจำ ตัวเลือกเหล่านี้ออกแบบมาเพื่อกำหนดอัตราส่วนการทำงาน/การใช้หน่วยความจำที่ดีที่สุดสำหรับสภาพแวดล้อมหรือความต้องการที่เฉพาะเจาะจง

--------------------

Binary Large Object (BLOB) คือข้อมูลไบนารีที่เก็บเป็นเอนทิตีเดียว เช่น เสียง วิดีโอ หรืองานนำเสนอเอง

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public final IFontSources getDocumentLevelFontSources()
```


ระบุแหล่งที่มาของแบบอักษรภายนอกที่จะใช้ในงานนำเสนอ แบบอักษรเหล่านี้จะใช้ได้ตลอดอายุของงานนำเสนอและไม่ถูกแชร์กับงานนำเสนออื่น

--------------------

> ```
> The following example shows how to specify custom fonts used with PowerPoint Presentation.
>  
>  File file = new File("customfonts/CustomFont1.ttf");
>  byte memoryFont1[] = new byte[(int) file.length()];
>  BufferedInputStream bis = new BufferedInputStream(new FileInputStream(file));
>  DataInputStream dis = new DataInputStream(bis);
>  dis.readFully(memoryFont1);
>  file = new File("customfonts/CustomFont2.ttf");
>  byte memoryFont2[] = new byte[(int) file.length()];
>  bis = new BufferedInputStream(new FileInputStream(file));
>  dis = new DataInputStream(bis);
>  dis.readFully(memoryFont2);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  // ทำงานกับงานนำเสนอ
>  // CustomFont1, CustomFont2 รวมถึงแบบอักษรจากโฟลเดอร์ assets\fonts และ global\fonts และโฟลเดอร์ย่อยของมันพร้อมใช้งานในงานนำเสนอ
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


ระบุแหล่งที่มาของแบบอักษรภายนอกที่จะใช้ในงานนำเสนอ แบบอักษรเหล่านี้จะใช้ได้ตลอดอายุของงานนำเสนอและไม่ถูกแชร์กับงานนำเสนออื่น

--------------------

> ```
> ตัวอย่างต่อไปนี้แสดงวิธีกำหนดแบบอักษรที่กำหนดเองสำหรับการใช้กับ PowerPoint Presentation.
>  
  File file = new File("customfonts/CustomFont1.ttf");
  byte memoryFont1[] = new byte[(int) file.length()];
  BufferedInputStream bis = new BufferedInputStream(new FileInputStream(file));
  DataInputStream dis = new DataInputStream(bis);
  dis.readFully(memoryFont1);
  file = new File("customfonts/CustomFont2.ttf");
  byte memoryFont2[] = new byte[(int) file.length()];
  bis = new BufferedInputStream(new FileInputStream(file));
  dis = new DataInputStream(bis);
  dis.readFully(memoryFont2);
  LoadOptions loadOptions = new LoadOptions();
  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
  try {
  // ทำงานกับงานนำเสนอ
  // CustomFont1, CustomFont2 รวมถึงแบบอักษรจากโฟลเดอร์ assets\fonts และ global\fonts และโฟลเดอร์ย่อยของมันพร้อมใช้งานในงานนำเสนอ
  } finally {
      if (presentation != null) presentation.dispose();
  }
  ```


**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public final IInterruptionToken getInterruptionToken()
```


โทเคนที่ใช้ตรวจสอบการขอการขัดจังหวะ

--------------------

โทเคนนี้จัดการอายุของอินสแตนซ์ [IPresentation](../../com.aspose.slides/ipresentation) ทั้งหมด การดำเนินการที่ใช้เวลานาน เช่น การโหลดหรือบันทึกงานนำเสนอ จะถูกขัดจังหวะโดยการเรียกเมธอด [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) ของ [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource)

**คืนค่า:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public final void setInterruptionToken(IInterruptionToken value)
```


โทเคนที่ใช้ตรวจสอบการขอการขัดจังหวะ

--------------------

โทเคนนี้จัดการอายุของอินสแตนซ์ [IPresentation](../../com.aspose.slides/ipresentation) ทั้งหมด การดำเนินการที่ใช้เวลานาน เช่น การโหลดหรือบันทึกงานนำเสนอ จะถูกขัดจังหวะโดยการเรียกเมธอด [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) ของ [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource)

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
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
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final ISpreadsheetOptions getSpreadsheetOptions()
```


รับตัวเลือกสำหรับสเปรดชีต ตัวอย่างเช่น ตัวเลือกเหล่านี้มีผลต่อการคำนวนสูตรสำหรับแผนภูมิ

**คืนค่า:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public final void setSpreadsheetOptions(ISpreadsheetOptions value)
```


รับตัวเลือกสำหรับสเปรดชีต ตัวอย่างเช่น ตัวเลือกเหล่านี้มีผลต่อการคำนวนสูตรสำหรับแผนภูมิ

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public final String getDefaultTextLanguage()
```


คืนค่า หรือกำหนดภาษาตั้งต้นสำหรับข้อความในงานนำเสนอ อ่าน/เขียน String.

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


**คืนค่า:**
java.lang.String
### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public final void setDefaultTextLanguage(String value)
```


คืนค่า หรือกำหนดภาษาตั้งต้นสำหรับข้อความในงานนำเสนอ อ่าน/เขียน String.

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
public final boolean getDeleteEmbeddedBinaryObjects()
```


กำหนดว่า Aspose.Slides จะลบวัตถุไบนารีฝังทั้งหมดขณะโหลดงานนำเสนอหรือไม่

ประเภทของวัตถุไบนารีฝัง:

อ่าน/เขียน boolean.

--------------------

> ```
> ตัวอย่างต่อไปนี้แสดงวิธีโหลดงานนำเสนอโดยไม่มีวัตถุไบนารีที่ฝังอยู่ใดๆ
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


กำหนดว่า Aspose.Slides จะลบวัตถุไบนารีฝังทั้งหมดขณะโหลดงานนำเสนอหรือไม่

ประเภทของวัตถุไบนารีฝัง:

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