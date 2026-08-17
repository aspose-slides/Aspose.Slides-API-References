---
title: Compress
second_title: Aspose.Slides για το Java API Αναφορά
description: Αντιπροσωπεύει μια ομάδα μεθόδων που προορίζονται να συμπιέσουν .
type: docs
url: /el/com.aspose.slides/compress/
---
**Κληρονομικότητα:**
java.lang.Object
```
public class Compress
```

Αντιπροσωπεύει μια ομάδα μεθόδων που προορίζονται να συμπιέσουν [Presentation](../../com.aspose.slides/presentation).

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
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Compress()](#Compress--) |  |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | Πραγματοποιεί τη συμπίεση του [Presentation](../../com.aspose.slides/presentation) αφαιρώντας αχρησιμοποίητες κύριες διαφάνειες. |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | Πραγματοποιεί τη συμπίεση του [Presentation](../../com.aspose.slides/presentation) αφαιρώντας αχρησιμοποίητες διαφάνειες διάταξης. |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | Πραγματοποιεί τη συμπίεση του [Presentation](../../com.aspose.slides/presentation) αφαιρώντας αχρησιμοποίητους χαρακτήρες από τις ενσωματωμένες γραμματοσειρές. |

### Compress() {#Compress--}
```
public Compress()
```

### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```

Πραγματοποιεί τη συμπίεση του [Presentation](../../com.aspose.slides/presentation) αφαιρώντας αχρησιμοποίητες κύριες διαφάνειες.

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

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Το αντικείμενο παρουσίασης |

### removeUnusedLayoutSlides(Presentation pres) {#removeUnusedLayoutSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedLayoutSlides(Presentation pres)
```

Πραγματοποιεί τη συμπίεση του [Presentation](../../com.aspose.slides/presentation) αφαιρώντας αχρησιμοποίητες διαφάνειες διάταξης.

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

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Το αντικείμενο παρουσίασης |

### compressEmbeddedFonts(Presentation pres) {#compressEmbeddedFonts-com.aspose.slides.Presentation-}
```
public static void compressEmbeddedFonts(Presentation pres)
```

Πραγματοποιεί τη συμπίεση του [Presentation](../../com.aspose.slides/presentation) αφαιρώντας αχρησιμοποίητους χαρακτήρες από τις ενσωματωμένες γραμματοσειρές.

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

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Το αντικείμενο παρουσίασης |