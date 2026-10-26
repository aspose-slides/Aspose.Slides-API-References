---
title: InkBrush
second_title: Αναφορά API Aspose.Slides για Java
description: Αναπαριστά ένα αντικείμενο inkBrush.
type: docs
url: /el/com.aspose.slides/inkbrush/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IInkBrush](../../com.aspose.slides/iinkbrush)
```
public class InkBrush implements IInkBrush
```

Αναπαριστά ένα αντικείμενο inkBrush.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getColor()](#getColor--) | Λαμβάνει ή ορίζει το χρώμα της βούρτσας για μια γραμμή. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Λαμβάνει ή ορίζει το χρώμα της βούρτσας για μια γραμμή. |
| [getSize()](#getSize--) | Λαμβάνει ή ορίζει το μέγεθος της βούρτσας για μια γραμμή σε μονάδες σημείου. |
| [setSize(Dimension2D value)](#setSize-java.awt.geom.Dimension2D-) | Λαμβάνει ή ορίζει το μέγεθος της βούρτσας για μια γραμμή σε μονάδες σημείου. |
| [getInkEffect()](#getInkEffect--) | Λαμβάνει τον τύπο εφέ μελανιού (π.χ., Galaxy, Gold, Silver) που ορίζει το οπτικό στυλ του χτυπήματος μελανιού. |
### getColor() {#getColor--}
```
public final Color getColor()
```

Λαμβάνει ή ορίζει το χρώμα της βούρτσας για μια γραμμή.

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
public final void setColor(Color value)
```

Λαμβάνει ή ορίζει το χρώμα της βούρτσας για μια γραμμή.

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
| value | java.awt.Color |  |
### getSize() {#getSize--}
```
public final Dimension2D getSize()
```

Λαμβάνει ή ορίζει το μέγεθος της βούρτσας για μια γραμμή σε μονάδες σημείου.

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
public final void setSize(Dimension2D value)
```

Λαμβάνει ή ορίζει το μέγεθος της βούρτσας για μια γραμμή σε μονάδες σημείου.

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.awt.geom.Dimension2D |  |
### getInkEffect() {#getInkEffect--}
```
public final int getInkEffect()
```

Λαμβάνει τον τύπο εφέ μελανιού (π.χ., Galaxy, Gold, Silver) που ορίζει το οπτικό στυλ του χτυπήματος μελανιού. Η τιμή αναλύεται από την ιδιότητα της βούρτσας "inkEffects". Εάν δεν οριστεί κάποιο αναγνωρισμένο εφέ, [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) επιστρέφεται.

**Επιστρέφει:**
int