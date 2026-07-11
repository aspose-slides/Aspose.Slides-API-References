---
title: SlideImageFormat
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Καθορίζει τη μορφή στην οποία θα αποθηκευτεί η εικόνα της διαφάνειας για εξαγωγή παρουσίασης σε HTML.
type: docs
url: /el/com.aspose.slides/slideimageformat/
---
**Κληρονομιά:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ISlideImageFormat](../../com.aspose.slides/islideimageformat)
```
public class SlideImageFormat implements ISlideImageFormat
```

Καθορίζει τη μορφή στην οποία θα αποθηκευτεί η εικόνα της διαφάνειας για εξαγωγή παρουσίασης σε HTML export.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [SlideImageFormat()](#SlideImageFormat--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [svg(SVGOptions options)](#svg-com.aspose.slides.SVGOptions-) | Οι διαφάνειες πρέπει να μετατραπούν σε μορφή SVG. |
| [bitmap(float scale, int imageFormat)](#bitmap-float-int-) | Οι διαφάνειες πρέπει να μετατραπούν σε raster εικόνα. |
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


Οι διαφάνειες πρέπει να μετατραπούν σε raster εικόνα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| scale | float | Ο συντελεστής κατά τον οποίο κλιμακώνεται η έξοδος εικόνας. |
| imageFormat | int | Η μορφή της προκύπτουσας εικόνας (π.χ., PNG, JPEG). |

**Επιστρέφει:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) -