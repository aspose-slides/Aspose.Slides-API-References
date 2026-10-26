---
title: ILayoutPlaceholderManager
second_title: Aspose.Slides for Java API Reference
description: Αντιπροσωπεύει ένα διαχειριστή που σας επιτρέπει να προσθέσετε σύμβολα κράτησης θέσης στη διαφάνεια διάταξης.
type: docs
url: /el/com.aspose.slides/ilayoutplaceholdermanager/
---```
public interface ILayoutPlaceholderManager
```

Αντιπροσωπεύει ένα διαχειριστή που σας επιτρέπει να προσθέσετε σύμβολα κράτησης θέσης στη διαφάνεια διάταξης.
## Μέθοδοι

| Method | Description |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | Adds a new placeholder shape to the layout slide to hold content, such as a picture, table, media or text. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | Adds a new placeholder shape to the layout slide to hold content, such as a picture, table, media or text in a vertical direction. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | Adds a new placeholder shape to the layout slide to hold text content. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | Adds a new placeholder shape to the layout slide to hold text content in a vertical direction. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | Adds a new placeholder shape to the layout slide to hold a picture. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | Adds a new placeholder shape to the layout slide to hold a chart. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | Adds a new placeholder shape to the layout slide to hold a table. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | Adds a new placeholder shape to the layout slide to hold a SmartArt diagram. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | Adds a new placeholder shape to the layout slide to hold a media object. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | Adds a new placeholder shape to the layout slide to hold an online image. |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```

Προσθέτει ένα νέο σχήμα σύμβολου κράτησης θέσης στη διαφάνεια διάταξης για να κρατήσει περιεχόμενο, όπως μια εικόνα, πίνακα, μέσο ή κείμενο.

--------------------

> ```
> The following example shows how to add the Content placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addContentPlaceholder(20, 20, 500, 300);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Η συντεταγμένη X του νέου σχήματος σύμβολου κράτησης θέσης. |
| y | float | Η συντεταγμένη Y του νέου σχήματος σύμβολου κράτησης θέσης. |
| width | float | Το πλάτος του νέου σχήματος σύμβολου κράτησης θέσης. |
| height | float | Το ύψος του νέου σχήματος σύμβολου κράτησης θέσης. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Δημιουργήθηκε [IAutoShape](../../com.aspose.slides/iautoshape) με ένα Placeholder περιεχομένου.
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```

Προσθέτει ένα νέο σχήμα σύμβολου κράτησης θέσης στη διαφάνεια διάταξης για να κρατήσει περιεχόμενο, όπως μια εικόνα, πίνακα, μέσο ή κείμενο σε κάθετη κατεύθυνση.

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
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Η συντεταγμένη X του νέου σχήματος σύμβολου κράτησης θέσης. |
| y | float | Η συντεταγμένη Y του νέου σχήματος σύμβολου κράτησης θέσης. |
| width | float | Το πλάτος του νέου σχήματος σύμβολου κράτησης θέσης. |
| height | float | Το ύψος του νέου σχήματος σύμβολου κράτησης θέσης. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Δημιουργήθηκε [IAutoShape](../../com.aspose.slides/iautoshape) με ένα Placeholder Περιεχομένου (Κάθετο).
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```

Προσθέτει ένα νέο σχήμα σύμβολου κράτησης θέσης στη διαφάνεια διάταξης για να κρατήσει κειμενικό περιεχόμενο.

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
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Η συντεταγμένη X του νέου σχήματος σύμβολου κράτησης θέσης. |
| y | float | Η συντεταγμένη Y του νέου σχήματος σύμβολου κράτησης θέσης. |
| width | float | Το πλάτος του νέου σχήματος σύμβολου κράτησης θέσης. |
| height | float | Το ύψος του νέου σχήματος σύμβολου κράτησης θέσης. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Δημιουργήθηκε [IAutoShape](../../com.aspose.slides/iautoshape) με ένα Placeholder κειμένου.
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```

Προσθέτει ένα νέο σχήμα σύμβολου κράτησης θέσης στη διαφάνεια διάταξης για να κρατήσει κειμενικό περιεχόμενο σε κάθετη κατεύθυνση.

--------------------

> ```
> The following example shows how to add the Text (Vertical) placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addVerticalTextPlaceholder(20, 20, 300, 500);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Η συντεταγμένη X του νέου σχήματος σύμβολου κράτησης θέσης. |
| y | float | Η συντεταγμένη Y του νέου σχήματος σύμβολου κράτησης θέσης. |
| width | float | Το πλάτος του νέου σχήματος σύμβολου κράτησης θέσης. |
| height | float | Το ύψος του νέου σχήματος σύμβολου κράτησης θέσης. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Δημιουργήθηκε [IAutoShape](../../com.aspose.slides/iautoshape) με ένα Placeholder κειμένου (Κάθετο).
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```

Προσθέτει ένα νέο σχήμα σύμβολου κράτησης θέσης στη διαφάνεια διάταξης για να κρατήσει μια εικόνα.

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
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Η συντεταγμένη X του νέου σχήματος σύμβολου κράτησης θέσης. |
| y | float | Η συντεταγμένη Y του νέου σχήματος σύμβολου κράτησης θέσης. |
| width | float | Το πλάτος του νέου σχήματος σύμβολου κράτησης θέσης. |
| height | float | Το ύψος του νέου σχήματος σύμβολου κράτησης θέσης. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Δημιουργήθηκε [IAutoShape](../../com.aspose.slides/iautoshape) με ένα Placeholder εικόνας.
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```

Προσθέτει ένα νέο σχήμα σύμβολου κράτησης θέσης στη διαφάνεια διάταξης για να κρατήσει ένα διάγραμμα.

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
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Η συντεταγμένη X του νέου σχήματος σύμβολου κράτησης θέσης. |
| y | float | Η συντεταγμένη Y του νέου σχήματος σύμβολου κράτησης θέσης. |
| width | float | Το πλάτος του νέου σχήματος σύμβολου κράτησης θέσης. |
| height | float | Το ύψος του νέου σχήματος σύμβολου κράτησης θέσης. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Δημιουργήθηκε [IAutoShape](../../com.aspose.slides/iautoshape) με ένα Placeholder διαγράμματος.
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```

Προσθέτει ένα νέο σχήμα σύμβολου κράτησης θέσης στη διαφάνεια διάταξης για να κρατήσει έναν πίνακα.

--------------------

> ```
> The following example shows how to add the Table placeholder shape to the layout slide.
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
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Η συντεταγμένη X του νέου σχήματος σύμβολου κράτησης θέσης. |
| y | float | Η συντεταγμένη Y του νέου σχήματος σύμβολου κράτησης θέσης. |
| width | float | Το πλάτος του νέου σχήματος σύβολου κράτησης θέσης. |
| height | float | Το ύψος του νέου σχήματος σύβολου κράτησης θέσης. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Δημιουργήθηκε [IAutoShape](../../com.aspose.slides/iautoshape) με ένα Placeholder πίνακα.
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```

Προσθέτει ένα νέο σχήμα σύμβολου κράτησης θέσης στη διαφάνεια διάταξης για να κρατήσει ένα SmartArt διάγραμμα.

--------------------

> ```
> The following example shows how to add the SmartArt placeholder shape to the layout slide.
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
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Η συντεταγμένη X του νέου σχήματος σύβολου κράτησης θέσης. |
| y | float | Η συντεταγμένη Y του νέου σχήματος σύβολου κράτησης θέσης. |
| width | float | Το πλάτος του νέου σχήματος σύβολου κράτησης θέσης. |
| height | float | Το ύψος του νέου σχήματος σύβολου κράτησης θέσης. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Δημιουργήθηκε [IAutoShape](../../com.aspose.slides/iautoshape) με ένα SmartArt Placeholder.
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```

Προσθέτει ένα νέο σχήμα σύβολου κράτησης θέσης στη διαφάνεια διάταξης για να κρατήσει ένα αντικείμενο πολυμέσων.

--------------------

> ```
> The following example shows how to add the Media placeholder shape to the layout slide.
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
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Η συντεταγμένη X του νέου σχήματος σύβολου κράτησης θέσης. |
| y | float | Η συντεταγμένη Y του νέου σχήματος σύβολου κράτησης θέσης. |
| width | float | Το πλάτος του νέου σχήματος σύβολου κράτησης θέσης. |
| height | float | Το ύψος του νέου σχήματος σύβολου κράτησης θέσης. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Δημιουργήθηκε [IAutoShape](../../com.aspose.slides/iautoshape) με ένα Placeholder πολυμέσων.
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```

Προσθέτει ένα νέο σχήμα σύβολου κράτησης θέσης στη διαφάνεια διάταξης για να κρατήσει μια διαδικτυακή εικόνα.

--------------------

> ```
> The following example shows how to add the Online Image placeholder shape to the layout slide.
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
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Η συντεταγμένη X του νέου σχήματος σύβολου κράτησης θέσης. |
| y | float | Η συντεταγμένη Y του νέου σχήματος σύβολου κράτησης θέσης. |
| width | float | Το πλάτος του νέου σχήματος σύβολου κράτησης θέσης. |
| height | float | Το ύψος του νέου σχήματος σύβολου κράτησης θέσης. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Δημιουργήθηκε [IAutoShape](../../com.aspose.slides/iautoshape) με ένα Placeholder διαδικτυακής εικόνας.