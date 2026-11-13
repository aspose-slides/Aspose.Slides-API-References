---
title: DataLabelCollection
second_title: Aspose.Slides για την αναφορά API Java
description: Αναπαριστά ετικέτες σειράς.
type: docs
url: /el/com.aspose.slides/datalabelcollection/
---
**Κληρονομία:**
java.lang.Object, com.aspose.slides.DomObject

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
```
public class DataLabelCollection extends DomObject<ChartSeries> implements IDataLabelCollection
```

Αναπαριστά ετικέτες σειράς.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getChart()](#getChart--) | Επιστρέφει το γονικό γράφημα. |
| [iterator()](#iterator--) | Επιστρέφει έναν απαριθμητή που διατρέχει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
| [isVisible()](#isVisible--) | False σημαίνει ότι η ετικέτα δεδομένων δεν είναι ορατή από προεπιλογή (και έτσι όλες οι Show\*-flags (ShowValue, ...) της ιδιότητας DefaultDataLabelFormat είναι false). |
| [hide()](#hide--) | Κάντε την ετικέτα δεδομένων κρυφή από προεπιλογή ορίζοντας όλες τις Show\*-flags (ShowValue, ...) της ιδιότητας DefaultDataLabelFormat σε κατάσταση false. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Αποκτά τον αριθμό των ορατών ετικετών δεδομένων στη συλλογή. |
| [getCount()](#getCount--) | Αποκτά τον αριθμό όλων των ετικετών δεδομένων στη συλλογή. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Αποκτά τη προεπιλεγμένη μορφή ετικέτας δεδομένων. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Αναπαριστά τη μορφή γραμμών οδηγού ετικετών δεδομένων. |
| [getParentSeries()](#getParentSeries--) | Αποκτά τη γονική σειρά. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Επιστρέφει έναν δείκτη της καθορισμένης DataLabel στη συλλογή. |
| [get_Item(int index)](#get-Item-int-) | Αποκτά την ετικέτα δεδομένων για το σημείο δεδομένων με τον καθορισμένο δείκτη. |
| [getDefaultLabelShapeType()](#getDefaultLabelShapeType--) | Αποκτά ή ορίζει τον προεπιλεγμένο τύπο σχήματος για τις ετικέτες δεδομένων. |
| [setDefaultLabelShapeType(int value)](#setDefaultLabelShapeType-int-) | Αποκτά ή ορίζει τον προεπιλεγμένο τύπο σχήματος για τις ετικέτες δεδομένων. |
| [getSlide()](#getSlide--) | Επιστρέφει τη γονική διαφάνεια ενός FillFormat. |
| [getPresentation()](#getPresentation--) | Επιστρέφει την γονική παρουσίαση ενός FillFormat. |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Επιστρέφει το γονικό γράφημα. Μόνο για ανάγνωση [IChart](../../com.aspose.slides/ichart).

**Επιστρέφει:**
[IChart](../../com.aspose.slides/ichart)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iterator()
```

Επιστρέφει έναν απαριθμητή που διατρέχει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iteratorJava()
```

Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - An java.util.Iterator for the entire collection.
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False σημαίνει ότι η ετικέτα δεδομένων δεν είναι ορατή από προεπιλογή (και έτσι όλες οι Show\*-flags (ShowValue, ...) της ιδιότητας DefaultDataLabelFormat είναι false). Μόνο για ανάγνωση boolean.

--------------------

Αν η ετικέτα δεδομένων είναι ορατή από προεπιλογή, μπορείτε να την κρύψετε από προεπιλογή με τη μέθοδο Hide(). Αλλά αν η ετικέτα δεδομένων δεν είναι ορατή από προεπιλογή (IsVisible είναι false), μπορείτε να κάνετε την ετικέτα δεδομένων «ορατή από προεπιλογή» ορίζοντας τις Show\*-flags (ShowValue, ...) της ιδιότητας DefaultDataLabelFormat σε κατάσταση true.

**Επιστρέφει:**
boolean
### hide() {#hide--}
```
public final void hide()
```

Κάντε την ετικέτα δεδομένων κρυφή από προεπιλογή ορίζοντας όλες τις Show\*-flags (ShowValue, ...) της ιδιότητας DefaultDataLabelFormat σε κατάσταση false. IsVisible will be false after this.

--------------------

Αν η ετικέτα δεδομένων δεν είναι ορατή από προεπιλογή (IsVisible είναι false), μπορείτε να κάνετε την ετικέτα δεδομένων «ορατή από προεπιλογή» ορίζοντας τις Show\*-flags (ShowValue, ...) της ιδιότητας DefaultDataLabelFormat σε κατάσταση true.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public final int getCountOfVisibleDataLabels()
```

Αποκτά τον αριθμό των ορατών ετικετών δεδομένων στη συλλογή. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### getCount() {#getCount--}
```
public final int getCount()
```

Αποκτά τον αριθμό όλων των ετικετών δεδομένων στη συλλογή. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public final IDataLabelFormat getDefaultDataLabelFormat()
```

Αποκτά τη προεπιλεγμένη μορφή ετικέτας δεδομένων. Μόνο για ανάγνωση [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Επιστρέφει:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public final IChartLinesFormat getLeaderLinesFormat()
```

Αναπαριστά τη μορφή γραμμών οδηγού ετικετών δεδομένων. Μόνο για ανάγνωση [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IChart chart = (IChart) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      IDataLabelCollection labels = series.get_Item(0).getLabels();
>      labels.getLeaderLinesFormat().getLine().getFillFormat().setFillType(FillType.Solid);
>      labels.getLeaderLinesFormat().getLine().getFillFormat().getSolidFillColor().setColor(new java.awt.Color(255, 0, 0, 255));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getParentSeries() {#getParentSeries--}
```
public final IChartSeries getParentSeries()
```

Αποκτά τη γονική σειρά. Μόνο για ανάγνωση [IChartSeries](../../com.aspose.slides/ichartseries).

**Επιστρέφει:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public final int indexOf(IDataLabel value)
```

Επιστρέφει έναν δείκτη της καθορισμένης DataLabel στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | Η DataLabel προς εύρεση. |

**Επιστρέφει:**
int - Index of a DataLabel or -1 if DataLabel not from this collection.
### get_Item(int index) {#get-Item-int-}
```
public final IDataLabel get_Item(int index)
```

Αποκτά την ετικέτα δεδομένων για το σημείο δεδομένων με τον καθορισμένο δείκτη.

--------------------

Εναλλακτικός τρόπος πρόσβασης στην ετικέτα δεδομένων είναι: - series.getDataPoints().get_Item(i).getLabel() - manage label properties.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getDefaultLabelShapeType() {#getDefaultLabelShapeType--}
```
public final int getDefaultLabelShapeType()
```

Αποκτά ή ορίζει τον προεπιλεγμένο τύπο σχήματος για τις ετικέτες δεδομένων. Επιστρέφει [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) εάν δεν έχει οριστεί σχήμα.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Ορίστε τον τύπο σχήματος όλων των ετικετών δεδομένων στην πρώτη σειρά σε Ellipse.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Η ρύθμιση αυτής της ιδιότητας ορίζει επίσης την ιδιότητα IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) για όλες τις ετικέτες δεδομένων στη συλλογή στην ίδια τιμή.

**Επιστρέφει:**
int
### setDefaultLabelShapeType(int value) {#setDefaultLabelShapeType-int-}
```
public final void setDefaultLabelShapeType(int value)
```

Αποκτά ή ορίζει τον προεπιλεγμένο τύπο σχήματος για τις ετικέτες δεδομένων. Επιστρέφει [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) εάν δεν έχει οριστεί σχήμα.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Ορίστε τον τύπο σχήματος όλων των ετικετών δεδομένων στην πρώτη σειρά σε Ellipse.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Η ρύθμιση αυτής της ιδιότητας ορίζει επίσης την ιδιότητα IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) για όλες τις ετικέτες δεδομένων στη συλλογή στην ίδια τιμή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

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