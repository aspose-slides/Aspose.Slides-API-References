---
title: Slide
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αντιπροσωπεύει μια διαφάνεια σε μια παρουσίαση.
type: docs
url: /el/com.aspose.slides/slide/
---
**Κληρονόμηση:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ISlide](../../com.aspose.slides/islide)
```
public final class Slide extends BaseSlide implements ISlide
```

Αναπαριστά μια διαφάνεια σε μια παρουσίαση.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Επιστρέφει τον διαχειριστή HeaderFooter της διαφάνειας. |
| [getThemeManager()](#getThemeManager--) | Επιστρέφει τον διαχειριστή του αντικαθιστάμενου θέματος. |
| [getSlideNumber()](#getSlideNumber--) | Επιστρέφει έναν αριθμό της διαφάνειας. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | Επιστρέφει έναν αριθμό της διαφάνειας. |
| [getHidden()](#getHidden--) | Καθορίζει αν η συγκεκριμένη διαφάνεια είναι κρυφή κατά τη διάρκεια μιας παρουσίασης διαφανειών. |
| [setHidden(boolean value)](#setHidden-boolean-) | Καθορίζει αν η συγκεκριμένη διαφάνεια είναι κρυφή κατά τη διάρκεια μιας παρουσίασης διαφανειών. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Καθορίζει αν τα σχήματα στη διαφάνεια πρότυπο πρέπει να εμφανίζονται στις διαφάνειες ή όχι. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Καθορίζει αν τα σχήματα στη διαφάνεια πρότυπο πρέπει να εμφανίζονται στις διαφάνειες ή όχι. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Επιστρέφει ένα αντικείμενο Thumbnail Image με προσαρμοσμένη κλιμάκωση. |
| [getImage()](#getImage--) | Επιστρέφει ένα αντικείμενο Thumbnail Image (20% του πραγματικού μεγέθους). |
| [getImage(Size imageSize)](#getImage-com.aspose.slides.android.Size-) | Επιστρέφει ένα αντικείμενο Thumbnail Image με συγκεκριμένο μέγεθος. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | Επιστρέφει ένα αντικείμενο Thumbnail tiff image με συγκεκριμένες παραμέτρους. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | Επιστρέφει ένα αντικείμενο Thumbnail Image. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | Επιστρέφει ένα αντικείμενο Thumbnail Image με προσαρμοσμένη κλιμάκωση. |
| [getImage(IRenderingOptions options, Size imageSize)](#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Επιστρέφει ένα αντικείμενο Thumbnail Image με συγκεκριμένο μέγεθος. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Αποθηκεύει το περιεχόμενο της διαφάνειας ως αρχείο SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Αποθηκεύει το περιεχόμενο της διαφάνειας ως αρχείο SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Αποθηκεύει το περιεχόμενο της διαφάνειας ως αρχείο EMF. |
| [remove()](#remove--) | Αφαιρεί τη διαφάνεια από την παρουσίαση. |
| [getLayoutSlide()](#getLayoutSlide--) | Επιστρέφει ή ορίζει τη διαφάνεια διάταξης για την τρέχουσα διαφάνεια. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | Επιστρέφει ή ορίζει τη διαφάνεια διάταξης για την τρέχουσα διαφάνεια. |
| [reset()](#reset--) | Επαναφέρει τη θέση, το μέγεθος και τη μορφοποίηση κάθε σχήματος που έχει πρωτότυπο στο LayoutSlide. |
| [getNotesSlideManager()](#getNotesSlideManager--) | Επιτρέπει την πρόσβαση στη διαφάνεια σημειώσεων, προσθήκη και αφαίρεσή της. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | Επιστρέφει όλα τα σχόλια διαφάνειας που προστέθηκαν από συγκεκριμένο συγγραφέα. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Συνδέει τα runs με την ίδια μορφοποίηση σε όλες τις παραγράφους σε όλα τα αποδεκτά σχήματα. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ISlideHeaderFooterManager getHeaderFooterManager()
```

Επιστρέφει τον διαχειριστή HeaderFooter της διαφάνειας. Μόνο για ανάγνωση [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**Επιστρέφει:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Επιστρέφει τον διαχειριστή του αντικαθιστάμενου θέματος. Μόνο για ανάγνωση [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Επιστρέφει:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```

Επιστρέφει έναν αριθμό της διαφάνειας. Ο δείκτης της διαφάνειας στη συλλογή [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) είναι πάντα ίσος με SlideNumber - Presentation.FirstSlideNumber. Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```

Επιστρέφει έναν αριθμό της διαφάνειας. Ο δείκτης της διαφάνειας στη συλλογή [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) είναι πάντα ίσος με SlideNumber - Presentation.FirstSlideNumber. Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

Καθορίζει αν η συγκεκριμένη διαφάνεια είναι κρυφή κατά τη διάρκεια μιας παρουσίασης διαφανειών. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

Καθορίζει αν η συγκεκριμένη διαφάνεια είναι κρυφή κατά τη διάρκεια μιας παρουσίασης διαφανειών. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Καθορίζει αν τα σχήματα στη διαφάνεια πρότυπο πρέπει να εμφανίζονται στις διαφάνειες ή όχι. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Καθορίζει αν τα σχήματα στη διαφάνεια πρότυπο πρέπει να εμφανίζονται στις διαφάνειες ή όχι. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
```

Επιστρέφει ένα αντικείμενο Thumbnail Image με προσαρμοσμένη κλιμάκωση.

--------------------

> ```
> The following example shows how to generate thumbnails from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("ThumbnailFromSlide.pptx");
>  try {
>      // Πρόσβαση στην πρώτη διαφάνεια
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Δημιουργία εικόνας πλήρους κλίμακας
>      IImage bmp = sld.getImage(1f, 1f);
>      // Αποθήκευση της εικόνας στο δίσκο σε μορφή JPEG
>      bmp.save("Thumbnail_out.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to converting slides to bitmap and saving the images in PNG.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // Μετατρέπει την πρώτη διαφάνεια στην παρουσίαση σε αντικείμενο Bitmap
>      IImage bmp = pres.getSlides().get_Item(0).getImage();
>      // Αποθηκεύει την εικόνα σε μορφή PNG
>      bmp.save("Slide_0.png", ImageFormat.Png);
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint PPT/PPTX to JPG.
>  
>  Presentation pres = new Presentation("PowerPoint-Presentation.ppt");
>  try {
>      for (ISlide sld : pres.getSlides())
>      {
>          // Δημιουργία εικόνας πλήρους κλίμακας
>          IImage bmp = sld.getImage(1f, 1f);
>          // Αποθήκευση της εικόνας στο δίσκο σε μορφή JPEG
>          bmp.save("Slide_"+sld.getSlideNumber()+"0.jpg", ImageFormat.Jpeg);
>      }
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint PPT/PPTX to JPG with customized dimensions.
>  
>  Presentation pres = new Presentation("PowerPoint-Presentation.pptx");
>  try {
>      // Ορισμός διαστάσεων
>      int desiredX = 1200;
>      int desiredY = 800;
>      // Λήψη κλιμακωμένων τιμών του X και Y
>      float ScaleX = (float)(1.0 / pres.getSlideSize().getSize().getWidth()) * desiredX;
>      float ScaleY = (float)(1.0 / pres.getSlideSize().getSize().getHeight()) * desiredY;
>      for (ISlide sld : pres.getSlides())
>      {
>          // Δημιουργία εικόνας πλήρους κλίμακας
>          IImage bmp = sld.getImage(ScaleX, ScaleY);
>          // Αποθήκευση της εικόνας στο δίσκο σε μορφή JPEG
>          bmp.save("Slide.jpg", ImageFormat.Jpeg);
>      }
>  } finally {
>      pres.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| scaleX | float | Η τιμή με την οποία κλιμακώνεται το Thumbnail κατά τον άξονα x. |
| scaleY | float | Η τιμή με την οποία κλιμακώνεται το Thumbnail κατά τον άξονα y. |

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage) - IImage object.
### getImage() {#getImage--}
```
public final IImage getImage()
```

Επιστρέφει ένα αντικείμενο Thumbnail Image (20% του πραγματικού μεγέθους).

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage)
### getImage(Size imageSize) {#getImage-com.aspose.slides.android.Size-}
```
public final IImage getImage(Size imageSize)
```

Επιστρέφει ένα αντικείμενο Thumbnail Image με συγκεκριμένο μέγεθος.

--------------------

> ```
> The following example shows how to converting slides to images with custom sizes using C#.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // Μετατρέπει την πρώτη διαφάνεια στην παρουσίαση σε Bitmap με το καθορισμένο μέγεθος
>      IImage bmp = pres.getSlides().get_Item(0).getImage(new com.aspose.slides.android.Size(1820, 1040));
>      // Αποθηκεύει την εικόνα σε μορφή JPEG
>      bmp.save("Slide_0.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| imageSize | [Size](../../com.aspose.slides.android/size) | Μέγεθος της εικόνας που θα δημιουργηθεί. |

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage) - Image object.
### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public final IImage getImage(ITiffOptions options)
```

Επιστρέφει ένα αντικείμενο Thumbnail tiff image με συγκεκριμένες παραμέτρους.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Tiff options. |

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage) - Image object.
### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public final IImage getImage(IRenderingOptions options)
```

Επιστρέφει ένα αντικείμενο Thumbnail Image.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage) - Image object.
### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

Επιστρέφει ένα αντικείμενο Thumbnail Image με προσαρμοσμένη κλιμάκωση.

--------------------

> ```
> The following example shows how to converting slides With notes and comments to Images.
>  
>  Presentation pres = new Presentation("PresentationNotesComments.pptx");
>  try {
>      // Δημιουργία επιλογών απόδοσης
>      IRenderingOptions options = new RenderingOptions();
>      // Δημιουργία επιλογών διάταξης σημειώσεων και σχολίων
>      NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
>      // Ορίζει τη θέση των σημειώσεων στη σελίδα
>      notesCommentsLayouting.setNotesPosition(NotesPositions.BottomTruncated);
>      // Ορίζει τη θέση των σχολίων στη σελίδα
>      notesCommentsLayouting.setCommentsPosition(CommentsPositions.Right);
>      // Ορίζει το πλάτος της περιοχής εξόδου σχολίων
>      notesCommentsLayouting.setCommentsAreaWidth(500);
>      // Ορίζει το χρώμα για την περιοχή σχολίων
>      notesCommentsLayouting.setCommentsAreaColor(Color.WHITE);
>      // Ορίζει τις επιλογές διάταξης για την απόδοση
>      options.setSlidesLayoutOptions(notesCommentsLayouting);
>      // Μετατρέπει την πρώτη διαφάνεια της παρουσίασης σε αντικείμενο android.graphics.Bitmap object
>      IImage image = pres.getSlides().get_Item(0).getImage(options, 2f, 2f);
>      // Αποθηκεύει την εικόνα σε μορφή GIF
>      image.save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |
| scaleX | float | Η τιμή με την οποία κλιμακώνεται το Thumbnail κατά τον άξονα x. |
| scaleY | float | Η τιμή με την οποία κλιμακώνεται το Thumbnail κατά τον άξονα y. |

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getImage(IRenderingOptions options, Size imageSize) {#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public final IImage getImage(IRenderingOptions options, Size imageSize)
```

Επιστρέφει ένα αντικείμενο Thumbnail Image με συγκεκριμένο μέγεθος.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Μέγεθος της εικόνας που θα δημιουργηθεί. |

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage) - Image object.
### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

Αποθηκεύει το περιεχόμενο της διαφάνειας ως αρχείο SVG.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.svg");
>      {
>          // Αποθηκεύει την πρώτη διαφάνεια ως αρχείο SVG
>          pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | Target stream |
### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Αποθηκεύει το περιεχόμενο της διαφάνειας ως αρχείο SVG.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file with options.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide1.svg");
>      SVGOptions options = new SVGOptions();
>      options.setVectorizeText(true);
>      // Αποθηκεύει την πρώτη διαφάνεια ως αρχείο SVG
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | Target stream |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG generation options |
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```

Αποθηκεύει το περιεχόμενο της διαφάνειας ως αρχείο EMF.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into a metafile.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.emf");
>      {
>          // Αποθηκεύει την πρώτη διαφάνεια ως αρχείο metafile
>          pres.getSlides().get_Item(0).writeAsEmf(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | Target stream |
### remove() {#remove--}
```
public final void remove()
```

Αφαιρεί τη διαφάνεια από την παρουσίαση.
### getLayoutSlide() {#getLayoutSlide--}
```
public final ILayoutSlide getLayoutSlide()
```

Επιστρέφει ή ορίζει τη διαφάνεια διάταξης για την τρέχουσα διαφάνεια. Ανάγνωση/εγγραφή [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Επιστρέφει:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public final void setLayoutSlide(ILayoutSlide value)
```

Επιστρέφει ή ορίζει τη διαφάνεια διάταξης για την τρέχουσα διαφάνεια. Ανάγνωση/εγγραφή [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |
### reset() {#reset--}
```
public final void reset()
```

Επαναφέρει τη θέση, το μέγεθος και τη μορφοποίηση κάθε σχήματος που έχει πρωτότυπο στο LayoutSlide.
### getNotesSlideManager() {#getNotesSlideManager--}
```
public final INotesSlideManager getNotesSlideManager()
```

Επιτρέπει την πρόσβαση στη διαφάνεια σημειώσεων, προσθήκη και αφαίρεσή της. Μόνο για ανάγνωση [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**Επιστρέφει:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public final IComment[] getSlideComments(ICommentAuthor author)
```

Επιστρέφει όλα τα σχόλια διαφάνειας που προστέθηκαν από συγκεκριμένο συγγραφέα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Συγγραφέας των σχολίων για εύρεση ή null για επιστροφή όλων των σχολίων. |

**Επιστρέφει:**
com.aspose.slides.IComment[] - Array of [Comment](../../com.aspose.slides/comment).
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

Συνδέει τα runs με την ίδια μορφοποίηση σε όλες τις παραγράφους σε όλα τα αποδεκτά σχήματα.