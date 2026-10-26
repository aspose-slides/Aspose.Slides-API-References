---
title: IInkBrush
second_title: Aspose.Slides για Android μέσω Java API Reference
description: Αναπαριστά πινέλο ίχνους.
type: docs
url: /el/com.aspose.slides/iinkbrush/
---```
public interface IInkBrush
```

Αναπαριστά πινέλο ίχνους.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getColor()](#getColor--) | Λαμβάνει ή ορίζει το χρώμα του πινέλου για μια γραμμή. |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | Λαμβάνει ή ορίζει το χρώμα του πινέλου για μια γραμμή. |
| [getSize()](#getSize--) | Λαμβάνει ή ορίζει το μέγεθος του πινέλου για μια γραμμή σε points. |
| [setSize(SizeF value)](#setSize-com.aspose.slides.android.SizeF-) | Λαμβάνει ή ορίζει το μέγεθος του πινέλου για μια γραμμή σε points. |
| [getInkEffect()](#getInkEffect--) | Λαμβάνει τον τύπο εφέ μελάνης (π.χ., Galaxy, Gold, Silver) που ορίζει το οπτικό στυλ της γραμμής μελάνης. |

### getColor() {#getColor--}
```
public abstract Integer getColor()
```

Λαμβάνει ή ορίζει το χρώμα του πινέλου για μια γραμμή.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      Color brushColor = brush.getColor();
>      brush.setColor(Color.RED);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
java.lang.Integer

### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public abstract void setColor(Integer value)
```

Λαμβάνει ή ορίζει το χρώμα του πινέλου για μια γραμμή.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      Color brushColor = brush.getColor();
>      brush.setColor(Color.RED);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getSize() {#getSize--}
```
public abstract SizeF getSize()
```

Λαμβάνει ή ορίζει το μέγεθος του πινέλου για μια γραμμή σε points.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      SizeF brushSize = brush.getSize();
>      brush.setSize(new com.aspose.slides.android.Size(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
[SizeF](../../com.aspose.slides.android/sizef)

### setSize(SizeF value) {#setSize-com.aspose.slides.android.SizeF-}
```
public abstract void setSize(SizeF value)
```

Λαμβάνει ή ορίζει το μέγεθος του πινέλου για μια γραμμή σε points.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      SizeF brushSize = brush.getSize();
>      brush.setSize(new com.aspose.slides.android.Size(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.slides.android/sizef) |  |

### getInkEffect() {#getInkEffect--}
```
public abstract int getInkEffect()
```

Λαμβάνει τον τύπο εφέ μελάνης (π.χ., Galaxy, Gold, Silver) που ορίζει το οπτικό στυλ της γραμμής μελάνης. Η τιμή αναλύεται από την ιδιότητα του πινέλου «inkEffects». Εάν δεν έχει οριστεί αναγνωρισμένο εφέ, [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) επιστρέφεται.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      Ink ink = (Ink) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkBrush brush = ink.getTraces()[0].getBrush();
>      System.out.println("InkEffects = " + brush.getInkEffect());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
int