---
title: IZoomObject
second_title: Aspose.Slides για την Java API Αναφορά
description: Αντιπροσωπεύει ένα αντικείμενο Zoom σε μια διαφάνεια.
type: docs
url: /el/com.aspose.slides/izoomobject/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IZoomObject extends IGraphicalObject
```

Αντιπροσωπεί ένα αντικείμενο Zoom σε μια διαφάνεια.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getImageType()](#getImageType--) | Λαμβάνει ή ορίζει τον τύπο εικόνας ενός αντικειμένου Zoom. |
| [setImageType(int value)](#setImageType-int-) | Λαμβάνει ή ορίζει τον τύπο εικόνας ενός αντικειμένου Zoom. |
| [getReturnToParent()](#getReturnToParent--) | Λαμβάνει ή ορίζει τη συμπεριφορά πλοήγησης στην παρουσίαση. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | Λαμβάνει ή ορίζει τη συμπεριφορά πλοήγησης στην παρουσίαση. |
| [getShowBackground()](#getShowBackground--) | Λαμβάνει ή ορίζει τιμή που καθορίζει εάν το Zoom θα χρησιμοποιήσει το φόντο της διαφάνειας-προορισμού. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | Λαμβάνει ή ορίζει τιμή που καθορίζει εάν το Zoom θα χρησιμοποιήσει το φόντο της διαφάνειας-προορισμού. |
| [getZoomImage()](#getZoomImage--) | Λαμβάνει ή ορίζει την εικόνα για το αντικείμενο Zoom. |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | Λαμβάνει ή ορίζει την εικόνα για το αντικείμενο Zoom. |
| [getTransitionDuration()](#getTransitionDuration--) | Λαμβάνει ή ορίζει τη διάρκεια της μετάβασης μεταξύ Zoom και διαφάνειας. |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | Λαμβάνει ή ορίζει τη διάρκεια της μετάβασης μεταξύ Zoom και διαφάνειας. |

### getImageType() {#getImageType--}
```
public abstract int getImageType()
```

Λαμβάνει ή ορίζει τον τύπο εικόνας ενός αντικειμένου Zoom. Ανάγνωση/εγγραφή [ZoomImageType](../../com.aspose.slides/zoomimagetype). Προεπιλεγμένη τιμή: Preview

--------------------

> ```
> This example demonstrates changing Image Type to Preview value. 
>  In this case the current image of a Zoom object changes to slide image:
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
public abstract void setImageType(int value)
```

Λαμβάνει ή ορίζει τον τύπο εικόνας ενός αντικειμένου Zoom. Ανάγνωση/εγγραφή [ZoomImageType](../../com.aspose.slides/zoomimagetype). Προεπιλεγμένη τιμή: Preview

--------------------

> ```
> This example demonstrates changing Image Type to Preview value. 
>  In this case the current image of a Zoom object changes to slide image:
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getReturnToParent() {#getReturnToParent--}
```
public abstract boolean getReturnToParent()
```

Λαμβάνει ή ορίζει τη συμπεριφορά πλοήγησης στην παρουσίαση. Ανάγνωση/εγγραφή boolean. Προεπιλεγμένη τιμή: false

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

Η αληθής τιμή της ιδιότητας υποδεικνύει επιστροφή στη γονική συμπεριφορά πλοήγησης στην παρουσίαση.

**Επιστρέφει:**
boolean

### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public abstract void setReturnToParent(boolean value)
```

Λαμβάνει ή ορίζει τη συμπεριφορά πλοήγησης στην παρουσίαση. Ανάγνωση/εγγραφή boolean. Προεπιλεγμένη τιμή: false

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

Η αληθής τιμή της ιδιότητας υποδεικνύει επιστροφή στη γονική συμπεριφορά πλοήγησης στην παρουσίαση.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowBackground() {#getShowBackground--}
```
public abstract boolean getShowBackground()
```

Λαμβάνει ή ορίζει τιμή που καθορίζει εάν το Zoom θα χρησιμοποιήσει το φόντο της διαφάνειας-προορισμού. Ανάγνωση/εγγραφή boolean. Προεπιλεγμένη τιμή: true

--------------------

> ```
> Το παράδειγμα δείχνει την αφαίρεση του φόντου της εικόνας ενός αντικειμένου Zoom:
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

Λαμβάνει ή ορίζει τιμή που καθορίζει εάν το Zoom θα χρησιμοποιήσει το φόντο της διαφάνειας-προορισμού. Ανάγνωση/εγγραφή boolean. Προεπιλεγμένη τιμή: true

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getZoomImage() {#getZoomImage--}
```
public abstract IPPImage getZoomImage()
```

Λαμβάνει ή ορίζει την εικόνα για το αντικείμενο Zoom. Ανάγνωση/εγγραφή [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> Το παράδειγμα δείχνει την αλλαγή εικόνας ενός αντικειμένου Zoom:
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
public abstract void setZoomImage(IPPImage value)
```

Λαμβάνει ή ορίζει την εικόνα για το αντικείμενο Zoom. Ανάγνωση/εγγραφή [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> Το παράδειγμα δείχνει την αλλαγή μιας εικόνας ενός αντικειμένου Zoom:
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getTransitionDuration() {#getTransitionDuration--}
```
public abstract float getTransitionDuration()
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

Εάν δεν καθοριστεί (TransitionDur = 0), θα χρησιμοποιηθεί η μετάβαση της διαφάνειας-προορισμού και οι χρονισμοί που σχετίζονται με αυτήν.

**Επιστρέφει:**
float

### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public abstract void setTransitionDuration(float value)
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

Εάν δεν καθοριστεί (TransitionDur = 0), θα χρησιμοποιηθεί η μετάβαση της διαφάνειας-προορισμού και οι χρονισμοί που σχετίζονται με αυτήν.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |