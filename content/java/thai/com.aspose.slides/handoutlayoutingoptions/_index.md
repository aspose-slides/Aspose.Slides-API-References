---
title: HandoutLayoutingOptions
second_title: Aspose.Slides สำหรับ Java API Reference
description: แสดงโหมดการจัดเรียงการนำเสนอแบบแจกเอกสารสำหรับการส่งออก.
type: docs
url: /th/com.aspose.slides/handoutlayoutingoptions/
---
**Inheritance:**
การสืบทอด: java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
```
public class HandoutLayoutingOptions implements ISlidesLayoutOptions
```

แสดงโหมดเลเอาต์การนำเสนอแบบแจกเอกสารสำหรับการส่งออก.
## Constructors

| Constructor | Description |
| --- | --- |
| [HandoutLayoutingOptions()](#HandoutLayoutingOptions--) | กำหนดค่าเริ่มต้น. |
## Methods

| Method | Description |
| --- | --- |
| [getHandout()](#getHandout--) | ระบุจำนวนสไลด์และลำดับที่จะวางบนหน้า [HandoutType](../../com.aspose.slides/handouttype). |
| [setHandout(int value)](#setHandout-int-) | ระบุจำนวนสไลด์และลำดับที่จะวางบนหน้า [HandoutType](../../com.aspose.slides/handouttype). |
| [getPrintSlideNumbers()](#getPrintSlideNumbers--) | ระบุว่าจะพิมพ์หมายเลขสไลด์ที่แสดงหรือไม่. |
| [setPrintSlideNumbers(boolean value)](#setPrintSlideNumbers-boolean-) | ระบุว่าจะพิมพ์หมายเลขสไลด์ที่แสดงหรือไม่. |
| [getPrintFrameSlide()](#getPrintFrameSlide--) | ระบุว่าจะวาดกรอบรอบสไลด์ที่แสดงหรือไม่. |
| [setPrintFrameSlide(boolean value)](#setPrintFrameSlide-boolean-) | ระบุว่าจะวาดกรอบรอบสไลด์ที่แสดงหรือไม่. |
| [getPrintComments()](#getPrintComments--) | ระบุว่าจะเปิดแสดงความคิดเห็นบนสไลด์หรือไม่ |
| [setPrintComments(boolean value)](#setPrintComments-boolean-) | ระบุว่าจะเปิดแสดงความคิดเห็นบนสไลด์หรือไม่ |
### HandoutLayoutingOptions() {#HandoutLayoutingOptions--}
```
public HandoutLayoutingOptions()
```

กำหนดค่าเริ่มต้น.

### getHandout() {#getHandout--}
```
public final int getHandout()
```

ระบุจำนวนสไลด์และลำดับที่จะวางบนหน้า [HandoutType](../../com.aspose.slides/handouttype).

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new Dimension(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

ค่าเริ่มต้นคือ  **HandoutType.Handouts6Horizontal** .

**Returns:**
int
### setHandout(int value) {#setHandout-int-}
```
public final void setHandout(int value)
```

ระบุจำนวนสไลด์และลำดับที่จะวางบนหน้า [HandoutType](../../com.aspose.slides/handouttype).

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new Dimension(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

ค่าเริ่มต้นคือ  **HandoutType.Handouts6Horizontal** .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPrintSlideNumbers() {#getPrintSlideNumbers--}
```
public final boolean getPrintSlideNumbers()
```

ระบุว่าจะพิมพ์หมายเลขสไลด์ที่แสดงหรือไม่.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintSlideNumbers(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new Dimension(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

ค่าเริ่มต้นคือ  **true** .

**Returns:**
boolean
### setPrintSlideNumbers(boolean value) {#setPrintSlideNumbers-boolean-}
```
public final void setPrintSlideNumbers(boolean value)
```

ระบุว่าจะพิมพ์หมายเลขสไลด์ที่แสดงหรือไม่.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintSlideNumbers(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new Dimension(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

ค่าเริ่มต้นคือ  **true** .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPrintFrameSlide() {#getPrintFrameSlide--}
```
public final boolean getPrintFrameSlide()
```

ระบุว่าจะวาดกรอบรอบสไลด์ที่แสดงหรือไม่.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintFrameSlide(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new Dimension(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

ค่าเริ่มต้นคือ  **true** .

**Returns:**
boolean
### setPrintFrameSlide(boolean value) {#setPrintFrameSlide-boolean-}
```
public final void setPrintFrameSlide(boolean value)
```

ระบุว่าจะวาดกรอบรอบสไลด์ที่แสดงหรือไม่.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintFrameSlide(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new Dimension(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

ค่าเริ่มต้นคือ  **true** .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPrintComments() {#getPrintComments--}
```
public final boolean getPrintComments()
```

ระบุว่าจะเปิดแสดงความคิดเห็นบนสไลด์หรือไม่

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintComments(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new Dimension(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

ค่าเริ่มต้นคือ  **false** .

**Returns:**
boolean
### setPrintComments(boolean value) {#setPrintComments-boolean-}
```
public final void setPrintComments(boolean value)
```

ระบุว่าจะเปิดแสดงความคิดเห็นบนสไลด์หรือไม่

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintComments(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new Dimension(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

ค่าเริ่มต้นคือ  **false** .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |