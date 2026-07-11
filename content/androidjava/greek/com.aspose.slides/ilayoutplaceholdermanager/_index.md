---
title: ILayoutPlaceholderManager
second_title: Aspose.Slides για Android μέσω Java API Reference
description: Αντιπροσωπεύει διαχειριστή που επιτρέπει την προσθήκη placeholders στη διαφάνεια διάταξης.
type: docs
url: /el/com.aspose.slides/ilayoutplaceholdermanager/
---```
public interface ILayoutPlaceholderManager
```

Αντιπροσωπεύει διαχειριστή που επιτρέπει την προσθήκη placeholders στη διαφάνεια διάταξης.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | Προσθέτει ένα νέο σχήμα placeholder στη διαφάνεια διάταξης για να κρατήσει περιεχόμενο, όπως μια εικόνα, πίνακα, πολυμέσα ή κείμενο. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | Προσθέτει ένα νέο σχήμα placeholder στη διαφάνεια διάταξης για να κρατήσει περιεχόμενο, όπως μια εικόνα, πίνακα, πολυμέσα ή κείμενο σε κατακόρυφη κατεύθυνση. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | Προσθέτει ένα νέο σχήμα placeholder στη διαφάνεια διάταξης για να κρατήσει κείμενο. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | Προσθέτει ένα νέο σχήμα placeholder στη διαφάνεια διάταξης για να κρατήσει κείμενο σε κατακόρυφη κατεύθυνση. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | Προσθέτει ένα νέο σχήμα placeholder στη διαφάνεια διάταξης για να κρατήσει μια εικόνα. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | Προσθέτει ένα νέο σχήμα placeholder στη διαφάνεια διάταξης για να κρατήσει ένα γράφημα. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | Προσθέτει ένα νέο σχήμα placeholder στη διαφάνεια διάταξης για να κρατήσει έναν πίνακα. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | Προσθέτει ένα νέο σχήμα placeholder στη διαφάνεια διάταξης για να κρατήσει ένα διάγραμμα SmartArt. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | Προσθέτει ένα νέο σχήμα placeholder στη διαφάνεια διάταξης για να κρατήσει ένα αντικείμενο πολυμέσων. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | Προσθέτει ένα νέο σχήμα placeholder στη διαφάνεια διάταξης για να κρατήσει μια online εικόνα. |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```


Προσθέτει ένα νέο σχήμα placeholder στη διαφάνεια διάταξης για να κρατήσει περιεχόμενο, όπως μια εικόνα, πίνακα, πολυμέσα ή κείμενο.

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
| x | float | The X coordinate of the new placeholder shape. |
| y | float | The Y coordinate of the new placeholder shape. |
| width | float | The width of the new placeholder shape. |
| height | float | The height of the new placeholder shape. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Created [IAutoShape](../../com.aspose.slides/iautoshape) with a Content placeholder.
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```


Προσθέτει ένα νέο σχήμα placeholder στη διαφάνεια διάταξης για να κρατήσει περιεχόμενο, όπως μια εικόνα, πίνακα, πολυμέσα ή κείμενο σε κατακόρυφη κατεύθυνση.

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
| x | float | The X coordinate of the new placeholder shape. |
| y | float | The Y coordinate of the new placeholder shape. |
| width | float | The width of the new placeholder shape. |
| height | float | The height of the new placeholder shape. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Created [IAutoShape](../../com.aspose.slides/iautoshape) with a Content (Vertical) placeholder.
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```


Προσθέτει ένα νέο σχήμα placeholder στη διαφάνεια διάταξης για να κρατήσει κείμενο.

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
| x | float | The X coordinate of the new placeholder shape. |
| y | float | The Y coordinate of the new placeholder shape. |
| width | float | The width of the new placeholder shape. |
| height | float | The height of the new placeholder shape. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Created [IAutoShape](../../com.aspose.slides/iautoshape) with a Text placeholder.
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```


Προσθέτει ένα νέο σχήμα placeholder στη διαφάνεια διάταξης για να κρατήσει κείμενο σε κατακόρυφη κατεύθυνση.

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
| x | float | The X coordinate of the new placeholder shape. |
| y | float | The Y coordinate of the new placeholder shape. |
| width | float | The width of the new placeholder shape. |
| height | float | The height of the new placeholder shape. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Created [IAutoShape](../../com.aspose.slides/iautoshape) with a Text (Vertical) placeholder.
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```


Προσθέτει ένα νέο σχήμα placeholder στη διαφάνεια διάταξης για να κρατήσει μια εικόνα.

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
| x | float | The X coordinate of the new placeholder shape. |
| y | float | The Y coordinate of the new placeholder shape. |
| width | float | The width of the new placeholder shape. |
| height | float | The height of the new placeholder shape. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Created [IAutoShape](../../com.aspose.slides/iautoshape) with a Picture placeholder.
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```


Προσθέτει ένα νέο σχήμα placeholder στη διαφάνεια διάταξης για να κρατήσει ένα γράφημα.

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
| x | float | The X coordinate of the new placeholder shape. |
| y | float | The Y coordinate of the new placeholder shape. |
| width | float | The width of the new placeholder shape. |
| height | float | The height of the new placeholder shape. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Created [IAutoShape](../../com.aspose.slides/iautoshape) with a Chart placeholder.
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```


Προσθέτει ένα νέο σχήμα placeholder στη διαφάνεια διάταξης για να κρατήσει έναν πίνακα.

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
| x | float | The X coordinate of the new placeholder shape. |
| y | float | The Y coordinate of the new placeholder shape. |
| width | float | The width of the new placeholder shape. |
| height | float | The height of the new placeholder shape. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Created [IAutoShape](../../com.aspose.slides/iautoshape) with a Table placeholder.
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```


Προσθέτει ένα νέο σχήμα placeholder στη διαφάνεια διάταξης για να κρατήσει ένα διάγραμμα SmartArt.

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
| x | float | The X coordinate of the new placeholder shape. |
| y | float | The Y coordinate of the new placeholder shape. |
| width | float | The width of the new placeholder shape. |
| height | float | The height of the new placeholder shape. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Created [IAutoShape](../../com.aspose.slides/iautoshape) with a SmartArt placeholder.
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```


Προσθέτει ένα νέο σχήμα placeholder στη διαφάνεια διάταξης για να κρατήσει ένα αντικείμενο πολυμέσων.

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
| x | float | The X coordinate of the new placeholder shape. |
| y | float | The Y coordinate of the new placeholder shape. |
| width | float | The width of the new placeholder shape. |
| height | float | The height of the new placeholder shape. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Created [IAutoShape](../../com.aspose.slides/iautoshape) with a Media placeholder.
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```


Προσθέτει ένα νέο σχήμα placeholder στη διαφάνεια διάταξης για να κρατήσει μια online εικόνα.

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
| x | float | The X coordinate of the new placeholder shape. |
| y | float | The Y coordinate of the new placeholder shape. |
| width | float | The width of the new placeholder shape. |
| height | float | The height of the new placeholder shape. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Created [IAutoShape](../../com.aspose.slides/iautoshape) with an Online Image placeholder.