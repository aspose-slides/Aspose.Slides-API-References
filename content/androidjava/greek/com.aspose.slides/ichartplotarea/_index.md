---
title: IChartPlotArea
second_title: Αναφορά API Java για Aspose.Slides για Android
description: Αντιπροσωπεύει τις ιδιότητες του τίτλου του γραφήματος.
type: docs
url: /el/com.aspose.slides/ichartplotarea/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartPlotArea extends ILayoutable, IActualLayout
```

Αντιπροσωπεύει τις ιδιότητες του τίτλου του γραφήματος.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFormat()](#getFormat--) | Επιστρέφει τη μορφή μιας περιοχής σχεδίασης. |
| [getLayoutTargetType()](#getLayoutTargetType--) | Εάν η διάταξη της περιοχής σχεδίασης ορίζεται χειροκίνητα, αυτή η ιδιότητα καθορίζει εάν η διάταξη της περιοχής σχεδίασης θα γίνει βάση του εσωτερικού της (χωρίς τους άξονες και τις ετικέτες άξονα) ή του εξωτερικού (συμπεριλαμβανομένων των αξόνων και των ετικετών άξονα). |
| [setLayoutTargetType(int value)](#setLayoutTargetType-int-) | Εάν η διάταξη της περιοχής σχεδίασης ορίζεται χειροκίνητα, αυτή η ιδιότητα καθορίζει εάν η διάταξη της περιοχής σχεδίασης θα γίνει βάση του εσωτερικού της (χωρίς τους άξονες και τις ετικέτες άξονα) ή του εξωτερικού (συμπεριλαμβανομένων των αξόνων και των ετικετών άξονα). |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Επιστρέφει τη μορφή μιας περιοχής σχεδίασης. Μόνο για ανάγνωση [IFormat](../../com.aspose.slides/iformat).

**Επιστρέφει:**
[IFormat](../../com.aspose.slides/iformat)

### getLayoutTargetType() {#getLayoutTargetType--}
```
public abstract int getLayoutTargetType()
```

Εάν η διάταξη της περιοχής σχεδίασης ορίζεται χειροκίνητα, αυτή η ιδιότητα καθορίζει εάν η διάταξη της περιοχής σχεδίασης θα γίνει βάση του εσωτερικού της (χωρίς τους άξονες και τις ετικέτες άξονα) ή του εξωτερικού (συμπεριλαμβανομένων των αξόνων και των ετικετών άξονα). Ανάγνωση/εγγραφή [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

--------------------

> ```
> Presentation presentation = new Presentation();
>   try
>   {
>       ISlide slide = presentation.getSlides().get_Item(0);
>       IChart chart = slide.getShapes().addChart(ChartType.ClusteredColumn, 20, 100, 600, 400);
>       chart.getPlotArea().setX(0.2f);
>       chart.getPlotArea().setY(0.2f);
>       chart.getPlotArea().setWidth(0.7f);
>       chart.getPlotArea().setHeight(0.7f);
>       chart.getPlotArea().setLayoutTargetType(LayoutTargetType.Inner);
>   } finally {
>       if (presentation != null) presentation.dispose();
>   }
> ```

**Επιστρέφει:**
int

### setLayoutTargetType(int value) {#setLayoutTargetType-int-}
```
public abstract void setLayoutTargetType(int value)
```

Εάν η διάταξη της περιοχής σχεδίασης ορίζεται χειροκίνητα, αυτή η ιδιότητα καθορίζει εάν η διάταξη της περιοχής σχεδίασης θα γίνει βάση του εσωτερικού της (χωρίς τους άξονες και τις ετικέτες άξονα) ή του εξωτερικού (συμπεριλαμβανομένων των αξόνων και των ετικετών άξονα). Ανάγνωση/εγγραφή [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

--------------------

> ```
> Presentation presentation = new Presentation();
>   try
>   {
>       ISlide slide = presentation.getSlides().get_Item(0);
>       IChart chart = slide.getShapes().addChart(ChartType.ClusteredColumn, 20, 100, 600, 400);
>       chart.getPlotArea().setX(0.2f);
>       chart.getPlotArea().setY(0.2f);
>       chart.getPlotArea().setWidth(0.7f);
>       chart.getPlotArea().setHeight(0.7f);
>       chart.getPlotArea().setLayoutTargetType(LayoutTargetType.Inner);
>   } finally {
>       if (presentation != null) presentation.dispose();
>   }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |