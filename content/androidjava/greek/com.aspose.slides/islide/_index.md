---
title: ISlide
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Αναπαριστά μια διαφάνεια σε μια παρουσίαση.
type: docs
url: /el/com.aspose.slides/islide/
---
**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ISlide extends IBaseSlide, IOverrideThemeable
```

Αναπαριστά μια διαφάνεια σε μια παρουσίαση.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Επιστρέφει τον διαχειριστή HeaderFooter της διαφάνειας. |
| [getSlideNumber()](#getSlideNumber--) | Επιστρέφει τον αριθμό της διαφάνειας. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | Επιστρέφει τον αριθμό της διαφάνειας. |
| [getHidden()](#getHidden--) | Καθορίζει εάν η συγκεκριμένη διαφάνεια είναι κρυφή κατά τη διάρκεια παρουσίασης. |
| [setHidden(boolean value)](#setHidden-boolean-) | Καθορίζει εάν η συγκεκριμένη διαφάνεια είναι κρυφή κατά τη διάρκεια παρουσίασης. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Επιστρέφει ένα αντικείμενο εικόνας με προσαρμοσμένη κλιμάκωση. |
| [getImage()](#getImage--) | Επιστρέφει ένα αντικείμενο Εικόνας μικρογραφίας (20 % του πραγματικού μεγέθους). |
| [getImage(Size imageSize)](#getImage-com.aspose.slides.android.Size-) | Επιστρέφει ένα αντικείμενο εικόνας με καθορισμένο μέγεθος. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | Επιστρέφει ένα αντικείμενο μικρογραφίας TIFF bitmap με καθορισμένες παραμέτρους. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | Επιστρέφει ένα αντικείμενο μικρογραφίας Bitmap. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | Επιστρέφει ένα αντικείμενο μικρογραφίας Bitmap με προσαρμοσμένη κλιμάκωση. |
| [getImage(IRenderingOptions options, Size imageSize)](#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Επιστρέφει ένα αντικείμενο μικρογραφίας Bitmap με καθορισμένο μέγεθος. |
| [getLayoutSlide()](#getLayoutSlide--) | Επιστρέφει ή ορίζει τη layout slide για την τρέχουσα διαφάνεια. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | Επιστρέφει ή ορίζει τη layout slide για την τρέχουσα διαφάνεια. |
| [getNotesSlideManager()](#getNotesSlideManager--) | Επιτρέπει την πρόσβαση στη notes slide, την προσθήκη και την αφαίρεσή της. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | Επιστρέφει όλα τα σχόλια διαφάνειας που προστέθηκαν από συγκεκριμένο συγγραφέα. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Αποθηκεύει το περιεχόμενο της διαφάνειας ως αρχείο SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Αποθηκεύει το περιεχόμενο της διαφάνειας ως αρχείο SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Αποθηκεύει το περιεχόμενο της διαφάνειας ως αρχείο EMF. |
| [remove()](#remove--) | Αφαιρεί τη διαφάνεια από την παρουσίαση. |
| [reset()](#reset--) | Επαναφέρει τη θέση, το μέγεθος και τη μορφοποίηση όλων των σχημάτων που έχουν πρωτότυπο στη LayoutSlide. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ISlideHeaderFooterManager getHeaderFooterManager()
```


Επιστρέφει τον διαχειριστή HeaderFooter της διαφάνειας. Μόνο για ανάγνωση [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**Επιστρέφει:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)
### getSlideNumber() {#getSlideNumber--}
```
public abstract int getSlideNumber()
```


Επιστρέφει τον αριθμό της διαφάνειας. Ο δείκτης της διαφάνειας στη συλλογή [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) είναι πάντα ίσος με SlideNumber - 1. Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public abstract void setSlideNumber(int value)
```


Επιστρέφει τον αριθμό της διαφάνειας. Ο δείκτης της διαφάνειας στη συλλογή [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) είναι πάντα ίσος με SlideNumber - 1. Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```


Καθορίζει εάν η συγκεκριμένη διαφάνεια είναι κρυφή κατά τη διάρκεια παρουσίασης. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```


Καθορίζει εάν η συγκεκριμένη διαφάνεια είναι κρυφή κατά τη διάρκεια παρουσίασης. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
```


Επιστρέφει ένα αντικείμενο εικόνας με προσαρμοσμένη κλιμάκωση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| scaleX | float | Η τιμή με την οποία θα κλιμακώσετε αυτή τη μικρογραφία στην κατεύθυνση του άξονα x. |
| scaleY | float | Η τιμή με την οποία θα κλιμακώσετε αυτή τη μικρογραφία στην κατεύθυνση του άξονα y. |

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage) - Image object android.graphics.Bitmap
### getImage() {#getImage--}
```
public abstract IImage getImage()
```


Επιστρέφει ένα αντικείμενο Εικόνας μικρογραφίας (20 % του πραγματικού μεγέθους).

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage) - Image object android.graphics.Bitmap
### getImage(Size imageSize) {#getImage-com.aspose.slides.android.Size-}
```
public abstract IImage getImage(Size imageSize)
```


Επιστρέφει ένα αντικείμενο εικόνας με καθορισμένο μέγεθος.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| imageSize | [Size](../../com.aspose.slides.android/size) | Μέγεθος της εικόνας που θα δημιουργηθεί. |

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage) - Bitmap object.
### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public abstract IImage getImage(ITiffOptions options)
```


Επιστρέφει ένα αντικείμενο μικρογραφίας TIFF bitmap με καθορισμένες παραμέτρους.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Ρυθμίσεις Tiff. |

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage) - Image object.
### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage getImage(IRenderingOptions options)
```


Επιστρέφει ένα αντικείμενο μικρογραφίας Bitmap.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Ρυθμίσεις απόδοσης. |

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```


Επιστρέφει ένα αντικείμενο μικρογραφίας Bitmap με προσαρμοσμένη κλιμάκωση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Ρυθμίσεις απόδοσης. |
| scaleX | float | Η τιμή με την οποία θα κλιμακώσετε αυτή τη μικρογραφία στην κατεύθυνση του άξονα x. |
| scaleY | float | Η τιμή με την οποία θα κλιμακώσετε αυτή τη μικρογραφία στην κατεύθυνση του άξονα y. |

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getImage(IRenderingOptions options, Size imageSize) {#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public abstract IImage getImage(IRenderingOptions options, Size imageSize)
```


Επιστρέφει ένα αντικείμενο μικρογραφίας Bitmap με καθορισμένο μέγεθος.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Ρυθμίσεις απόδοσης. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Μέγεθος της εικόνας που θα δημιουργηθεί. |

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getLayoutSlide() {#getLayoutSlide--}
```
public abstract ILayoutSlide getLayoutSlide()
```


Επιστρέφει ή ορίζει τη layout slide για την τρέχουσα διαφάνεια. Ανάγνωση/εγγραφή [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Επιστρέφει:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public abstract void setLayoutSlide(ILayoutSlide value)
```


Επιστρέφει ή ορίζει τη layout slide για την τρέχουσα διαφάνεια. Ανάγνωση/εγγραφή [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |

### getNotesSlideManager() {#getNotesSlideManager--}
```
public abstract INotesSlideManager getNotesSlideManager()
```


Επιτρέπει την πρόσβαση στη notes slide, την προσθήκη και την αφαίρεσή της. Μόνο για ανάγνωση [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**Επιστρέφει:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public abstract IComment[] getSlideComments(ICommentAuthor author)
```


Επιστρέφει όλα τα σχόλια διαφάνειας που προστέθηκαν από συγκεκριμένο συγγραφέα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Συγγραφέας των σχολίων προς εύρεση ή null για επιστροφή όλων των σχολίων. |

**Επιστρέφει:**
com.aspose.slides.IComment[] - Array of [IComment](../../com.aspose.slides/icomment).
### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```


Αποθηκεύει το περιεχόμενο της διαφάνειας ως αρχείο SVG.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | Στοχευόμενη ροή |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```


Αποθηκεύει το περιεχόμενο της διαφάνειας ως αρχείο SVG.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | Στοχευόμενη ροή |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Ρυθμίσεις δημιουργίας SVG |

### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```


Αποθηκεύει το περιεχόμενο της διαφάνειας ως αρχείο EMF.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | Στοχευόμενη ροή |

### remove() {#remove--}
```
public abstract void remove()
```


Αφαιρεί τη διαφάνεια από την παρουσίαση.

### reset() {#reset--}
```
public abstract void reset()
```


Επαναφέρει τη θέση, το μέγεθος και τη μορφοποίηση όλων των σχημάτων που έχουν πρωτότυπο στη LayoutSlide.