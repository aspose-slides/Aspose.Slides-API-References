---
title: LayoutPlaceholderManager
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αντιπροσωπεύει έναν διαχειριστή που επιτρέπει την προσθήκη δεσμευτών θέσης στη διαφάνεια διάταξης.
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

Αντιπροσωπεύει έναν διαχειριστή που επιτρέπει την προσθήκη δεσμευτών θέσης στη διαφάνεια διάταξης.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | Προσθέτει ένα νέο σχήμα δεσμευτή θέσης στη διαφάνεια διάταξης για να κρατήσει περιεχόμενο, όπως μια εικόνα, πίνακα, πολυμέσο ή κείμενο. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | Προσθέτει ένα νέο σχήμα δεσμευτή θέσης στη διαφάνεια διάταξης για να κρατήσει περιεχόμενο, όπως μια εικόνα, πίνακα, πολυμέσο ή κείμενο σε κατακόρυφη κατεύθυνση. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | Προσθέτει ένα νέο σχήμα δεσμευτή θέσης στη διαφάνεια διάταξης για να κρατήσει κειμενικό περιεχόμενο. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | Προσθέτει ένα νέο σχήμα δεσμευτή θέσης στη διαφάνεια διάταξης για να κρατήσει κειμενικό περιεχόμενο σε κατακόρυφη κατεύθυνση. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | Προσθέτει ένα νέο σχήμα δεσμευτή θέσης στη διαφάνεια διάταξης για να κρατήσει μια εικόνα. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | Προσθέτει ένα νέο σχήμα δεσμευτή θέσης στη διαφάνεια διάταξης για να κρατήσει ένα γράφημα. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | Προσθέτει ένα νέο σχήμα δεσμευτή θέσης στη διαφάνεια διάταξης για να κρατήσει έναν πίνακα. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | Προσθέτει ένα νέο σχήμα δεσμευτή θέσης στη διαφάνεια διάταξης για να κρατήσει ένα διάγραμμα SmartArt. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | Προσθέτει ένα νέο σχήμα δεσμευτή θέσης στη διαφάνεια διάταξης για να κρατήσει ένα αντικείμενο πολυμέσου. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | Προσθέτει ένα νέο σχήμα δεσμευτή θέσης στη διαφάνεια διάταξης για να κρατήσει μια διαδικτυακή εικόνα. |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```

Προσθέτει ένα νέο σχήμα δεσμευτή θέσης στη διαφάνεια διάταξης για να κρατήσει περιεχόμενο, όπως μια εικόνα, πίνακα, πολυμέσο ή κείμενο.

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
| x | float | Η συντεταγμένη X του νέου σχήματος δεσμευτή θέσης. |
| y | float | Η συντεταγμένη Y του νέου σχήματος δεσμευτή θέσης. |
| width | float | Το πλάτος του νέου σχήματος δεσμευτή θέσης. |
| height | float | Το ύψος του νέου σχήματος δεσμευτή θέσης. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Δημιουργήθηκε [IAutoShape](../../com.aspose.slides/iautoshape) με έναν δεσμευτή θέσης Περιεχομένου.
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```

Προσθέτει ένα νέο σχήμα δεσμευτή θέσης στη διαφάνεια διάταξης για να κρατήσει περιεχόμενο, όπως μια εικόνα, πίνακα, πολυμέσο ή κείμενο σε κατακόρυφη κατεύθυνση.

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
| x | float | Η συντεταγμένη X του νέου σχήματος δεσμευτή θέσης. |
| y | float | Η συντεταγμένη Y του νέου σχήματος δεσμευτή θέσης. |
| width | float | Το πλάτος του νέου σχήματος δεσμευτή θέσης. |
| height | float | Το ύψος του νέου σχήματος δεσμευτή θέσης. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Δημιουργήθηκε [IAutoShape](../../com.aspose.slides/iautoshape) με έναν δεσμευτή θέσης Περιεχομένου (Κατακόρυφο).
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```

Προσθέτει ένα νέο σχήμα δεσμευτή θέσης στη διαφάνεια διάταξης για να κρατήσει κειμενικό περιεχόμενο.

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
| x | float | Η συντεταγμένη X του νέου σχήματος δεσμευτή θέσης. |
| y | float | Η συντεταγμένη Y του νέου σχήματος δεσμευτή θέσης. |
| width | float | Το πλάτος του νέου σχήματος δεσμευτή θέσης. |
| height | float | Το ύψος του νέου σχήματος δεσμευτή θέσης. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Δημιουργήθηκε [IAutoShape](../../com.aspose.slides/iautoshape) με έναν δεσμευτή θέσης Κειμένου.
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```

Προσθέτει ένα νέο σχήμα δεσμευτή θέσης στη διαφάνεια διάταξης για να κρατήσει κειμενικό περιεχόμενο σε κατακόρυφη κατεύθυνση.

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
| x | float | Η συντεταγμένη X του νέου σχήματος δεσμευτή θέσης. |
| y | float | Η συντεταγμένη Y του νέου σχήματος δεσμευτή θέσης. |
| width | float | Το πλάτος του νέου σχήματος δεσμευτή θέσης. |
| height | float | Το ύψος του νέου σχήματος δεσμευτή θέσης. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Δημιουργήθηκε [IAutoShape](../../com.aspose.slides/iautoshape) με έναν δεσμευτή θέσης Κειμένου (Κατακόρυφο).
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public final IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```

Προσθέτει ένα νέο σχήμα δεσμευτή θέσης στη διαφάνεια διάταξης για να κρατήσει μια εικόνα.

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
| x | float | Η συντεταγμένη X του νέου σχήματος δεσμευτή θέσης. |
| y | float | Η συντεταγμένη Y του νέου σχήματος δεσμευτή θέσης. |
| width | float | Το πλάτος του νέου σχήματος δεσμευτή θέσης. |
| height | float | Το ύψος του νέου σχήματος δεσμευτή θέσης. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Δημιουργήθηκε [IAutoShape](../../com.aspose.slides/iautoshape) με έναν δεσμευτή θέσης Εικόνας.
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public final IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```

Προσθέτει ένα νέο σχήμα δεσμευτή θέσης στη διαφάνεια διάταξης για να κρατήσει ένα γράφημα.

--------------------

> ```
> The following example shows how to add the Chart placeholder shape to the layout slide.
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
| x | float | Η συντεταγμένη X του νέου σχήματος δεσμευτή θέσης. |
| y | float | Η συντεταγμένη Y του νέου σχήματος δεσμευτή θέσης. |
| width | float | Το πλάτος του νέου σχήματος δεσμευτή θέσης. |
| height | float | Το ύψος του νέου σχήματος δεσμευτή θέσης. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Δημιουργήθηκε [IAutoShape](../../com.aspose.slides/iautoshape) με έναν δεσμευτή θέσης Γραφήματος.
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public final IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```

Προσθέτει ένα νέο σχήμα δεσμευτή θέσης στη διαφάνεια διάταξης για να κρατήσει έναν πίνακα.

--------------------

> ```
> Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε το σχήμα δεσμευτή θέσης Πίνακα στη διαφάνεια διάταξης.
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
| x | float | Η συντεταγμένη X του νέου σχήματος δεσμευτή θέσης. |
| y | float | Η συντεταγμένη Y του νέου σχήματος δεσμευτή θέσης. |
| width | float | Το πλάτος του νέου σχήματος δεσμευτή θέσης. |
| height | float | Το ύψος του νέου σχήματος δεσμευτή θέσης. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Δημιουργήθηκε [IAutoShape](../../com.aspose.slides/iautoshape) με έναν δεσμευτή θέσης Πίνακα.
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public final IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```

Προσθέτει ένα νέο σχήμα δεσμευτή θέσης στη διαφάνεια διάταξης για να κρατήσει ένα διάγραμμα SmartArt.

--------------------

> ```
> Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε το σχήμα δεσμευτή θέσης SmartArt στη διαφάνεια διάταξης.
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
| x | float | Η συντεταγμένη X του νέου σχήματος δεσμευτή θέσης. |
| y | float | Η συντεταγμένη Y του νέου σχήματος δεσμευτή θέσης. |
| width | float | Το πλάτος του νέου σχήματος δεσμευτή θέσης. |
| height | float | Το ύψος του νέου σχήματος δεσμευτή θέσης. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Δημιουργήθηκε [IAutoShape](../../com.aspose.slides/iautoshape) με έναν δεσμευτή θέσης SmartArt.
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public final IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```

Προσθέτει ένα νέο σχήμα δεσμευτή θέσης στη διαφάνεια διάταξης για να κρατήσει ένα αντικείμενο πολυμέσου.

--------------------

> ```
> Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε το σχήμα δεσμευτή θέσης Media στη διαφάνεια διάταξης.
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
| x | float | Η συντεταγμένη X του νέου σχήματος δεσμευτή θέσης. |
| y | float | Η συντεταγμένη Y του νέου σχήματος δεσμευτή θέσης. |
| width | float | Το πλάτος του νέου σχήματος δεσμευτή θέσης. |
| height | float | Το ύψος του νέου σχήματος δεσμευτή θέσης. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Δημιουργήθηκε [IAutoShape](../../com.aspose.slides/iautoshape) με έναν δεσμευτή θέσης Πολυμέσου.
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public final IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```

Προσθέτει ένα νέο σχήμα δεσμευτή θέσης στη διαφάνεια διάταξης για να κρατήσει μια διαδικτυακή εικόνα.

--------------------

> ```
> Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε το σχήμα δεσμευτή θέσης Online Image στη διαφάνεια διάταξης.
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
| x | float | Η συντεταγμένη X του νέου σχήματος δεσμευτή θέσης. |
| y | float | Η συντεταγμένη Y του νέου σχήματος δεσμευτή θέσης. |
| width | float | Το πλάτος του νέου σχήματος δεσμευτή θέσης. |
| height | float | Το ύψος του νέου σχήματος δεσμευτή θέσης. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Δημιουργήθηκε [IAutoShape](../../com.aspose.slides/iautoshape) με έναν δεσμευτή θέσης Διαδικτυακής Εικόνας.