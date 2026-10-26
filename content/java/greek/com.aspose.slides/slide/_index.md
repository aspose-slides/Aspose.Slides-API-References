---
title: Slide
second_title: Aspose.Slides για Java API Αναφορά
description: Αντιπροσωπεύει μια διαφάνεια σε μια παρουσίαση.
type: docs
url: /el/com.aspose.slides/slide/
---
**Κληρονομία:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ISlide](../../com.aspose.slides/islide)
```
public final class Slide extends BaseSlide implements ISlide
```

Αποτελεί μια διαφάνεια σε μια παρουσίαση.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Επιστρέφει τον διαχειριστή HeaderFooter της διαφάνειας. |
| [getThemeManager()](#getThemeManager--) | Επιστρέφει τον υπερκαθορισμένο διαχειριστή θέματος. |
| [getSlideNumber()](#getSlideNumber--) | Επιστρέφει έναν αριθμό διαφάνειας. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | Επιστρέφει έναν αριθμό διαφάνειας. |
| [getHidden()](#getHidden--) | Καθορίζει αν η συγκεκριμένη διαφάνεια είναι κρυφή κατά τη διάρκεια της παρουσίασης. |
| [setHidden(boolean value)](#setHidden-boolean-) | Καθορίζει αν η συγκεκριμένη διαφάνεια είναι κρυφή κατά τη διάρκεια της παρουσίασης. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Καθορίζει εάν τα σχήματα στην κύρια διαφάνεια πρέπει να εμφανίζονται στις διαφάνειες ή όχι. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Καθορίζει εάν τα σχήματα στην κύρια διαφάνεια πρέπει να εμφανίζονται στις διαφάνειες ή όχι. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Επιστρέφει ένα αντικείμενο Thumbnail Image με προσαρμοσμένη κλιμάκωση. |
| [getImage()](#getImage--) | Επιστρέφει ένα αντικείμενο Thumbnail Image (20% του πραγματικού μεγέθους). |
| [getImage(Dimension imageSize)](#getImage-java.awt.Dimension-) | Επιστρέφει ένα αντικείμενο Thumbnail Image με καθορισμένο μέγεθος. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | Επιστρέφει ένα αντικείμενο Thumbnail tiff image με καθορισμένες παραμέτρους. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | Επιστρέφει ένα αντικείμενο Thumbnail Image. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | Επιστρέφει ένα αντικείμενο Thumbnail Image με προσαρμοσμένη κλιμάκωση. |
| [getImage(IRenderingOptions options, Dimension imageSize)](#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Επιστρέφει ένα αντικείμενο Thumbnail Image με καθορισμένο μέγεθος. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Αποθηκεύει το περιεχόμενο της διαφάνειας ως αρχείο SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Αποθηκεύει το περιεχόμενο της διαφάνειας ως αρχείο SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Αποθηκεύει το περιεχόμενο της διαφάνειας ως αρχείο EMF. |
| [remove()](#remove--) | Αφαιρεί τη διαφάνεια από την παρουσίαση. |
| [getLayoutSlide()](#getLayoutSlide--) | Επιστρέφει ή ορίζει τη διαφάνεια διάταξης για την τρέχουσα διαφάνεια. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | Επιστρέφει ή ορίζει τη διαφάνεια διάταξης για την τρέχουσα διαφάνεια. |
| [reset()](#reset--) | Επαναφέρει τη θέση, το μέγεθος και τη μορφοποίηση κάθε σχήματος που έχει πρωτότυπο στην LayoutSlide. |
| [getNotesSlideManager()](#getNotesSlideManager--) | Επιτρέπει την πρόσβαση στη διαφάνεια σημειώσεων, την προσθήκη και την αφαίρεσή της. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | Επιστρέφει όλα τα σχόλια διαφάνειας που προστέθηκαν από συγκεκριμένο συγγραφέα. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Ενώνει τα runs με την ίδια μορφοποίηση σε όλες τις παραγράφους σε όλα τα αποδεκτά σχήματα. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ISlideHeaderFooterManager getHeaderFooterManager()
```

Επιστρέφει τον διαχειριστή HeaderFooter της διαφάνειας. Μόνο προς ανάγνωση [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**Επιστρέφει:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Επιστρέφει τον υπερκαθορισμένο διαχειριστή θέματος. Μόνο προς ανάγνωση [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Επιστρέφει:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```

Επιστρέφει έναν αριθμό διαφάνειας. Ο δείκτης της διαφάνειας στη συλλογή [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) είναι πάντα ίσος με SlideNumber - Presentation.FirstSlideNumber. Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```

Επιστρέφει έναν αριθμό διαφάνειας. Ο δείκτης της διαφάνειας στη συλλογή [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) είναι πάντα ίσος με SlideNumber - Presentation.FirstSlideNumber. Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

Καθορίζει αν η συγκεκριμένη διαφάνεια είναι κρυφή κατά τη διάρκεια της παρουσίασης. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

Καθορίζει αν η συγκεκριμένη διαφάνεια είναι κρυφή κατά τη διάρκεια της παρουσίασης. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Καθορίζει εάν τα σχήματα στην κύρια διαφάνεια πρέπει να εμφανίζονται στις διαφάνειες ή όχι. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Καθορίζει εάν τα σχήματα στην κύρια διαφάνεια πρέπει να εμφανίζονται στις διαφάνειες ή όχι. Ανάγνωση/εγγραφή boolean.

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
>      // Access the first slide
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Create a full scale image
>      IImage bmp = sld.getImage(1f, 1f);
>      // Save the image to disk in JPEG format
>      bmp.save("Thumbnail_out.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to converting slides to bitmap and saving the images in PNG.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // Converts the first slide in the presentation to a Bitmap object
>      IImage bmp = pres.getSlides().get_Item(0).getImage();
>      // Saves the image in the PNG format
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
>          // Create a full scale image
>          IImage bmp = sld.getImage(1f, 1f);
>          // Save the image to disk in JPEG format
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
>      // Define dimensions
>      int desiredX = 1200;
>      int desiredY = 800;
>      // Get scaled values of X and Y
>      float ScaleX = (float)(1.0 / pres.getSlideSize().getSize().getWidth()) * desiredX;
>      float ScaleY = (float)(1.0 / pres.getSlideSize().getSize().getHeight()) * desiredY;
>      for (ISlide sld : pres.getSlides())
>      {
>          // Create a full scale image
>          IImage bmp = sld.getImage(ScaleX, ScaleY);
>          // Save the image to disk in JPEG format
>          bmp.save("Slide.jpg", ImageFormat.Jpeg);
>      }
>  } finally {
>      pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| scaleX | float | Η τιμή με την οποία κλιμακώνεται αυτό το Thumbnail στον άξονα x. |
| scaleY | float | Η τιμή με την οποία κλιμακώνεται αυτό το Thumbnail στον άξονα y. |

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage) - αντικείμενο IImage.
### getImage() {#getImage--}
```
public final IImage getImage()
```

Επιστρέφει ένα αντικείμενο Thumbnail Image (20% του πραγματικού μεγέθους).

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage)
### getImage(Dimension imageSize) {#getImage-java.awt.Dimension-}
```
public final IImage getImage(Dimension imageSize)
```

Επιστρέφει ένα αντικείμενο Thumbnail Image με καθορισμένο μέγεθος.

--------------------

> ```
> The following example shows how to converting slides to images with custom sizes using C#.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // Μετατρέπει την πρώτη διαφάνεια στην παρουσίαση σε ένα Bitmap με το καθορισμένο μέγεθος
>      IImage bmp = pres.getSlides().get_Item(0).getImage(new Dimension(1820, 1040));
>      // Αποθηκεύει την εικόνα σε μορφή JPEG
>      bmp.save("Slide_0.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| imageSize | java.awt.Dimension | Μέγεθος της εικόνας που θα δημιουργηθεί. |

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage) - αντικείμενο Image.
### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public final IImage getImage(ITiffOptions options)
```

Επιστρέφει ένα αντικείμενο Thumbnail tiff image με καθορισμένες παραμέτρους.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Επιλογές Tiff. |

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage) - αντικείμενο Image.
### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public final IImage getImage(IRenderingOptions options)
```

Επιστρέφει ένα αντικείμενο Thumbnail Image.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Επιλογές απόδοσης. |

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage) - αντικείμενο Image.
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
>      // Ορίστε επιλογές διάταξης για την απόδοση
>      options.setSlidesLayoutOptions(notesCommentsLayouting);
>      // Μετατρέπει την πρώτη διαφάνεια της παρουσίασης σε αντικείμενο BufferedImage
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
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Επιλογές απόδοσης. |
| scaleX | float | Η τιμή με την οποία κλιμακώνεται αυτό το Thumbnail στον άξονα x. |
| scaleY | float | Η τιμή με την οποία κλιμακώνεται αυτό το Thumbnail στον άξονα y. |

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage) - αντικείμενα Bitmap.
### getImage(IRenderingOptions options, Dimension imageSize) {#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public final IImage getImage(IRenderingOptions options, Dimension imageSize)
```

Επιστρέφει ένα αντικείμενο Thumbnail Image με καθορισμένο μέγεθος.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Επιλογές απόδοσης. |
| imageSize | java.awt.Dimension | Μέγεθος της εικόνας που θα δημιουργηθεί. |

**Επιστρέφει:**
[IImage](../../com.aspose.slides/iimage) - αντικείμενο Image.
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
| stream | java.io.OutputStream | Ροή προορισμού |
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
| stream | java.io.OutputStream | Ροή προορισμού |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Επιλογές δημιουργίας SVG |
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
| stream | java.io.OutputStream | Ροή προορισμού |
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

Επαναφέρει τη θέση, το μέγεθος και τη μορφοποίηση κάθε σχήματος που έχει πρωτότυπο στην LayoutSlide.
### getNotesSlideManager() {#getNotesSlideManager--}
```
public final INotesSlideManager getNotesSlideManager()
```

Επιτρέπει την πρόσβαση στη διαφάνεια σημειώσεων, την προσθήκη και την αφαίρεσή της. Μόνο προς ανάγνωση [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

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
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Συγγραφέας των σχολίων προς αναζήτηση ή null για επιστροφή όλων των σχολίων. |

**Επιστρέφει:**
com.aspose.slides.IComment[] - Πίνακας [Comment](../../com.aspose.slides/comment).
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

Ενώνει τα runs με την ίδια μορφοποίηση σε όλες τις παραγράφους σε όλα τα αποδεκτά σχήματα.