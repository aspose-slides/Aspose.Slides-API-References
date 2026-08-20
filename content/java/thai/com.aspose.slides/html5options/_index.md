---
title: Html5Options
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ Java
description: เป็นตัวแทนของตัวเลือกการส่งออก HTML5
type: docs
url: /th/com.aspose.slides/html5options/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
[com.aspose.slides.IHtml5Options](../../com.aspose.slides/ihtml5options)
```
public class Html5Options extends SaveOptions implements IHtml5Options
```

เป็นตัวเลือกการส่งออก HTML5.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [Html5Options()](#Html5Options--) | คอนสตรัคเตอร์เริ่มต้น. |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getAnimateTransitions()](#getAnimateTransitions--) | คืนค่า หรือกำหนดตัวเลือกการเคลื่อนไหวของการเปลี่ยน. |
| [setAnimateTransitions(boolean value)](#setAnimateTransitions-boolean-) | คืนค่า หรือกำหนดตัวเลือกการเคลื่อนไหวของการเปลี่ยน. |
| [getAnimateShapes()](#getAnimateShapes--) | คืนค่า หรือกำหนดตัวเลือกการเคลื่อนไหวของรูปร่าง. |
| [setAnimateShapes(boolean value)](#setAnimateShapes-boolean-) | คืนค่า หรือกำหนดตัวเลือกการเคลื่อนไหวของรูปร่าง. |
| [getEmbedImages()](#getEmbedImages--) | คืนค่า หรือกำหนดตัวเลือกการฝังรูปภาพ. |
| [setEmbedImages(boolean value)](#setEmbedImages-boolean-) | คืนค่า หรือกำหนดตัวเลือกการฝังรูปภาพ. |
| [getOutputPath()](#getOutputPath--) | กำหนดว่าทรัพยากรภายนอกควรถูกเก็บไว้ที่ไหน. |
| [setOutputPath(String value)](#setOutputPath-java.lang.String-) | กำหนดว่าทรัพยากรภายนอกควรถูกเก็บไว้ที่ไหน. |
| [getPicturesCompression()](#getPicturesCompression--) | เป็นตัวแทนระดับการบีบอัดรูปภาพ |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | เป็นตัวแทนระดับการบีบอัดรูปภาพ |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | รับหรือกำหนดค่าที่บ่งบอกว่าข้อความถูกเรนเดอร์โดยไม่ใช้ลิแกเจอร์. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | รับหรือกำหนดค่าที่บ่งบอกว่าข้อความถูกเรนเดอร์โดยไม่ใช้ลิแกเจอร์. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | รับหรือกำหนดโหมดที่สไลด์ถูกจัดวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | รับหรือกำหนดโหมดที่สไลด์ถูกจัดวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
### Html5Options() {#Html5Options--}
```
public Html5Options()
```

คอนสตรัคเตอร์เริ่มต้น.

### getAnimateTransitions() {#getAnimateTransitions--}
```
public final boolean getAnimateTransitions()
```

คืนค่า หรือกำหนดตัวเลือกการเคลื่อนไหวของการเปลี่ยน. อ่าน/เขียน boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**คืนค่า:**
boolean
### setAnimateTransitions(boolean value) {#setAnimateTransitions-boolean-}
```
public final void setAnimateTransitions(boolean value)
```

คืนค่า หรือกำหนดตัวเลือกการเคลื่อนไหวของการเปลี่ยน. อ่าน/เขียน boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getAnimateShapes() {#getAnimateShapes--}
```
public final boolean getAnimateShapes()
```

คืนค่า หรือกำหนดตัวเลือกการเคลื่อนไหวของรูปร่าง. อ่าน/เขียน boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
> 
>      pres.save("demo-animate-shapes.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**คืนค่า:**
boolean
### setAnimateShapes(boolean value) {#setAnimateShapes-boolean-}
```
public final void setAnimateShapes(boolean value)
```

คืนค่า หรือกำหนดตัวเลือกการเคลื่อนไหวของรูปร่าง. อ่าน/เขียน boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
> 
>      pres.save("demo-animate-shapes.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getEmbedImages() {#getEmbedImages--}
```
public final boolean getEmbedImages()
```

คืนค่า หรือกำหนดตัวเลือกการฝังรูปภาพ. อ่าน/เขียน boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**คืนค่า:**
boolean
### setEmbedImages(boolean value) {#setEmbedImages-boolean-}
```
public final void setEmbedImages(boolean value)
```

คืนค่า หรือกำหนดตัวเลือกการฝังรูปภาพ. อ่าน/เขียน boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getOutputPath() {#getOutputPath--}
```
public final String getOutputPath()
```

กำหนดว่าทรัพยากรภายนอกควรถูกเก็บไว้ที่ไหน. อ่าน/เขียน String.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      html5Options.setOutputPath(the_desired_path);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**คืนค่า:**
java.lang.String
### setOutputPath(String value) {#setOutputPath-java.lang.String-}
```
public final void setOutputPath(String value)
```

กำหนดว่าทรัพยากรภายนอกควรถูกเก็บไว้ที่ไหน. อ่าน/เขียน String.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      html5Options.setOutputPath(the_desired_path);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

เป็นตัวแทนระดับการบีบอัดรูปภาพ

**คืนค่า:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

เป็นตัวแทนระดับการบีบอัดรูปภาพ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

รับหรือกำหนดค่าที่บ่งบอกว่าข้อความถูกเรนเดอร์โดยไม่ใช้ลิแกเจอร์. เมื่อกำหนดเป็น true, ลิแกเจอร์จะถูกปิดในผลลัพธ์ที่เรนเดอร์. ค่าเริ่มต้นของคุณสมบัตินี้คือ false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // ปิดการใช้ลิแกเจอร์ในการเรนเดอร์ข้อความ
> 
>      pres.save("output.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**คืนค่า:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```

รับหรือกำหนดค่าที่บ่งบอกว่าข้อความถูกเรนเดอร์โดยไม่ใช้ลิแกเจอร์. เมื่อกำหนดเป็น true, ลิแกเจอร์จะถูกปิดในผลลัพธ์ที่เรนเดอร์. ค่าเริ่มต้นของคุณสมบัตินี้คือ false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // ปิดการใช้ลิแกเจอร์ในการเรนเดอร์ข้อความ
> 
>      pres.save("output.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

รับหรือกำหนดโหมดที่สไลด์ถูกจัดวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HandoutLayoutingOptions handoutLayoutingOptions = new HandoutLayoutingOptions();
>      handoutLayoutingOptions.setHandout(HandoutType.Handouts4Horizontal);
>      Html5Options options = new Html5Options();
>      options.setSlidesLayoutOptions(handoutLayoutingOptions);
> 
>      pres.save("pres.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**คืนค่า:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

รับหรือกำหนดโหมดที่สไลด์ถูกจัดวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HandoutLayoutingOptions handoutLayoutingOptions = new HandoutLayoutingOptions();
>      handoutLayoutingOptions.setHandout(HandoutType.Handouts4Horizontal);
>      Html5Options options = new Html5Options();
>      options.setSlidesLayoutOptions(handoutLayoutingOptions);
> 
>      pres.save("pres.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |