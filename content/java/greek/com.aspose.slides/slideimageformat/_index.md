---
title: SlideImageFormat
second_title: Aspose.Slides για την Αναφορά API Java
description: Καθορίζει τη μορφή στην οποία θα αποθηκευτεί η εικόνα διαφάνειας για εξαγωγή παρουσίασης σε HTML.
type: docs
url: /el/com.aspose.slides/slideimageformat/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ISlideImageFormat](../../com.aspose.slides/islideimageformat)
```
public class SlideImageFormat implements ISlideImageFormat
```

Καθορίζει τη μορφή στην οποία θα αποθηκευτεί η εικόνα διαφάνειας για εξαγωγή παρουσίασης σε HTML.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [SlideImageFormat()](#SlideImageFormat--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [svg(SVGOptions options)](#svg-com.aspose.slides.SVGOptions-) | Slides should converted to a SVG format. |
| [bitmap(float scale, int imageFormat)](#bitmap-float-int-) | Slides should be converted to a raster image. |
### SlideImageFormat() {#SlideImageFormat--}
```
public SlideImageFormat()
```


### svg(SVGOptions options) {#svg-com.aspose.slides.SVGOptions-}
```
public static SlideImageFormat svg(SVGOptions options)
```


Οι διαφάνειες πρέπει να μετατραπούν σε μορφή SVG.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [SVGOptions](../../com.aspose.slides/svgoptions) | Επιλογές για εξαγωγή SVG. |

**Επιστρέφει:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) - Το αντικείμενο [SlideImageFormat](../../com.aspose.slides/slideimageformat).
### bitmap(float scale, int imageFormat) {#bitmap-float-int-}
```
public static SlideImageFormat bitmap(float scale, int imageFormat)
```


Οι διαφάνειες πρέπει να μετατραπούν σε εικόνα raster.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| scale | float | Ο παράγοντας με τον οποίο κλιμακώνεται η έξοδος εικόνας. |
| imageFormat | int | Η μορφή της προκύπτουσας εικόνας (π.χ., PNG, JPEG). |

**Επιστρέφει:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) -