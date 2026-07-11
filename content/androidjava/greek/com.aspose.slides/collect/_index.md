---
title: Collect
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αντιπροσωπεύει μια ομάδα μεθόδων που προορίζονται για τη συλλογή αντικειμένων μοντέλου διαφορετικών τύπων από .
type: docs
url: /el/com.aspose.slides/collect/
---
**Κληρονομικότητα:**
java.lang.Object
```
public class Collect
```

Αντιπροσωπεύει μια ομάδα μεθόδων που προορίζονται για τη συλλογή αντικειμένων μοντέλου διαφορετικών τύπων από [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // ... αλλαγή μορφοποίησης σχήματος ή άλλων ιδιοτήτων
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Collect()](#Collect--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [shapes(Presentation pres)](#shapes-com.aspose.slides.Presentation-) | Συλλέγει όλες τις παρουσίες του [Shape](../../com.aspose.slides/shape) στο [Presentation](../../com.aspose.slides/presentation). |
### Collect() {#Collect--}
```
public Collect()
```


### shapes(Presentation pres) {#shapes-com.aspose.slides.Presentation-}
```
public static System.Collections.Generic.IGenericEnumerable<Shape> shapes(Presentation pres)
```


Συλλέγει όλες τις παρουσίες του [Shape](../../com.aspose.slides/shape) στο [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // αν το σχήμα είναι AutoShape, προσθέστε ένα μαύρο στερεό περίγραμμα
>          if (shape instanceof AutoShape)
>          {
>              AutoShape autoShape = (AutoShape)shape;
>              autoShape.getLineFormat().setStyle(LineStyle.Single);
>              autoShape.getLineFormat().setWidth(10f);
>              autoShape.getLineFormat().getFillFormat().setFillType(FillType.Solid);
>              autoShape.getLineFormat().getFillFormat().getSolidFillColor().setColor(Color.black);
>          }
>      }
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Παρουσίαση για τη συλλογή σχημάτων |

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.Shape> - Συλλογή όλων των σχημάτων που περιέχονται στην παρουσίαση