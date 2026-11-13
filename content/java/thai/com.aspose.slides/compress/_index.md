---
title: Compress
second_title: อ้างอิง API ของ Aspose.Slides for Java
description: เป็นกลุ่มของเมธอดที่มีจุดมุ่งหมายเพื่อบีบอัด
type: docs
url: /th/com.aspose.slides/compress/
---
**การสืบทอด:**
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
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [Compress()](#Compress--) |  |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [compressPresentation(Presentation presentation)](#compressPresentation-com.aspose.slides.Presentation-) | ลดขนาดของงานนำเสนอโดยใช้ขั้นตอนบีบอัดที่มีทั้งหมด:

 *  ลบสไลด์แม่แบบที่ไม่ได้ใช้ \#removeUnusedMasterSlides(Presentation).removeUnusedMasterSlides(Presentation).
 *  ลบสไลด์เลเอาต์ที่ไม่ได้ใช้ \#removeUnusedLayoutSlides(Presentation).removeUnusedLayoutSlides(Presentation).
 *  คงไว้เฉพาะ glyph ที่ใช้จริงในฟอนต์ที่ฝังอยู่ \#compressEmbeddedFonts(Presentation).compressEmbeddedFonts(Presentation).
 *  ลดความละเอียดของรูปภาพเป็น 150 DPI และลบพื้นที่ที่ถูกครอปของรูปภาพ \#compressImages(IPresentation,int).compressImages(IPresentation,int). |
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | ทำการบีบอัดของ [Presentation](../../com.aspose.slides/presentation) โดยการลบสไลด์แม่แบบที่ไม่ได้ใช้. |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | ทำการบีบอัดของ [Presentation](../../com.aspose.slides/presentation) โดยการลบสไลด์เลเอาต์ที่ไม่ได้ใช้. |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | ทำการบีบอัดของ [Presentation](../../com.aspose.slides/presentation) โดยการลบอักขระที่ไม่ได้ใช้จากฟอนต์ที่ฝังอยู่. |
| [compressImages(IPresentation presentation, int resolution)](#compressImages-com.aspose.slides.IPresentation-int-) | ลดความละเอียดของรูปภาพในงานนำเสนอและลบพื้นที่ที่ถูกครอปของรูปภาพ เหมือนกับฟีเจอร์ "Compress Pictures" ของ PowerPoint ที่ใช้กับรูปภาพทั้งหมด. |
### Compress() {#Compress--}
```
public Compress()
```

### compressPresentation(Presentation presentation) {#compressPresentation-com.aspose.slides.Presentation-}
```
public static void compressPresentation(Presentation presentation)
```

ลดขนาดของงานนำเสนอโดยใช้ขั้นตอนบีบอัดที่มีทั้งหมด:

 *  ลบสไลด์แม่แบบที่ไม่ได้ใช้ \#removeUnusedMasterSlides(Presentation).removeUnusedMasterSlides(Presentation).
 *  ลบสไลด์เลเอาต์ที่ไม่ได้ใช้ \#removeUnusedLayoutSlides(Presentation).removeUnusedLayoutSlides(Presentation).
 *  คงไว้เฉพาะ glyph ที่ใช้จริงในฟอนต์ที่ฝังอยู่ \#compressEmbeddedFonts(Presentation).compressEmbeddedFonts(Presentation).
 *  ลดความละเอียดของรูปภาพเป็น 150 DPI และลบพื้นที่ที่ถูกครอปของรูปภาพ \#compressImages(IPresentation,int).compressImages(IPresentation,int).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.compressPresentation(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| presentation | [Presentation](../../com.aspose.slides/presentation) | งานนำเสนอที่ต้องการบีบอัด.

--------------------

หากต้องการปรับแต่งการบีบอัด เช่น ใช้ความละเอียดของรูปภาพที่แตกต่างหรือข้ามขั้นตอนบางอย่าง ให้เรียกเมธอดที่ระบุไว้ข้างต้นอย่างเดี่ยวแทนการใช้เมธอดนี้ พื้นที่ที่ถูกครอปของรูปภาพจะถูกลบอย่างถาวรและไม่สามารถกู้คืนได้ใน PowerPoint. |

### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```

ทำการบีบอัดของ [Presentation](../../com.aspose.slides/presentation) โดยการลบสไลด์แม่แบบที่ไม่ได้ใช้.

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
| pres | [Presentation](../../com.aspose.slides/presentation) | อินสแตนซ์ของงานนำเสนอ

### removeUnusedLayoutSlides(Presentation pres) {#removeUnusedLayoutSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedLayoutSlides(Presentation pres)
```

ทำการบีบอัดของ [Presentation](../../com.aspose.slides/presentation) โดยการลบสไลด์เลเอาต์ที่ไม่ได้ใช้.

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
| pres | [Presentation](../../com.aspose.slides/presentation) | อินสแตนซ์ของงานนำเสนอ

### compressEmbeddedFonts(Presentation pres) {#compressEmbeddedFonts-com.aspose.slides.Presentation-}
```
public static void compressEmbeddedFonts(Presentation pres)
```

ทำการบีบอัดของ [Presentation](../../com.aspose.slides/presentation) โดยการลบอักขระที่ไม่ได้ใช้จากฟอนต์ที่ฝังอยู่.

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
| pres | [Presentation](../../com.aspose.slides/presentation) | อินสแตนซ์ของงานนำเสนอ

### compressImages(IPresentation presentation, int resolution) {#compressImages-com.aspose.slides.IPresentation-int-}
```
public static void compressImages(IPresentation presentation, int resolution)
```

ลดความละเอียดของรูปภาพในงานนำเสนอและลบพื้นที่ที่ถูกครอปของรูปภาพ เหมือนกับฟีเจอร์ "Compress Pictures" ของ PowerPoint ที่ใช้กับรูปภาพทั้งหมด รูปภาพบนสไลด์, สไลด์เลเอาต์และสไลด์แม่แบบจะถูกประมวลผลรวมถึงรูปภาพภายในกลุ่มรูปร่างและการเติมรูปภาพของรูปร่าง.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.compressImages(pres, PicturesCompression.Dpi150);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | งานนำเสนอที่ต้องการประมวลผล. |
| resolution | int | ความละเอียดเป้าหมายสัมพันธ์กับขนาดที่รูปภาพแต่ละรูปถูกแสดง [PicturesCompression.DocumentResolution](../../com.aspose.slides/picturescompression\#DocumentResolution) จะไม่เปลี่ยนรูปภาพ.

รูปภาพที่มีความละเอียดเท่ากับหรือต่ำกว่าความละเอียดเป้าหมายจะไม่ถูกเปลี่ยนแปลง; รูปภาพจะไม่ถูกขยายขึ้น.

ไม่ได้ประมวลผล: พื้นหลังสไลด์, การเติมเซลล์ตาราง, แผนภูมิ, SmartArt, รูปภาพ GIF (เพื่อรักษาการเคลื่อนไหว), รูปภาพ SVG และเมตาไฟล์ (EMF/WMF).

พื้นที่ที่ถูกครอปจะถูกลบอย่างถาวรและไม่สามารถกู้คืนได้ใน PowerPoint. |