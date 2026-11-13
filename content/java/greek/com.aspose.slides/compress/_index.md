---
title: Compress
second_title: Aspose.Slides για Java API Αναφορά
description: Αναπαριστά μια ομάδα μεθόδων που προορίζονται για συμπίεση .
type: docs
url: /el/com.aspose.slides/compress/
---
**Κληρονομικότητα:**
java.lang.Object
```
public class Compress
```

Αναπαριστά μια ομάδα μεθόδων που προορίζονται για συμπίεση του [Presentation](../../com.aspose.slides/presentation).

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
| [compressPresentation(Presentation presentation)](#compressPresentation-com.aspose.slides.Presentation-) | Μειώνει το μέγεθος μιας παρουσίασης εφαρμόζοντας όλα τα διαθέσιμα βήματα συμπίεσης:

 *  Αφαιρεί αχρησιμοποίητες κύριες διαφάνειες \#removeUnusedMasterSlides(Presentation).removeUnusedMasterSlides(Presentation).
 *  Αφαιρεί αχρησιμοποίητες διαφάνειες διάταξης \#removeUnusedLayoutSlides(Presentation).removeUnusedLayoutSlides(Presentation).
 *  Διατηρεί μόνο τα γλύφια που χρησιμοποιούνται πραγματικά σε ενσωματωμένες γραμματοσειρές \#compressEmbeddedFonts(Presentation).compressEmbeddedFonts(Presentation).
 *  Μειώνει την ανάλυση των εικόνων σε 150 DPI και διαγράφει τις περικομμένες περιοχές των εικόνων \#compressImages(IPresentation,int).compressImages(IPresentation,int). |
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | Πραγματοποιεί συμπίεση του [Presentation](../../com.aspose.slides/presentation) αφαιρώντας αχρησιμοποίητες κύριες διαφάνειες. |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | Πραγματοποιεί συμπίεση του [Presentation](../../com.aspose.slides/presentation) αφαιρώντας αχρησιμοποίητες διαφάνειες διάταξης. |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | Πραγματοποιεί συμπίεση του [Presentation](../../com.aspose.slides/presentation) αφαιρώντας αχρησιμοποίητους χαρακτήρες από ενσωματωμένες γραμματοσειρές. |
| [compressImages(IPresentation presentation, int resolution)](#compressImages-com.aspose.slides.IPresentation-int-) | Μειώνει την ανάλυση των εικόνων στην παρουσίαση και διαγράφει τις περικομμένες περιοχές τους, παρόμοια με το "Compress Pictures" του PowerPoint που εφαρμόζεται σε όλες τις εικόνες. |
### Compress() {#Compress--}
```
public Compress()
```


### compressPresentation(Presentation presentation) {#compressPresentation-com.aspose.slides.Presentation-}
```
public static void compressPresentation(Presentation presentation)
```


Μειώνει το μέγεθος μιας παρουσίασης εφαρμόζοντας όλα τα διαθέσιμα βήματα συμπίεσης:

 *  Αφαιρεί αχρησιμοποίητες κύριες διαφάνειες \#removeUnusedMasterSlides(Presentation).removeUnusedMasterSlides(Presentation).
 *  Αφαιρεί αχρησιμοποίητες διαφάνειες διάταξης \#removeUnusedLayoutSlides(Presentation).removeUnusedLayoutSlides(Presentation).
 *  Διατηρεί μόνο τα γλύφια που χρησιμοποιούνται πραγματικά σε ενσωματωμένες γραμματοσειρές \#compressEmbeddedFonts(Presentation).compressEmbeddedFonts(Presentation).
 *  Μειώνει την ανάλυση των εικόνων σε 150 DPI και διαγράφει τις περικομμένες περιοχές των εικόνων \#compressImages(IPresentation,int).compressImages(IPresentation,int).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.compressPresentation(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| presentation | [Presentation](../../com.aspose.slides/presentation) | Η παρουσίαση προς συμπίεση.

--------------------

Για να προσαρμόσετε τη συμπίεση, για παράδειγμα για να χρησιμοποιήσετε διαφορετική ανάλυση εικόνας ή να παραλείψετε ένα βήμα, καλέστε τις παραπάνω μεθόδους ξεχωριστά αντί για αυτήν. Οι περικομμένες περιοχές των εικόνων διαγράφονται μόνιμα και δεν μπορούν να επαναφερθούν στο PowerPoint. |

### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```


Πραγματοποιεί συμπίεση του [Presentation](../../com.aspose.slides/presentation) αφαιρώντας αχρησιμοποίητες κύριες διαφάνειες.

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
| pres | [Presentation](../../com.aspose.slides/presentation) | Το αντικείμενο παρουσίασης.

### removeUnusedLayoutSlides(Presentation pres) {#removeUnusedLayoutSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedLayoutSlides(Presentation pres)
```


Πραγματοποιεί συμπίεση του [Presentation](../../com.aspose.slides/presentation) αφαιρώντας αχρησιμοποίητες διαφάνειες διάταξης.

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
| pres | [Presentation](../../com.aspose.slides/presentation) | Το αντικείμενο παρουσίασης.

### compressEmbeddedFonts(Presentation pres) {#compressEmbeddedFonts-com.aspose.slides.Presentation-}
```
public static void compressEmbeddedFonts(Presentation pres)
```


Πραγματοποιεί συμπίεση του [Presentation](../../com.aspose.slides/presentation) αφαιρώντας αχρησιμοποίητους χαρακτήρες από ενσωματωμένες γραμματοσειρές.

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
| pres | [Presentation](../../com.aspose.slides/presentation) | Το αντικείμενο παρουσίασης.

### compressImages(IPresentation presentation, int resolution) {#compressImages-com.aspose.slides.IPresentation-int-}
```
public static void compressImages(IPresentation presentation, int resolution)
```


Μειώνει την ανάλυση των εικόνων στην παρουσίαση και διαγράφει τις περικομμένες περιοχές τους, παρόμοια με το "Compress Pictures" του PowerPoint που εφαρμόζεται σε όλες τις εικόνες. Επεξεργάζονται εικόνες σε διαφάνειες, διαφάνειες διάταξης και κύριες διαφάνειες, συμπεριλαμβανομένων των εικόνων εντός ομαδικών σχημάτων και γεμίσματος εικόνας σχήματος.

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

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Η παρουσίαση προς επεξεργασία. |
| resolution | int | Η επιθυμητή ανάλυση σε σχέση με το μέγεθος στο οποίο εμφανίζεται κάθε εικόνα. [PicturesCompression.DocumentResolution](../../com.aspose.slides/picturescompression\#DocumentResolution) αφήνει τις εικόνες αμετάβλητες.

Οι εικόνες που ήδη έχουν τη στόχευση ανάλυση ή είναι κάτω από αυτήν αφήνονται αμετάβλητες· οι εικόνες δεν αυξάνονται ποτέ σε ανάλυση.

Δεν επεξεργάζονται: φόντα διαφανειών, γεμίσματα κελιών πινάκων, διαγράμματα, SmartArt, εικόνες GIF (για διατήρηση της κίνησης), εικόνες SVG και μετααρχεία (EMF/WMF).

Οι περικομμένες περιοχές διαγράφονται μόνιμα και δεν μπορούν να επαναφερθούν στο PowerPoint. |