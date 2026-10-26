---
title: IInkBrush
second_title: Aspose.Slides for Java API Reference
description: Represents trace brush.
type: docs
url: /el/com.aspose.slides/iinkbrush/
---```
public interface IInkBrush
```

Αντιπροσωπεύει το πινέλο ίχνους.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getColor()](#getColor--) | Αποκτά ή ορίζει το χρώμα της βούρτσας για μια γραμμή. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Αποκτά ή ορίζει το χρώμα της βούρτσας για μια γραμμή. |
| [getSize()](#getSize--) | Αποκτά ή ορίζει το μέγεθος της βούρτσας για μια γραμμή σε points. |
| [setSize(Dimension2D value)](#setSize-java.awt.geom.Dimension2D-) | Αποκτά ή ορίζει το μέγεθος της βούρτσας για μια γραμμή σε points. |
| [getInkEffect()](#getInkEffect--) | Αποκτά τον τύπο εφέ μεθόσης (π.χ., Galaxy, Gold, Silver) που ορίζει το οπτικό στυλ του ίχνος μεθόσης. |
### getColor() {#getColor--}
```
public abstract Color getColor()
```


Αποκτά ή ορίζει το χρώμα της βούρτσας για μια γραμμή.

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
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```


Αποκτά ή ορίζει το χρώμα της βούρτσας για μια γραμμή.

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Color |  |

### getSize() {#getSize--}
```
public abstract Dimension2D getSize()
```


Αποκτά ή ορίζει το μέγεθος της βούρτσας για μια γραμμή σε points.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      Dimension2D brushSize = brush.getSize();
>      brush.setSize(new Dimension(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
java.awt.geom.Dimension2D
### setSize(Dimension2D value) {#setSize-java.awt.geom.Dimension2D-}
```
public abstract void setSize(Dimension2D value)
```


Αποκτά ή ορίζει το μέγεθος της βούρτσας για μια γραμμή σε points.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      Dimension2D brushSize = brush.getSize();
>      brush.setSize(new Dimension(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.geom.Dimension2D |  |

### getInkEffect() {#getInkEffect--}
```
public abstract int getInkEffect()
```


Αποκτά τον τύπο εφέ μεθόσης (π.χ., Galaxy, Gold, Silver) που ορίζει το οπτικό στυλ του ίχνος μεθόσης. Η τιμή αναλύεται από την ιδιότητα της βούρτσας «inkEffects». Εάν δεν έχει οριστεί αναγνωρισμένο εφέ, [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) επιστρέφεται.

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