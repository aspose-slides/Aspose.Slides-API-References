---
title: ISlide
second_title: Aspose.Slides για την Αναφορά API του Java
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
| [getSlideNumber()](#getSlideNumber--) | Επιστρέφει έναν αριθμό διαφάνειας. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | Επιστρέφει έναν αριθμό διαφάνειας. |
| [getHidden()](#getHidden--) | Καθορίζει αν η συγκεκριμένη διαφάνεια είναι κρυφή κατά τη διάρκεια της παρουσίασης. |
| [setHidden(boolean value)](#setHidden-boolean-) | Καθορίζει αν η συγκεκριμένη διαφάνεια είναι κρυφή κατά τη διάρκεια της παρουσίασης. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Επιστρέφει ένα αντικείμενο εικόνας με προσαρμοσμένη κλιμάκωση. |
| [getImage()](#getImage--) | Επιστρέφει ένα αντικείμενο εικόνας μικρογραφίας (20% του πραγματικού μεγέθους). |
| [getImage(Dimension imageSize)](#getImage-java.awt.Dimension-) | Επιστρέφει ένα αντικείμενο εικόνας με καθορισμένο μέγεθος. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | Επιστρέφει ένα αντικείμενο bitmap tiff μικρογραφίας με καθορισμένες παραμέτρους. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | Επιστρέφει ένα αντικείμενο Bitmap μικρογραφίας. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | Επιστρέφει ένα αντικείμενο Bitmap μικρογραφίας με προσαρμοσμένη κλιμάκωση. |
| [getImage(IRenderingOptions options, Dimension imageSize)](#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Επιστρέφει ένα αντικείμενο Bitmap μικρογραφίας με καθορισμένο μέγεθος. |
| [getLayoutSlide()](#getLayoutSlide--) | Επιστρέφει ή ορίζει τη διαφάνεια διάταξης για την τρέχουσα διαφάνεια. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | Επιστρέφει ή ορίζει τη διαφάνεια διάταξης για την τρέχουσα διαφάνεια. |
| [getNotesSlideManager()](#getNotesSlideManager--) | Επιτρέπει την πρόσβαση στη διαφάνεια σημειώσεων, την προσθήκη και την αφαίρεσή της. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | Επιστρέφει όλα τα σχόλια της διαφάνειας που προστέθηκαν από συγκεκριμένο συγγραφέα. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Αποθηκεύει το περιεχόμενο της διαφάνειας ως αρχείο SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Αποθηκεύει το περιεχόμενο της διαφάνειας ως αρχείο SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Αποθηκεύει το περιεχόμενο της διαφάνειας ως αρχείο EMF. |
| [remove()](#remove--) | Αφαιρεί τη διαφάνεια από την παρουσίαση. |
| [reset()](#reset--) | Επαναφέρει τη θέση, το μέγεθος και τη μορφοποίηση κάθε σχήματος που έχει πρωτότυπο στο LayoutSlide. |
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

Επιστρέφει έναν αριθμό διαφάνειας. Ο δείκτης της διαφάνειας στη συλλογή [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) είναι πάντα ίσος με SlideNumber - 1. Ανάγνωση/Εγγραφή int.

**Επιστρέφει:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public abstract void setSlideNumber(int value)
```

Επιστρέφει έναν αριθμό διαφάνειας. Ο δείκτης της διαφάνειας στη συλλογή [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) είναι πάντα ίσος με SlideNumber - 1. Ανάγνωση/Εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

Καθορίζει αν η συγκεκριμένη διαφάνεια είναι κρυφή κατά τη διάρκεια της παρουσίασης. Ανάγνωση/Εγγραφή boolean.

**Επιστρέφει:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

Καθορίζει αν η συγκεκριμένη διαφάνεια είναι κρυφή κατά τη διάρκεια της παρουσίασης. Ανάγνωση/Εγγραφή boolean.

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
| scaleX | float | Η τιμή με την οποία κλιμακώνεται αυτή η μικρογραφία στον άξονα x. |
| scaleY | float | Η τιμή με την οποία κλιμακώνεται αυτή η μικρογραφία στον άξονα y. |

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage) - Αντικείμενο Image java.awt.image.BufferedImage
### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Επιστρέφει ένα αντικείμενο εικόνας μικρογραφίας (20% του πραγματικού μεγέθους).

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage) - Αντικείμενο Image java.awt.image.BufferedImage
### getImage(Dimension imageSize) {#getImage-java.awt.Dimension-}
```
public abstract IImage getImage(Dimension imageSize)
```

Επιστρέφει ένα αντικείμενο εικόνας με καθορισμένο μέγεθος.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| imageSize | java.awt.Dimension | Μέγεθος της εικόνας που θα δημιουργηθεί. |

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage) - Αντικείμενο Bitmap.
### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public abstract IImage getImage(ITiffOptions options)
```

Επιστρέφει ένα αντικείμενο bitmap tiff μικρογραφίας με καθορισμένες παραμέτρους.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Επιλογές Tiff. |

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage) - Αντικείμενο Image.
### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage getImage(IRenderingOptions options)
```

Επιστρέφει ένα αντικείμενο Bitmap μικρογραφίας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Επιλογές Rendering. |

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage) - Αντικείμενα Bitmap.
### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

Επιστρέφει ένα αντικείμενο Bitmap μικρογραφίας με προσαρμοσμένη κλιμάκωση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Επιλογές Rendering. |
| scaleX | float | Η τιμή με την οποία κλιμακώνεται αυτή η μικρογραφία στον άξονα x. |
| scaleY | float | Η τιμή με την οποία κλιμακώνεται αυτή η μικρογραφία στον άξονα y. |

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage) - Αντικείμενα Bitmap.
### getImage(IRenderingOptions options, Dimension imageSize) {#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public abstract IImage getImage(IRenderingOptions options, Dimension imageSize)
```

Επιστρέφει ένα αντικείμενο Bitmap μικρογραφίας με καθορισμένο μέγεθος.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Επιλογές Rendering. |
| imageSize | java.awt.Dimension | Μέγεθος της εικόνας που θα δημιουργηθεί. |

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage) - Αντικείμενα Bitmap.
### getLayoutSlide() {#getLayoutSlide--}
```
public abstract ILayoutSlide getLayoutSlide()
```

Επιστρέφει ή ορίζει τη διαφάνεια διάταξης για την τρέχουσα διαφάνεια. Ανάγνωση/Εγγραφή [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Επιστρέφει:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public abstract void setLayoutSlide(ILayoutSlide value)
```

Επιστρέφει ή ορίζει τη διαφάνεια διάταξης για την τρέχουσα διαφάνεια. Ανάγνωση/Εγγραφή [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |
### getNotesSlideManager() {#getNotesSlideManager--}
```
public abstract INotesSlideManager getNotesSlideManager()
```

Επιτρέπει την πρόσβαση στη διαφάνεια σημειώσεων, την προσθήκη και την αφαίρεσή της. Μόνο για ανάγνωση [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**Επιστρέφει:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public abstract IComment[] getSlideComments(ICommentAuthor author)
```

Επιστρέφει όλα τα σχόλια της διαφάνειας που προστέθηκαν από συγκεκριμένο συγγραφέα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Συγγραφέας των σχολίων προς εύρεση ή null για να επιστραφούν όλα τα σχόλια. |

**Επιστρέφει:**
com.aspose.slides.IComment[] - Πίνακας των [IComment](../../com.aspose.slides/icomment).
### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

Αποθηκεύει το περιεχόμενο της διαφάνειας ως αρχείο SVG.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | Ροή προορισμού |
### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Αποθηκεύει το περιεχόμενο της διαφάνειας ως αρχείο SVG.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | Ροή προορισμού |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Επιλογές δημιουργίας SVG |
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```

Αποθηκεύει το περιεχόμενο της διαφάνειας ως αρχείο EMF.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | Ροή προορισμού |
### remove() {#remove--}
```
public abstract void remove()
```

Αφαιρεί τη διαφάνεια από την παρουσίαση.
### reset() {#reset--}
```
public abstract void reset()
```

Επαναφέρει τη θέση, το μέγεθος και τη μορφοποίηση κάθε σχήματος που έχει πρωτότυπο στο LayoutSlide.