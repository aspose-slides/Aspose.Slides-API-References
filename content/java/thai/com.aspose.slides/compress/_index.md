---
title: Compress
second_title: Aspose.Slides สำหรับ Java API Reference
description: เป็นกลุ่มของเมธอดที่มีจุดมุ่งหมายเพื่อบีบอัด .
type: docs
url: /th/com.aspose.slides/compress/
---
**Inheritance:**  
java.lang.Object  
```
public class Compress
```

เป็นกลุ่มของเมธอดที่มีจุดมุ่งหมายเพื่อบีบอัด [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.removeUnusedMasterSlides(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [Compress()](#Compress--) |  |
## Methods

| Method | Description |
| --- | --- |
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | ทำการบีบอัด [Presentation](../../com.aspose.slides/presentation) โดยการลบสไลด์มาสเตอร์ที่ไม่ได้ใช้ออก |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | ทำการบีบอัด [Presentation](../../com.aspose.slides/presentation) โดยการลบสไลด์เค้าโครงที่ไม่ได้ใช้ออก |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | ทำการบีบอัด [Presentation](../../com.aspose.slides/presentation) โดยการลบอักขระที่ไม่ได้ใช้จากฟอนต์ฝังตัว |

### Compress() {#Compress--}
```
public Compress()
```

### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```

ทำการบีบอัด [Presentation](../../com.aspose.slides/presentation) โดยการลบสไลด์มาสเตอร์ที่ไม่ได้ใช้ออก

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.removeUnusedMasterSlides(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | อินสแตนซ์ของ Presentation |

### removeUnusedLayoutSlides(Presentation pres) {#removeUnusedLayoutSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedLayoutSlides(Presentation pres)
```

ทำการบีบอัด [Presentation](../../com.aspose.slides/presentation) โดยการลบสไลด์เค้าโครงที่ไม่ได้ใช้ออก

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.removeUnusedLayoutSlides(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | อินสแตนซ์ของ Presentation |

### compressEmbeddedFonts(Presentation pres) {#compressEmbeddedFonts-com.aspose.slides.Presentation-}
```
public static void compressEmbeddedFonts(Presentation pres)
```

ทำการบีบอัด [Presentation](../../com.aspose.slides/presentation) โดยการลบอักขระที่ไม่ได้ใช้จากฟอนต์ฝังตัว

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.compressEmbeddedFonts(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | อินสแตนซ์ของ Presentation |