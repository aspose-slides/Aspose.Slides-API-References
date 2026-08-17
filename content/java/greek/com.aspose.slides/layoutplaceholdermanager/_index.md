---
title: LayoutPlaceholderManager
second_title: Αναφορά API Aspose.Slides για Java
description: Αναπαριστά διαχειριστή που επιτρέπει την προσθήκη συμβόλων κράτησης στη διαφάνεια διάταξης.
type: docs
url: /el/com.aspose.slides/layoutplaceholdermanager/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
```
public class LayoutPlaceholderManager implements ILayoutPlaceholderManager
```

Αναπαριστά διαχειριστή που επιτρέπει την προσθήκη συμβόλων κράτησης στην διαφάνεια διάταξης.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | Προσθέτει νέο σχήμα placeholder στη διαφάνεια διάταξης για την αποθήκευση περιεχομένου, όπως εικόνα, πίνακα, πολυμέσων ή κείμενο. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | Προσθέτει νέο σχήμα placeholder στη διαφάνεια διάταξης για την αποθήκευση περιεχομένου, όπως εικόνα, πίνακα, πολυμέσων ή κείμενο σε κατακόρυφη κατεύθυνση. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | Προσθέτει νέο σχήμα placeholder στη διαφάνεια διάταξης για την αποθήκευση κειμένου. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | Προσθέτει νέο σχήμα placeholder στη διαφάνεια διάταξης για την αποθήκευση κειμένου σε κατακόρυφη κατεύθυνση. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | Προσθέτει νέο σχήμα placeholder στη διαφάνεια διάταξης για την αποθήκευση μιας εικόνας. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | Προσθέτει νέο σχήμα placeholder στη διαφάνεια διάταξης για την αποθήκευση ενός διαγράμματος. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | Προσθέτει νέο σχήμα placeholder στη διαφάνεια διάταξης για την αποθήκευση ενός πίνακα. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | Προσθέτει νέο σχήμα placeholder στη διαφάνεια διάταξης για την αποθήκευση διαγράμματος SmartArt. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | Προσθέτει νέο σχήμα placeholder στη διαφάνεια διάταξης για την αποθήκευση αντικειμένου πολυμέσων. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | Προσθέτει νέο σχήμα placeholder στη διαφάνεια διάταξης για την αποθήκευση μιας online εικόνας. |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```


Προσθέτει νέο σχήμα placeholder στη διαφάνεια διάταξης για την αποθήκευση περιεχομένου, όπως εικόνα, πίνακα, πολυμέσων ή κείμενο.

--------------------

> ```
> The following example shows how to add the Content placeholder shape to the layout slide.
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addContentPlaceholder(20, 20, 500, 300);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η συντεταγμένη X του νέου σχήματος placeholder. |
| y | float | Η συντεταγμένη Y του νέου σχήματος placeholder. |
| width | float | Το πλάτος του νέου σχήματος placeholder. |
| height | float | Το ύψος του νέου σχήματος placeholder. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Δημιουργήθηκε [IAutoShape](../../com.aspose.slides/iautoshape) με ένα σύμβολο κράτησης Περιεχομένου.
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```


Προσθέτει νέο σχήμα placeholder στη διαφάνεια διάταξης για την αποθήκευση περιεχομένου, όπως εικόνα, πίνακα, πολυμέσων ή κείμενο σε κατακόρυφη κατεύθυνση.

--------------------

> ```
> The following example shows how to add the Content (Vertical) placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addVerticalContentPlaceholder(20, 20, 300, 500);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η συντεταγμένη X του νέου σχήματος placeholder. |
| y | float | Η συντεταγμένη Y του νέου σχήματος placeholder. |
| width | float | Το πλάτος του νέου σχήματος placeholder. |
| height | float | Το ύψος του νέου σχήματος placeholder. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Δημιουργήθηκε [IAutoShape](../../com.aspose.slides/iautoshape) με ένα σύμβολο κράτησης Περιεχομένου (Κατακόρυφο).
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```


Προσθέτει νέο σχήμα placeholder στη διαφάνεια διάταξης για την αποθήκευση κειμένου.

--------------------

> ```
> The following example shows how to add the Text placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addTextPlaceholder(20, 20, 500, 300);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η συντεταγμένη X του νέου σχήματος placeholder. |
| y | float | Η συντεταγμένη Y του νέου σχήματος placeholder. |
| width | float | Το πλάτος του νέου σχήματος placeholder. |
| height | float | Το ύψος του νέου σχήματος placeholder. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Δημιουργήθηκε [IAutoShape](../../com.aspose.slides/iautoshape) με ένα σύμβολο κράτησης Κειμένου.
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```


Προσθέτει νέο σχήμα placeholder στη διαφάνεια διάταξης για την αποθήκευση κειμένου σε κατακόρυφη κατεύθυνση.

--------------------

> ```
> The following example shows how to add the Text (Vertical) placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addTextPlaceholder(20, 20, 500, 300);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η συντεταγμένη X του νέου σχήματος placeholder. |
| y | float | Η συντεταγμένη Y του νέου σχήματος placeholder. |
| width | float | Το πλάτος του νέου σχήματος placeholder. |
| height | float | Το ύψος του νέου σχήματος placeholder. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Δημιουργήθηκε [IAutoShape](../../com.aspose.slides/iautoshape) με ένα σύμβολο κράτησης Κειμένου (Κατακόρυφο).
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public final IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```


Προσθέτει νέο σχήμα placeholder στη διαφάνεια διάταξης για την αποθήκευση μιας εικόνας.

--------------------

> ```
> The following example shows how to add the Picture placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addPicturePlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η συντεταγμένη X του νέου σχήματος placeholder. |
| y | float | Η συντεταγμένη Y του νέου σχήματος placeholder. |
| width | float | Το πλάτος του νέου σχήματος placeholder. |
| height | float | Το ύψος του νέου σχήματος placeholder. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Δημιουργήθηκε [IAutoShape](../../com.aspose.slides/iautoshape) με ένα σύμβολο κράτησης Εικόνας.
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public final IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```


Προσθέτει νέο σχήμα placeholder στη διαφάνεια διάταξης για την αποθήκευση ενός διαγράμματος.

--------------------

> ```
> Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε το σχήμα placeholder Chart στη διαφάνεια διάταξης.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addChartPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η συντεταγμένη X του νέου σχήματος placeholder. |
| y | float | Η συντεταγμένη Y του νέου σχήματος placeholder. |
| width | float | Το πλάτος του νέου σχήματος placeholder. |
| height | float | Το ύψος του νέου σχήματος placeholder. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Δημιουργήθηκε [IAutoShape](../../com.aspose.slides/iautoshape) με ένα σύμβολο κράτησης Διαγράμματος.
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public final IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```


Προσθέτει νέο σχήμα placeholder στη διαφάνεια διάταξης για την αποθήκευση ενός πίνακα.

--------------------

> ```
> Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε το σχήμα placeholder Table στη διαφάνεια διάταξης.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addTablePlaceholder(20, 20, 500, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η συντεταγμένη X του νέου σχήματος placeholder. |
| y | float | Η συντεταγμένη Y του νέου σχήματος placeholder. |
| width | float | Το πλάτος του νέου σχήματος placeholder. |
| height | float | Το ύψος του νέου σχήματος placeholder. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Δημιουργήθηκε [IAutoShape](../../com.aspose.slides/iautoshape) με ένα σύμβολο κράτησης Πίνακα.
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public final IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```


Προσθέτει νέο σχήμα placeholder στη διαφάνεια διάταξης για την αποθήκευση διαγράμματος SmartArt.

--------------------

> ```
> Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε το σχήμα placeholder SmartArt στη διαφάνεια διάταξης.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addSmartArtPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η συντεταγμένη X του νέου σχήματος placeholder. |
| y | float | Η συντεταγμένη Y του νέου σχήματος placeholder. |
| width | float | Το πλάτος του νέου σχήματος placeholder. |
| height | float | Το ύψος του νέου σχήματος placeholder. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Δημιουργήθηκε [IAutoShape](../../com.aspose.slides/iautoshape) με ένα σύμβολο κράτησης SmartArt.
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public final IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```


Προσθέτει νέο σχήμα placeholder στη διαφάνεια διάταξης για την αποθήκευση αντικειμένου πολυμέσων.

--------------------

> ```
> Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε το σχήμα placeholder Media στη διαφάνεια διάταξης.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addMediaPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η συντεταγμένη X του νέου σχήματος placeholder. |
| y | float | Η συντεταγμένη Y του νέου σχήματος placeholder. |
| width | float | Το πλάτος του νέου σχήματος placeholder. |
| height | float | Το ύψος του νέου σχήματος placeholder. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Δημιουργήθηκε [IAutoShape](../../com.aspose.slides/iautoshape) με ένα σύμβολο κράτησης Πολυμέσων.
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public final IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```


Προσθέτει νέο σχήμα placeholder στη διαφάνεια διάταξης για την αποθήκευση μιας online εικόνας.

--------------------

> ```
> Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε το σχήμα placeholder Online Image στη διαφάνεια διάταξης.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addOnlineImagePlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η συντεταγμένη X του νέου σχήματος placeholder. |
| y | float | Η συντεταγμένη Y του νέου σχήματος placeholder. |
| width | float | Το πλάτος του νέου σχήματος placeholder. |
| height | float | Το ύψος του νέου σχήματος placeholder. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Δημιουργήθηκε [IAutoShape](../../com.aspose.slides/iautoshape) με ένα σύμβολο κράτησης Online Image.