---
title: IDataLabelCollection
second_title: Aspose.Slides για την αναφορά API της Java
description: Αντιπροσωπεύει ετικέτες σειράς.
type: docs
url: /el/com.aspose.slides/idatalabelcollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IDataLabelCollection extends System.Collections.Generic.IGenericEnumerable<IDataLabel>, IChartComponent
```

Αντιπροσωπεύει ετικέτες σειράς.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Λαμβάνει την ετικέτα δεδομένων για το σημείο δεδομένων με τον καθορισμένο δείκτη. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Επιστρέφει την προεπιλεγμένη μορφή όλων των ετικετών δεδομένων στη συλλογή. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Αντιπροσωπεύει τη μορφή των γραμμών οδηγών ετικετών δεδομένων. |
| [isVisible()](#isVisible--) | False σημαίνει ότι η ετικέτα δεδομένων δεν είναι ορατή εξ ορισμού (και έτσι όλες οι σημαίες Show*-flags (ShowValue, ...) της ιδιότητας DefaultDataLabelFormat είναι false). |
| [hide()](#hide--) | Κάντε την ετικέτα δεδομένων κρυφή εξ ορισμού ορίζοντας όλες τις σημαίες Show*-flags (ShowValue, ...) της ιδιότητας DefaultDataLabelFormat σε κατάσταση false. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Λαμβάνει τον αριθμό των ορατών ετικετών δεδομένων στη συλλογή. |
| [getCount()](#getCount--) | Λαμβάνει τον αριθμό όλων των ετικετών δεδομένων στη συλλογή. |
| [getParentSeries()](#getParentSeries--) | Επιστρέφει τη γονική σειρά διαγράμματος. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Επιστρέφει το δείκτη της συγκεκριμένης DataLabel στη συλλογή. |
| [getDefaultLabelShapeType()](#getDefaultLabelShapeType--) | Λαμβάνει ή ορίζει τον προεπιλεγμένο τύπο σχήματος για τις ετικέτες δεδομένων. |
| [setDefaultLabelShapeType(int value)](#setDefaultLabelShapeType-int-) | Λαμβάνει ή ορίζει τον προεπιλεγμένο τύπο σχήματος για τις ετικέτες δεδομένων. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```

Λαμβάνει την ετικέτα δεδομένων για το σημείο δεδομένων με τον καθορισμένο δείκτη.

--------------------

Εναλλακτικός τρόπος πρόσβασης στην ετικέτα δεδομένων είναι:
- getSeries().getDataPoints().get_Item(i).getLabel()
- manage label properties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public abstract IDataLabelFormat getDefaultDataLabelFormat()
```

Επιστρέφει την προεπιλεγμένη μορφή όλων των ετικετών δεδομένων στη συλλογή. Μόνο για ανάγνωση [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Returns:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public abstract IChartLinesFormat getLeaderLinesFormat()
```

Αντιπροσωπεύει τη μορφή των γραμμών οδηγών ετικετών δεδομένων. Μόνο για ανάγνωση [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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


**Returns:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False σημαίνει ότι η ετικέτα δεδομένων δεν είναι ορατή εξ ορισμού (και έτσι όλες οι σημαίες Show*-flags (ShowValue, ...) της ιδιότητας DefaultDataLabelFormat είναι false). Μόνο για ανάγνωση boolean.

--------------------

Αν η ετικέτα δεδομένων είναι ορατή εξ ορισμού, μπορείτε να την κρύψετε εξ ορισμού με τη μέθοδο Hide(). Αν η ετικέτα δεδομένων δεν είναι ορατή εξ ορισμού (IsVisible είναι false), μπορείτε να την κάνετε «ορατή εξ ορισμού» ορίζοντας τις σημαίες Show*-flags (ShowValue, ...) της ιδιότητας DefaultDataLabelFormat σε κατάσταση true.

**Returns:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Κάνει την ετικέτα δεδομένων κρυφή εξ ορισμού ορίζοντας όλες τις σημαίες Show*-flags (ShowValue, ...) της ιδιότητας DefaultDataLabelFormat σε κατάσταση false. IsVisible θα είναι false μετά από αυτό.

--------------------

Αν η ετικέτα δεδομένων δεν είναι ορατή εξ ορισμού (IsVisible είναι false), μπορείτε να την κάνετε «ορατή εξ ορισμού» ορίζοντας τις σημαίες Show*-flags (ShowValue, ...) της ιδιότητας DefaultDataLabelFormat σε κατάσταση true.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```

Λαμβάνει τον αριθμό των ορατών ετικετών δεδομένων στη συλλογή. Μόνο για ανάγνωση int.

**Returns:**
int
### getCount() {#getCount--}
```
public abstract int getCount()
```

Λαμβάνει τον αριθμό όλων των ετικετών δεδομένων στη συλλογή. Μόνο για ανάγνωση int.

**Returns:**
int
### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```

Επιστρέφει τη γονική σειρά διαγράμματος. Μόνο για ανάγνωση [IChartSeries](../../com.aspose.slides/ichartseries).

**Returns:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public abstract int indexOf(IDataLabel value)
```

Επιστρέφει το δείκτη της συγκεκριμένης DataLabel στη συλλογή.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel to find. |

**Returns:**
int - Δείκτης μιας DataLabel ή -1 αν η DataLabel δεν προέρχεται από αυτή τη συλλογή.
### getDefaultLabelShapeType() {#getDefaultLabelShapeType--}
```
public abstract int getDefaultLabelShapeType()
```

Λαμβάνει ή ορίζει τον προεπιλεγμένο τύπο σχήματος για τις ετικέτες δεδομένων. Επιστρέφει [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) αν δεν έχει οριστεί σχήμα.

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

Ο καθορισμός αυτής της ιδιότητας ορίζει επίσης την ιδιότητα IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) για όλες τις ετικέτες δεδομένων στη συλλογή στην ίδια τιμή.

**Returns:**
int
### setDefaultLabelShapeType(int value) {#setDefaultLabelShapeType-int-}
```
public abstract void setDefaultLabelShapeType(int value)
```

Λαμβάνει ή ορίζει τον προεπιλεγμένο τύπο σχήματος για τις ετικέτες δεδομένων. Επιστρέφει [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) αν δεν έχει οριστεί σχήμα.

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

Ο καθορισμός αυτής της ιδιότητας ορίζει επίσης την ιδιότητα IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) για όλες τις ετικέτες δεδομένων στη συλλογή στην ίδια τιμή.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |