---
title: ZoomObject
second_title: Aspose.Slides για Java API Αναφορά
description: Αντιπροσωπεύει ένα αντικείμενο Zoom σε μια διαφάνεια.
type: docs
url: /el/com.aspose.slides/zoomobject/
---
**Κληρονομία:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public class ZoomObject extends GraphicalObject implements IZoomObject
```

Αντιπροσωπεύει ένα αντικείμενο Zoom σε μια διαφάνεια.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getImageType()](#getImageType--) | Αποκτά ή ορίζει τον τύπο εικόνας ενός αντικειμένου Zoom. |
| [setImageType(int value)](#setImageType-int-) | Αποκτά ή ορίζει τον τύπο εικόνας ενός αντικειμένου Zoom. |
| [getReturnToParent()](#getReturnToParent--) | Αποκτά ή ορίζει τη συμπεριφορά πλοήγησης στη παρουσίαση. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | Αποκτά ή ορίζει τη συμπεριφορά πλοήγησης στη παρουσίαση. |
| [getShowBackground()](#getShowBackground--) | Αποκτά ή ορίζει την τιμή που καθορίζει εάν το Zoom θα χρησιμοποιήσει το φόντο της διαφάνειας προορισμού. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | Αποκτά ή ορίζει την τιμή που καθορίζει εάν το Zoom θα χρησιμοποιήσει το φόντο της διαφάνειας προορισμού. |
| [getZoomImage()](#getZoomImage--) | Αποκτά ή ορίζει την εικόνα για το αντικείμενο Zoom. |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | Αποκτά ή ορίζει την εικόνα για το αντικείμενο Zoom. |
| [getTransitionDuration()](#getTransitionDuration--) | Αποκτά ή ορίζει τη διάρκεια της μετάβασης μεταξύ Zoom και διαφάνειας. |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | Αποκτά ή ορίζει τη διάρκεια της μετάβασης μεταξύ Zoom και διαφάνειας. |

### getImageType() {#getImageType--}
```
public final int getImageType()
```

Αποκτά ή ορίζει τον τύπο εικόνας ενός αντικειμένου Zoom. Ανάγνωση/εγγραφή [ZoomImageType](../../com.aspose.slides/zoomimagetype). Προεπιλεγμένη τιμή: Preview

--------------------

> ```
> Next example demonstrates changing Image Type to Preview value. 
>  In this case current image of a Zoom object changes to slide image:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>      zoomFrame.setImageType(ZoomImageType.Preview);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Καθορίζει εάν το αντικείμενο Zoom χρησιμοποιεί την προεπισκόπηση της διαφάνειας ή μια εικόνα εξωφύλλου.

**Επιστρέφει:**
int

### setImageType(int value) {#setImageType-int-}
```
public final void setImageType(int value)
```

Αποκτά ή ορίζει τον τύπο εικόνας ενός αντικειμένου Zoom. Ανάγνωση/εγγραφή [ZoomImageType](../../com.aspose.slides/zoomimagetype). Προεπιλεγμένη τιμή: Preview

--------------------

> ```
> Next example demonstrates changing Image Type to Preview value. 
>  In this case current image of a Zoom object changes to slide image:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>      zoomFrame.setImageType(ZoomImageType.Preview);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Καθορίζει εάν το αντικείμενο Zoom χρησιμοποιεί την προεπισκόπηση της διαφάνειας ή μια εικόνα εξωφύλλου.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getReturnToParent() {#getReturnToParent--}
```
public final boolean getReturnToParent()
```

Αποκτά ή ορίζει τη συμπεριφορά πλοήγησης στη παρουσίαση. Ανάγνωση/εγγραφή boolean. Προεπιλεγμένη τιμή: false

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setReturnToParent(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Η αληθής τιμή της ιδιότητας καθορίζει τη συμπεριφορά πλοήγησης επιστροφής στο γονέα στη παρουσίαση.

**Επιστρέφει:**
boolean

### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public final void setReturnToParent(boolean value)
```

Αποκτά ή ορίζει τη συμπεριφορά πλοήγησης στη παρουσίαση. Ανάγνωση/εγγραφή boolean. Προεπιλεγμένη τιμή: false

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setReturnToParent(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Η αληθής τιμή της ιδιότητας καθορίζει τη συμπεριφορά πλοήγησης επιστροφής στο γονέα στη παρουσίαση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getShowBackground() {#getShowBackground--}
```
public final boolean getShowBackground()
```

Αποκτά ή ορίζει την τιμή που καθορίζει εάν το Zoom θα χρησιμοποιήσει το φόντο της διαφάνειας προορισμού. Ανάγνωση/εγγραφή boolean. Προεπιλεγμένη τιμή: true

--------------------

> ```
> the example demonstrates removing the background of an image of a Zoom object:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
boolean

### setShowBackground(boolean value) {#setShowBackground-boolean-}
```
public final void setShowBackground(boolean value)
```

Αποκτά ή ορίζει την τιμή που καθορίζει εάν το Zoom θα χρησιμοποιήσει το φόντο της διαφάνειας προορισμού. Ανάγνωση/εγγραφή boolean. Προεπιλεγμένη τιμή: true

--------------------

> ```
> the example demonstrates removing the background of an image of a Zoom object:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getZoomImage() {#getZoomImage--}
```
public final IPPImage getZoomImage()
```

Αποκτά ή ορίζει την εικόνα για το αντικείμενο Zoom. Ανάγνωση/εγγραφή [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> the example demonstrates changing an image of a Zoom object:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      zoomFrame.setImage(image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
[IPPImage](../../com.aspose.slides/ippimage)

### setZoomImage(IPPImage value) {#setZoomImage-com.aspose.slides.IPPImage-}
```
public final void setZoomImage(IPPImage value)
```

Αποκτά ή ορίζει την εικόνα για το αντικείμενο Zoom. Ανάγνωση/εγγραφή [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> το παράδειγμα δείχνει την αλλαγή μιας εικόνας ενός αντικειμένου Zoom:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      zoomFrame.setImage(image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getTransitionDuration() {#getTransitionDuration--}
```
public final float getTransitionDuration()
```

Αποκτά ή ορίζει τη διάρκεια της μετάβασης μεταξύ Zoom και διαφάνειας. Ανάγνωση/εγγραφή float. Προεπιλεγμένη τιμή: 1.0f

--------------------

> ```
> the example demonstrates changing the duration of the transition between Zoom and slide:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setTransitionDuration(2.5f);
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

Εάν δεν καθοριστεί (TransitionDur = 0), θα χρησιμοποιηθεί η μετάβαση της διαφάνειας προορισμού και οι χρονισμοί που σχετίζονται με αυτή τη μετάβαση.

**Επιστρέφει:**
float

### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public final void setTransitionDuration(float value)
```

Αποκτά ή ορίζει τη διάρκεια της μετάβασης μεταξύ Zoom και διαφάνειας. Ανάγνωση/εγγραφή float. Προεπιλεγμένη τιμή: 1.0f

--------------------

> ```
> το παράδειγμα δείχνει την αλλαγή της διάρκειας της μετάβασης μεταξύ Zoom και διαφάνειας:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setTransitionDuration(2.5f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

Εάν δεν καθοριστεί (TransitionDur = 0), θα χρησιμοποιηθεί η μετάβαση της διαφάνειας προορισμού και οι χρονισμοί που σχετίζονται με αυτή τη μετάβαση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |