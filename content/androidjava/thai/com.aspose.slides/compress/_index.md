---
title: Compress
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: เป็นกลุ่มของเมธอดที่ออกแบบมาเพื่อบีบอัด .
type: docs
url: /th/com.aspose.slides/compress/
---
**การสืบทอด:**
java.lang.Object
```
public class Compress
```

เป็นกลุ่มของเมธอดที่ออกแบบมาเพื่อบีบอัด [Presentation](../../com.aspose.slides/presentation).

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
## ตัวสร้าง

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [Compress()](#Compress--) |  |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | ทำการบีบอัด [Presentation](../../com.aspose.slides/presentation) โดยการลบสไลด์แม่ที่ไม่ได้ใช้ |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | ทำการบีบอัด [Presentation](../../com.aspose.slides/presentation) โดยการลบสไลด์เค้าโครงที่ไม่ได้ใช้ |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | ทำการบีบอัด [Presentation](../../com.aspose.slides/presentation) โดยการลบอักขระที่ไม่ได้ใช้จากฟอนต์ที่ฝังไว้ |
### Compress() {#Compress--}
```
public Compress()
```


### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```


ทำการบีบอัด [Presentation](../../com.aspose.slides/presentation) โดยการลบสไลด์แม่ที่ไม่ได้ใช้

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

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | อินสแตนซ์ของการนำเสนอ |

### removeUnusedLayoutSlides(Presentation pres) {#removeUnusedLayoutSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedLayoutSlides(Presentation pres)
```


ทำการบีบอัด [Presentation](../../com.aspose.slides/presentation) โดยการลบสไลด์เค้าโครงที่ไม่ได้ใช้

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

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | อินสแตนซ์ของการนำเสนอ |

### compressEmbeddedFonts(Presentation pres) {#compressEmbeddedFonts-com.aspose.slides.Presentation-}
```
public static void compressEmbeddedFonts(Presentation pres)
```


ทำการบีบอัด [Presentation](../../com.aspose.slides/presentation) โดยการลบอักขระที่ไม่ได้ใช้จากฟอนต์ที่ฝังไว้

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

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | อินสแตนซ์ของการนำเสนอ |