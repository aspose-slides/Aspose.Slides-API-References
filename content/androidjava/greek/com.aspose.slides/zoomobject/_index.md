---
title: ZoomObject
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αναπαριστά ένα αντικείμενο Zoom σε μια διαφάνεια.
type: docs
url: /el/com.aspose.slides/zoomobject/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public class ZoomObject extends GraphicalObject implements IZoomObject
```

Αναπαριστά ένα αντικείμενο Zoom σε μια διαφάνεια.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getImageType()](#getImageType--) | Gets or sets the image type of a zoom object. |
| [setImageType(int value)](#setImageType-int-) | Gets or sets the image type of a zoom object. |
| [getReturnToParent()](#getReturnToParent--) | Gets or sets the navigation behavior in slideshow. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | Gets or sets the navigation behavior in slideshow. |
| [getShowBackground()](#getShowBackground--) | Gets or sets value that specifies whether the Zoom will use the background of the destination slide. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | Gets or sets value that specifies whether the Zoom will use the background of the destination slide. |
| [getZoomImage()](#getZoomImage--) | Gets or sets image for zoom object. |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | Gets or sets image for zoom object. |
| [getTransitionDuration()](#getTransitionDuration--) | Gets or sets the duration of the transition between Zoom and slide. |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | Gets or sets the duration of the transition between Zoom and slide. |
### getImageType() {#getImageType--}
```
public final int getImageType()
```

Λαμβάνει ή ορίζει τον τύπο εικόνας ενός αντικειμένου Zoom. Ανάγνωση/εγγραφή [ZoomImageType](../../com.aspose.slides/zoomimagetype). Προεπιλεγμένη τιμή: Preview

--------------------

> ```
> Next example demonstrates changing Image Type to Preview value. 
>  In this case current image of a Zoom object changes to slide image:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>          zoomFrame.setImageType(ZoomImageType.Preview);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Καθορίζει αν το αντικείμενο Zoom χρησιμοποιεί την προεπισκόπηση της διαφάνειας ή μια εικόνα εξώφυλλου.

**Επιστρέφει:**
int
### setImageType(int value) {#setImageType-int-}
```
public final void setImageType(int value)
```

Λαμβάνει ή ορίζει τον τύπο εικόνας ενός αντικειμένου Zoom. Ανάγνωση/εγγραφή [ZoomImageType](../../com.aspose.slides/zoomimagetype). Προεπιλεγμένη τιμή: Preview

--------------------

> ```
> Next example demonstrates changing Image Type to Preview value. 
>  In this case current image of a Zoom object changes to slide image:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>          zoomFrame.setImageType(ZoomImageType.Preview);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Καθορίζει αν το αντικείμενο Zoom χρησιμοποιεί την προεπισκόπηση της διαφάνειας ή μια εικόνα εξώφυλλου.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getReturnToParent() {#getReturnToParent--}
```
public final boolean getReturnToParent()
```

Λαμβάνει ή ορίζει τη συμπεριφορά πλοήγησης στη παρουσίαση. Ανάγνωση/εγγραφή boolean. Προεπιλεγμένη τιμή: false

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

Η αληθής τιμή της ιδιότητας καθορίζει τη συμπεριφορά επιστροφής στον γονέα στη παρουσίαση.

**Επιστρέφει:**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public final void setReturnToParent(boolean value)
```

Λαμβάνει ή ορίζει τη συμπεριφορά πλοήγησης στη παρουσίαση. Ανάγνωση/εγγραφή boolean. Προεπιλεγμένη τιμή: false

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

Η αληθής τιμή της ιδιότητας καθορίζει τη συμπεριφορά επιστροφής στον γονέα στη παρουσίαση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getShowBackground() {#getShowBackground--}
```
public final boolean getShowBackground()
```

Λαμβάνει ή ορίζει τιμή που καθορίζει αν το Zoom θα χρησιμοποιήσει το παρασκήνιο της διαφάνειας προορισμού. Ανάγνωση/εγγραφή boolean. Προεπιλεγμένη τιμή: true

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

Λαμβάνει ή ορίζει τιμή που καθορίζει αν το Zoom θα χρησιμοποιήσει το παρασκήνιο της διαφάνειας προορισμού. Ανάγνωση/εγγραφή boolean. Προεπιλεγμένη τιμή: true

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

Λαμβάνει ή ορίζει την εικόνα για το αντικείμενο Zoom. Ανάγνωση/εγγραφή [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> the example demonstrates changing an image of a Zoom object:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          zoomFrame.setImage(image);
>      } finally {
>          if (fos != null) fos.close();
>      }
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

Λαμβάνει ή ορίζει την εικόνα για το αντικείμενο Zoom. Ανάγνωση/εγγραφή [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> the example demonstrates changing an image of a Zoom object:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          zoomFrame.setImage(image);
>      } finally {
>          if (fos != null) fos.close();
>      }
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

Λαμβάνει ή ορίζει τη διάρκεια της μετάβασης μεταξύ Zoom και διαφάνειας. Ανάγνωση/εγγραφή float. Προεπιλεγμένη τιμή: 1.0f

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


--------------------

Αν δεν καθοριστεί (TransitionDur = 0), θα χρησιμοποιηθεί η μετάβαση της διαφάνειας προορισμού και τα χρονικά σημεία που σχετίζονται με αυτή τη μετάβαση.

**Επιστρέφει:**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public final void setTransitionDuration(float value)
```

Λαμβάνει ή ορίζει τη διάρκεια της μετάβασης μεταξύ Zoom και διαφάνειας. Ανάγνωση/εγγραφή float. Προεπιλεγμένη τιμή: 1.0f

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

--------------------

Αν δεν καθοριστεί (TransitionDur = 0), θα χρησιμοποιηθεί η μετάβαση της διαφάνειας προορισμού και τα χρονικά σημεία που σχετίζονται με αυτή τη μετάβαση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |