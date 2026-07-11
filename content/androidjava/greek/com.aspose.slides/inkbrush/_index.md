---
title: InkBrush
second_title: Aspose.Slides για Android μέσω Αναφοράς API Java
description: Αναπαριστά ένα αντικείμενο inkBrush.
type: docs
url: /el/com.aspose.slides/inkbrush/
---
**Κληρονόμηση:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IInkBrush](../../com.aspose.slides/iinkbrush)
```
public class InkBrush implements IInkBrush
```

Αναπαριστά ένα αντικείμενο inkBrush.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getColor()](#getColor--) | Παίρνει ή ορίζει το χρώμα του πινέλου για μια γραμμή. |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | Παίρνει ή ορίζει το χρώμα του πινέλου για μια γραμμή. |
| [getSize()](#getSize--) | Παίρνει ή ορίζει το μέγεθος του πινέλου για μια γραμμή σε σημεία. |
| [setSize(SizeF value)](#setSize-com.aspose.slides.android.SizeF-) | Παίρνει ή ορίζει το μέγεθος του πινέλου για μια γραμμή σε σημεία. |
| [getInkEffect()](#getInkEffect--) | Παίρνει τον τύπο εφέ μελανιού (π.χ., Galaxy, Gold, Silver) που ορίζει το οπτικό στυλ του χτυπήματος μελάνης. |

### getColor() {#getColor--}
```
public final Integer getColor()
```

Παίρνει ή ορίζει το χρώμα του πινέλου για μια γραμμή.

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
public final void setColor(Integer value)
```

Παίρνει ή ορίζει το χρώμα του πινέλου για μια γραμμή.

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
public final SizeF getSize()
```

Παίρνει ή ορίζει το μέγεθος του πινέλου για μια γραμμή σε σημεία.

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
public final void setSize(SizeF value)
```

Παίρνει ή ορίζει το μέγεθος του πινέλου για μια γραμμή σε σημεία.

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
public final int getInkEffect()
```

Παίρνει τον τύπο εφέ μελανιού (π.χ., Galaxy, Gold, Silver) που ορίζει το οπτικό στυλ του χτυπήματος μελάνης. Η τιμή γίνεται parse από την ιδιότητα του πινέλου «inkEffects». Αν δεν έχει καθοριστεί κάποιο αναγνωρισμένο εφέ, επιστρέφεται το [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined).

**Επιστρέφει:**
int