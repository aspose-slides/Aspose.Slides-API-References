---
title: Html5Options
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นตัวเลือกการส่งออก HTML5.
type: docs
url: /th/com.aspose.slides/html5options/
---
**การสืบทอด:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**อินเทอร์เฟซที่ทำงานทั้งหมด:**  
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
## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [Html5Options()](#Html5Options--) | คอนสตรักเตอร์เริ่มต้น. |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getAnimateTransitions()](#getAnimateTransitions--) | รับหรือกำหนดตัวเลือกการเคลื่อนไหวของการเปลี่ยนหน้า. |
| [setAnimateTransitions(boolean value)](#setAnimateTransitions-boolean-) | รับหรือกำหนดตัวเลือกการเคลื่อนไหวของการเปลี่ยนหน้า. |
| [getAnimateShapes()](#getAnimateShapes--) | รับหรือกำหนดตัวเลือกการเคลื่อนไหวของรูปทรง. |
| [setAnimateShapes(boolean value)](#setAnimateShapes-boolean-) | รับหรือกำหนดตัวเลือกการเคลื่อนไหวของรูปทรง. |
| [getEmbedImages()](#getEmbedImages--) | รับหรือกำหนดตัวเลือกการฝังภาพ. |
| [setEmbedImages(boolean value)](#setEmbedImages-boolean-) | รับหรือกำหนดตัวเลือกการฝังภาพ. |
| [getOutputPath()](#getOutputPath--) | กำหนดตำแหน่งที่ควรจัดเก็บทรัพยากรภายนอก. |
| [setOutputPath(String value)](#setOutputPath-java.lang.String-) | กำหนดตำแหน่งที่ควรจัดเก็บทรัพยากรภายนอก. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | รับหรือกำหนดค่าที่บ่งชี้ว่าข้อความถูกแสดงโดยไม่ใช้ ligatures. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | รับหรือกำหนดค่าที่บ่งชี้ว่าข้อความถูกแสดงโดยไม่ใช้ ligatures. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | รับหรือกำหนดโหมดที่สไลด์จะถูกวางบนหน้ากระดาษเมื่อส่งออกรายการนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | รับหรือกำหนดโหมดที่สไลด์จะถูกวางบนหน้ากระดาษเมื่อส่งออกรายการนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |

### Html5Options() {#Html5Options--}
```
public Html5Options()
```

คอนสตรักเตอร์เริ่มต้น.

### getAnimateTransitions() {#getAnimateTransitions--}
```
public final boolean getAnimateTransitions()
```

รับหรือกำหนดตัวเลือกการเคลื่อนไหวของการเปลี่ยนหน้า. อ่าน/เขียน boolean.

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

**ค่าที่ส่งคืน:**  
boolean
### setAnimateTransitions(boolean value) {#setAnimateTransitions-boolean-}
```
public final void setAnimateTransitions(boolean value)
```

รับหรือกำหนดตัวเลือกการเคลื่อนไหวของการเปลี่ยนหน้า. อ่าน/เขียน boolean.

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
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getAnimateShapes() {#getAnimateShapes--}
```
public final boolean getAnimateShapes()
```

รับหรือกำหนดตัวเลือกการเคลื่อนไหวของรูปทรง. อ่าน/เขียน boolean.

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

**ค่าที่ส่งคืน:**  
boolean
### setAnimateShapes(boolean value) {#setAnimateShapes-boolean-}
```
public final void setAnimateShapes(boolean value)
```

รับหรือกำหนดตัวเลือกการเคลื่อนไหวของรูปทรง. อ่าน/เขียน boolean.

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
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getEmbedImages() {#getEmbedImages--}
```
public final boolean getEmbedImages()
```

รับหรือกำหนดตัวเลือกการฝังภาพ. อ่าน/เขียน boolean.

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

**ค่าที่ส่งคืน:**  
boolean
### setEmbedImages(boolean value) {#setEmbedImages-boolean-}
```
public final void setEmbedImages(boolean value)
```

รับหรือกำหนดตัวเลือกการฝังภาพ. อ่าน/เขียน boolean.

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
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getOutputPath() {#getOutputPath--}
```
public final String getOutputPath()
```

กำหนดตำแหน่งที่ควรจัดเก็บทรัพยากรภายนอก. อ่าน/เขียน String.

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

**ค่าที่ส่งคืน:**  
java.lang.String
### setOutputPath(String value) {#setOutputPath-java.lang.String-}
```
public final void setOutputPath(String value)
```

กำหนดตำแหน่งที่ควรจัดเก็บทรัพยากรภายนอก. อ่าน/เขียน String.

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
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

รับหรือกำหนดค่าที่บ่งชี้ว่าข้อความถูกแสดงโดยไม่ใช้ ligatures. เมื่อกำหนดเป็น true, ligatures จะถูกปิดในผลลัพธ์ที่แสดง. โดยค่าเริ่มต้น, คุณสมบัตินี้ถูกตั้งค่าเป็น false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // ปิดลิเกเจอร์ในการเรนเดอร์ข้อความ
> 
>      pres.save("output.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**ค่าที่ส่งคืน:**  
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```

รับหรือกำหนดค่าที่บ่งชี้ว่าข้อความถูกแสดงโดยไม่ใช้ ligatures. เมื่อกำหนดเป็น true, ligatures จะถูกปิดในผลลัพธ์ที่แสดง. โดยค่าเริ่มต้น, คุณสมบัตินี้ถูกตั้งค่าเป็น false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // ปิดลิเกเจอร์ในการเรนเดอร์ข้อความ
> 
>      pres.save("output.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

รับหรือกำหนดโหมดที่สไลด์จะถูกวางบนหน้ากระดาษเมื่อส่งออกรายการนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

**ค่าที่ส่งคืน:**  
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

รับหรือกำหนดโหมดที่สไลด์จะถูกวางบนหน้ากระดาษเมื่อส่งออกรายการนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |