---
title: ChartPlotArea
second_title: Aspose.Slides για την τεκμηρίωση API του Java
description: Αναπαριστά το ορθογώνιο όπου πρέπει να σχεδιαστεί το γράφημα.
type: docs
url: /el/com.aspose.slides/chartplotarea/
---
**Κληρονομικότητα:**
java.lang.Object, com.aspose.slides.DomObject

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IChartPlotArea](../../com.aspose.slides/ichartplotarea)
```
public class ChartPlotArea extends DomObject<Chart> implements IChartPlotArea
```

Αναπαριστά το ορθογώνιο όπου πρέπει να σχεδιαστεί το γράφημα.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFormat()](#getFormat--) | Επιστρέφει τη μορφή μιας περιοχής σχεδίασης. |
| [getX()](#getX--) | Επιστρέφει ή ορίζει την τιμή του x συντεταγμένου της επάνω αριστερής γωνίας του πλαισίου περιοχής σχεδίασης ως κλάσμα του πλάτους του διαγράμματος (από 0 έως 1). |
| [setX(float value)](#setX-float-) | Επιστρέφει ή ορίζει την τιμή του x συντεταγμένου της επάνω αριστερής γωνίας του πλαισίου περιοχής σχεδίασης ως κλάσμα του πλάτους του διαγράμματος (από 0 έως 1). |
| [getY()](#getY--) | Επιστρέφει ή ορίζει την τιμή του y συντεταγμένου της επάνω αριστερής γωνίας του πλαισίου περιοχής σχεδίασης ως κλάσμα του ύψους του διαγράμματος (από 0 έως 1). |
| [setY(float value)](#setY-float-) | Επιστρέφει ή ορίζει την τιμή του y συντεταγμένου της επάνω αριστερής γωνίας του πλαισίου περιοχής σχεδίασης ως κλάσμα του ύψους του διαγράμματος (από 0 έως 1). |
| [getWidth()](#getWidth--) | Επιστρέφει ή ορίζει το πλάτος ενός πλαισίου περιοχής σχεδίασης ως κλάσμα του πλάτους του διαγράμματος (από 0 έως 1). |
| [setWidth(float value)](#setWidth-float-) | Επιστρέφει ή ορίζει το πλάτος ενός πλαισίου περιοχής σχεδίασης ως κλάσμα του πλάτους του διαγράμματος (από 0 έως 1). |
| [getHeight()](#getHeight--) | Επιστρέφει ή ορίζει το ύψος ενός πλαισίου περιοχής σχεδίασης ως κλάσμα του ύψους του διαγράμματος (από 0 έως 1). |
| [setHeight(float value)](#setHeight-float-) | Επιστρέφει ή ορίζει το ύψος ενός πλαισίου περιοχής σχεδίασης ως κλάσμα του ύψους του διαγράμματος (από 0 έως 1). |
| [getRight()](#getRight--) | Δεξιά. |
| [getBottom()](#getBottom--) | Κάτω. |
| [getChart()](#getChart--) | Διάγραμμα. |
| [isLocationAutocalculated()](#isLocationAutocalculated--) | Καθορίζει πώς θα υπολογίζεται η θέση: true – υπολογίζεται αυτόματα· ορίζεται από τις ιδιότητες X, Y, Width, Height. |
| [getLayoutTargetType()](#getLayoutTargetType--) | Εάν η διάταξη της περιοχής σχεδίασης καθορίζεται χειροκίνητα, αυτή η ιδιότητα καθορίζει αν η διάταξη θα γίνει κατά εσωτερική πλευρά (χωρίς άξονες και ετικέτες άξονα) ή εξωτερική (με άξονες και ετικέτες άξονα). |
| [setLayoutTargetType(int value)](#setLayoutTargetType-int-) | Εάν η διάταξη της περιοχής σχεδίασης καθορίζεται χειροκίνητα, αυτή η ιδιότητα καθορίζει αν η διάταξη θα γίνει κατά εσωτερική πλευρά (χωρίς άξονες και ετικέτες άξονα) ή εξωτερική (με άξονες και ετικέτες άξονα). |
| [getActualX()](#getActualX--) | Καθορίζει την πραγματική θέση x (αριστερά) του στοιχείου διαγράμματος σε σχέση με την επάνω αριστερή γωνία του διαγράμματος. |
| [getActualY()](#getActualY--) | Καθορίζει την πραγματική κορυφή του στοιχείου διαγράμματος σε σχέση με την επάνω αριστερή γωνία του διαγράμματος. |
| [getActualWidth()](#getActualWidth--) | Καθορίζει το πραγματικό πλάτος του στοιχείου διαγράμματος. |
| [getActualHeight()](#getActualHeight--) | Καθορίζει το πραγματικό ύψος του στοιχείου διαγράμματος. |
| [getSlide()](#getSlide--) | Επιστρέφει τη γονική διαφάνεια ενός FillFormat. |
| [getPresentation()](#getPresentation--) | Επιστρέφει την γονική παρουσίαση ενός FillFormat. |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```


Επιστρέφει τη μορφή μιας περιοχής σχεδίασης. Μόνο για ανάγνωση [IFormat](../../com.aspose.slides/iformat).

**Επιστρέφει:**
[IFormat](../../com.aspose.slides/iformat)
### getX() {#getX--}
```
public final float getX()
```


Επιστρέφει ή ορίζει την τιμή του x συντεταγμένου της επάνω αριστερής γωνίας του πλαισίου περιοχής σχεδίασης ως κλάσμα του πλάτους του διαγράμματος (από 0 έως 1). Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```


Επιστρέφει ή ορίζει την τιμή του x συντεταγμένου της επάνω αριστερής γωνίας του πλαισίου περιοχής σχεδίασης ως κλάσμα του πλάτους του διαγράμματος (από 0 έως 1). Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |
### getY() {#getY--}
```
public final float getY()
```


Επιστρέφει ή ορίζει την τιμή του y συντεταγμένου της επάνω αριστερής γωνίας του πλαισίου περιοχής σχεδίασης ως κλάσμα του ύψους του διαγράμματος (από 0 έως 1). Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```


Επιστρέφει ή ορίζει την τιμή του y συντεταγμένου της επάνω αριστερής γωνίας του πλαισίου περιοχής σχεδίασης ως κλάσμα του ύψους του διαγράμματος (από 0 έως 1). Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |
### getWidth() {#getWidth--}
```
public final float getWidth()
```


Επιστρέφει ή ορίζει το πλάτος ενός πλαισίου περιοχής σχεδίασης ως κλήσμα του πλάτους του διαγράμματος (από 0 έως 1). Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


Επιστρέφει ή ορίζει το πλάτος ενός πλαισίου περιοχής σχεδίασης ως κλήσμα του πλάτους του διαγράμματος (από 0 έως 1). Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |
### getHeight() {#getHeight--}
```
public final float getHeight()
```


Επιστρέφει ή ορίζει το ύψος ενός πλαισίου περιοχής σχεδίασης ως κλήσμα του ύψους του διαγράμματος (από 0 έως 1). Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


Επιστρέφει ή ορίζει το ύψος ενός πλαισίου περιοχής σχεδίασης ως κλήσμα του ύψους του διαγράμματος (από 0 έως 1). Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |
### getRight() {#getRight--}
```
public final float getRight()
```


Δεξιά. Μόνο για ανάγνωση float.

**Επιστρέφει:**
float
### getBottom() {#getBottom--}
```
public final float getBottom()
```


Κάτω. Μόνο για ανάγνωση float.

**Επιστρέφει:**
float
### getChart() {#getChart--}
```
public final IChart getChart()
```


Διάγραμμα. Μόνο για ανάγνωση [IChart](../../com.aspose.slides/ichart).

**Επιστρέφει:**
[IChart](../../com.aspose.slides/ichart)
### isLocationAutocalculated() {#isLocationAutocalculated--}
```
public final boolean isLocationAutocalculated()
```


Καθορίζει πώς θα υπολογίζεται η θέση: true – υπολογίζεται αυτόματα; ορίζεται από τις ιδιότητες X, Y, Width, Height. Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean
### getLayoutTargetType() {#getLayoutTargetType--}
```
public final int getLayoutTargetType()
```


Εάν η διάταξη της περιοχής σχεδίασης καθορίζεται χειροκίνητα, αυτή η ιδιότητα καθορίζει αν η διάταξη θα γίνει κατά εσωτερική πλευρά (χωρίς άξονες και ετικέτες άξονα) ή εξωτερική (με άξονες και ετικέτες άξονα). Ανάγνωση/εγγραφή [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

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
>       ...
>   } finally {
>       if (presentation != null) presentation.dispose();
>   }
> ```

**Επιστρέφει:**
int
### setLayoutTargetType(int value) {#setLayoutTargetType-int-}
```
public final void setLayoutTargetType(int value)
```


Εάν η διάταξη της περιοχής σχεδίασης καθορίζεται χειροκίνητα, αυτή η ιδιότητα καθορίζει αν η διάταξη θα γίνει κατά εσωτερική πλευρά (χωρίς άξονες και ετικέτες άξονα) ή εξωτερική (με άξονες και ετικέτες άξονα). Ανάγνωση/εγγραφή [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

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
>       ...
>   } finally {
>       if (presentation != null) presentation.dispose();
>   }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getActualX() {#getActualX--}
```
public final float getActualX()
```


Καθορίζει την πραγματική θέση x (αριστερά) του στοιχείου διαγράμματος σε σχέση με την επάνω αριστερή γωνία του διαγράμματος. Καλέστε τη μέθοδο IChart.ValidateChartLayout() πριν για να λάβετε τις πραγματικές τιμές. Ανάγνωση float.

**Επιστρέφει:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```


Καθορίζει την πραγματική κορυφή του στοιχείου διαγράμματος σε σχέση με την επάνω αριστερή γωνία του διαγράμματος. Καλέστε τη μέθοδο IChart.ValidateChartLayout() πριν για να λάβετε τις πραγματικές τιμές. Ανάγνωση float.

**Επιστρέφει:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```


Καθορίζει το πραγματικό πλάτος του στοιχείου διαγράμματος. Καλέστε τη μέθοδο IChart.ValidateChartLayout() πριν για να λάβετε τις πραγματικές τιμές. Ανάγνωση float.

**Επιστρέφει:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```


Καθορίζει το πραγματικό ύψος του στοιχείου διαγράμματος. Καλέστε τη μέθοδο IChart.ValidateChartLayout() πριν για να λάβετε τις πραγματικές τιμές. Ανάγνωση float.

**Επιστρέφει:**
float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Επιστρέφει τη γονική διαφάνεια ενός FillFormat. Μόνο για ανάγνωση [BaseSlide](../../com.aspose.slides/baseslide).

**Επιστρέφει:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Επιστρέφει την γονική παρουσίαση ενός FillFormat. Μόνο για ανάγνωση [IPresentation](../../com.aspose.slides/ipresentation).

**Επιστρέφει:**
[IPresentation](../../com.aspose.slides/ipresentation)