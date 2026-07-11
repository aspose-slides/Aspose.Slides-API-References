---
title: IZoomObject
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αντιπροσωπεύει ένα αντικείμενο Zoom σε μια διαφάνεια.
type: docs
url: /el/com.aspose.slides/izoomobject/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IZoomObject extends IGraphicalObject
```

Αναπαριστά ένα αντικείμενο Zoom σε μια διαφάνεια.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getImageType()](#getImageType--) | Αποκτά ή ορίζει τον τύπο εικόνας ενός αντικειμένου Zoom. |
| [setImageType(int value)](#setImageType-int-) | Αποκτά ή ορίζει τον τύπο εικόνας ενός αντικειμένου Zoom. |
| [getReturnToParent()](#getReturnToParent--) | Αποκτά ή ορίζει τη συμπεριφορά πλοήγησης στην παρουσίαση. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | Αποκτά ή ορίζει τη συμπεριφορά πλοήγησης στην παρουσίαση. |
| [getShowBackground()](#getShowBackground--) | Αποκτά ή ορίζει τιμή που καθορίζει εάν το Zoom θα χρησιμοποιήσει το φόντο της διαφάνειας προορισμού. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | Αποκτά ή ορίζει τιμή που καθορίζει εάν το Zoom θα χρησιμοποιήσει το φόντο της διαφάνειας προορισμού. |
| [getZoomImage()](#getZoomImage--) | Αποκτά ή ορίζει εικόνα για το αντικείμενο Zoom. |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | Αποκτά ή ορίζει εικόνα για το αντικείμενο Zoom. |
| [getTransitionDuration()](#getTransitionDuration--) | Αποκτά ή ορίζει τη διάρκεια της μετάβασης μεταξύ Zoom και διαφάνειας. |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | Αποκτά ή ορίζει τη διάρκεια της μετάβασης μεταξύ Zoom και διαφάνειας. |
### getImageType() {#getImageType--}
```
public abstract int getImageType()
```

Αποκτά ή ορίζει τον τύπο εικόνας ενός αντικειμένου Zoom. Ανάγνωση/εγγραφή [ZoomImageType](../../com.aspose.slides/zoomimagetype). Προεπιλεγμένη τιμή: Preview

--------------------

> ```
> This example demonstrates changing Image Type to Preview value. 
>  In this case the current image of a Zoom object changes to slide image:
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

Καθορίζει αν το αντικείμενο Zoom χρησιμοποιεί την προεπισκόπηση διαφάνειας ή μια εικόνα εξώφυλλου.

**Επιστρέφει:**
int
### setImageType(int value) {#setImageType-int-}
```
public abstract void setImageType(int value)
```

Αποκτά ή ορίζει τον τύπο εικόνας ενός αντικειμένου Zoom. Ανάγνωση/εγγραφή [ZoomImageType](../../com.aspose.slides/zoomimagetype). Προεπιλεγμένη τιμή: Preview

--------------------

> ```
> This example demonstrates changing Image Type to Preview value. 
>  In this case the current image of a Zoom object changes to slide image:
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

Καθορίζει αν το αντικείμενο Zoom χρησιμοποιεί την προεπισκόπηση διαφάνειας ή μια εικόνα εξώφυλλου.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getReturnToParent() {#getReturnToParent--}
```
public abstract boolean getReturnToParent()
```

Αποκτά ή ορίζει τη συμπεριφορά πλοήγησης στην παρουσίαση. Ανάγνωση/εγγραφή boolean. Προεπιλεγμένη τιμή: false

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

Η τιμή true της ιδιότητας καθορίζει τη συμπεριφορά επιστροφής στον γονέα κατά την πλοήγηση στην παρουσίαση.

**Επιστρέφει:**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public abstract void setReturnToParent(boolean value)
```

Αποκτά ή ορίζει τη συμπεριφορά πλοήγησης στην παρουσίαση. Ανάγνωση/εγγραφή boolean. Προεπιλεγμένη τιμή: false

--------------------

> ```
> Παράδειγμα:
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

Η τιμή true της ιδιότητας καθορίζει τη συμπεριφορά επιστροφής στον γονέα κατά την πλοήγηση στην παρουσίαση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getShowBackground() {#getShowBackground--}
```
public abstract boolean getShowBackground()
```

Αποκτά ή ορίζει τιμή που καθορίζει εάν το Zoom θα χρησιμοποιήσει το φόντο της διαφάνειας προορισμού. Ανάγνωση/εγγραφή boolean. Προεπιλεγμένη τιμή: true

--------------------

> ```
> The example demonstrates removing the background of an image of a Zoom object:
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
public abstract void setShowBackground(boolean value)
```

Αποκτά ή ορίζει τιμή που καθορίζει εάν το Zoom θα χρησιμοποιήσει το φόντο της διαφάνειας προορισμού. Ανάγνωση/εγγραφή boolean. Προεπιλεγμένη τιμή: true

--------------------

> ```
> Το παράδειγμα δείχνει την αφαίρεση του φόντου μιας εικόνας ενός αντικειμένου Zoom:
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
public abstract IPPImage getZoomImage()
```

Αποκτά ή ορίζει εικόνα για το αντικείμενο Zoom. Ανάγνωση/εγγραφή [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> Το παράδειγμα δείχνει την αλλαγή μιας εικόνας ενός αντικειμένου Zoom:
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
public abstract void setZoomImage(IPPImage value)
```

Αποκτά ή ορίζει εικόνα για το αντικείμενο Zoom. Ανάγνωση/εγγραφή [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> Το παράδειγμα δείχνει την αλλαγή μιας εικόνας ενός αντικειμένου Zoom:
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
public abstract float getTransitionDuration()
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

--------------------

Εάν δεν καθοριστεί (TransitionDur = 0), θα χρησιμοποιήσει τη μετάβαση της διαφάνειας προορισμού και τα χρονικά στοιχεία που σχετίζονται με αυτήν τη μετάβαση.

**Επιστρέφει:**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public abstract void setTransitionDuration(float value)
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

--------------------

Εάν δεν καθοριστεί (TransitionDur = 0), θα χρησιμοποιήσει τη μετάβαση της διαφάνειας προορισμού και τα χρονικά στοιχεία που σχετίζονται με αυτήν τη μετάβαση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |