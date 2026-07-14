---
title: IHtml5Options
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง Java API
description: แสดงตัวเลือกการส่งออก HTML5
type: docs
url: /th/com.aspose.slides/ihtml5options/
---
**ส่วนติดต่อที่ใช้งานทั้งหมด:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IHtml5Options extends ISaveOptions
```

แสดงตัวเลือกการส่งออก HTML5

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
## Methods

| Method | Description |
| --- | --- |
| [getAnimateTransitions()](#getAnimateTransitions--) | คืนค่าหรือกำหนดตัวเลือกการเคลื่อนไหวของการเปลี่ยนแปลง. |
| [setAnimateTransitions(boolean value)](#setAnimateTransitions-boolean-) | คืนค่าหรือกำหนดตัวเลือกการเคลื่อนไหวของการเปลี่ยนแปลง. |
| [getAnimateShapes()](#getAnimateShapes--) | คืนค่าหรือกำหนดตัวเลือกการเคลื่อนไหวของรูปร่าง. |
| [setAnimateShapes(boolean value)](#setAnimateShapes-boolean-) | คืนค่าหรือกำหนดตัวเลือกการเคลื่อนไหวของรูปร่าง. |
| [getEmbedImages()](#getEmbedImages--) | คืนค่าหรือกำหนดตัวเลือกการฝังรูปภาพ. |
| [setEmbedImages(boolean value)](#setEmbedImages-boolean-) | คืนค่าหรือกำหนดตัวเลือกการฝังรูปภาพ. |
| [getOutputPath()](#getOutputPath--) | กำหนดตำแหน่งที่จะเก็บทรัพยากรภายนอก. |
| [setOutputPath(String value)](#setOutputPath-java.lang.String-) | กำหนดตำแหน่งที่จะเก็บทรัพยากรภายนอก. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | ได้รับหรือกำหนดค่าที่บ่งชี้ว่าข้อความจะถูกแสดงโดยไม่ใช้ลิการเจอร์. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | ได้รับหรือกำหนดค่าที่บ่งชี้ว่าข้อความจะถูกแสดงโดยไม่ใช้ลิการเจอร์. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | ได้รับหรือกำหนดโหมดที่สไลด์จะถูกจัดวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | ได้รับหรือกำหนดโหมดที่สไลด์จะถูกจัดวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
### getAnimateTransitions() {#getAnimateTransitions--}
```
public abstract boolean getAnimateTransitions()
```

คืนค่าหรือกำหนดตัวเลือกการเคลื่อนไหวของการเปลี่ยนแปลง. อ่าน/เขียน boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**คืนค่า:**
boolean
### setAnimateTransitions(boolean value) {#setAnimateTransitions-boolean-}
```
public abstract void setAnimateTransitions(boolean value)
```

คืนค่าหรือกำหนดตัวเลือกการเคลื่อนไหวของการเปลี่ยนแปลง. อ่าน/เขียน boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAnimateShapes() {#getAnimateShapes--}
```
public abstract boolean getAnimateShapes()
```

คืนค่าหรือกำหนดตัวเลือกการเคลื่อนไหวของรูปร่าง. อ่าน/เขียน boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
> 
>      pres.save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**คืนค่า:**
boolean
### setAnimateShapes(boolean value) {#setAnimateShapes-boolean-}
```
public abstract void setAnimateShapes(boolean value)
```

คืนค่าหรือกำหนดตัวเลือกการเคลื่อนไหวของรูปร่าง. อ่าน/เขียน boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
> 
>      pres.save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEmbedImages() {#getEmbedImages--}
```
public abstract boolean getEmbedImages()
```

คืนค่าหรือกำหนดตัวเลือกการฝังรูปภาพ. อ่าน/เขียน boolean.

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
public abstract void setEmbedImages(boolean value)
```

คืนค่าหรือกำหนดตัวเลือกการฝังรูปภาพ. อ่าน/เขียน boolean.

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getOutputPath() {#getOutputPath--}
```
public abstract String getOutputPath()
```

กำหนดตำแหน่งที่จะแสดงทรัพยากรภายนอก. อ่าน/เขียน String.

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
public abstract void setOutputPath(String value)
```

กำหนดตำแหน่งที่จะแสดงทรัพยากรภายนอก. อ่าน/เขียน String.

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

ได้รับหรือกำหนดค่าที่บ่งชี้ว่าข้อความจะถูกแสดงโดยไม่ใช้ลิการเจอร์. เมื่อกำหนดเป็น true, ลิการเจอร์จะถูกปิดใช้งานในผลลัพธ์ที่แสดง. โดยค่าเริ่มต้น property นี้ตั้งเป็น false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // ปิดการใช้งานลิการเจอร์ในการแสดงผลข้อความ
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
public abstract void setDisableFontLigatures(boolean value)
```

ได้รับหรือกำหนดค่าที่บ่งชี้ว่าข้อความจะถูกแสดงโดยไม่ใช้ลิการเจอร์. เมื่อกำหนดเป็น true, ลิการเจอร์จะถูกปิดใช้งานในผลลัพธ์ที่แสดง. โดยค่าเริ่มต้น property นี้ตั้งเป็น false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // ปิดการใช้งานลิการเจอร์ในการแสดงผลข้อความ
> 
>      pres.save("output.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

ได้รับหรือกำหนดโหมดที่สไลด์จะถูกจัดวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

ได้รับหรือกำหนดโหมดที่สไลด์จะถูกจัดวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |