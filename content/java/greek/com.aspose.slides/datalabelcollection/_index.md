---
title: DataLabelCollection
second_title: Aspose.Slides για Java API Αναφορά
description: Αντιπροσωπεύει ετικέτες σειράς.
type: docs
url: /el/com.aspose.slides/datalabelcollection/
---
**Κληρονομία:**
java.lang.Object, com.aspose.slides.DomObject

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
```
public class DataLabelCollection extends DomObject<ChartSeries> implements IDataLabelCollection
```

Αντιπροσωπεύει ετικέτες σειράς.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getChart()](#getChart--) | Επιστρέφει το γονικό διάγραμμα. |
| [iterator()](#iterator--) | Επιστρέφει έναν enumerator που διατρέχει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
| [isVisible()](#isVisible--) | False σημαίνει ότι η ετικέτα δεδομένων δεν είναι ορατή εξ ορισμού (και έτσι όλες οι σημαίες Show*- (ShowValue, ...) της ιδιότητας DefaultDataLabelFormat είναι false). |
| [hide()](#hide--) | Κάντε την ετικέτα δεδομένων κρυφή εξ ορισμού ορίζοντας όλες τις σημαίες Show*- (ShowValue, ...) της ιδιότητας DefaultDataLabelFormat στην κατάσταση false. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Λαμβάνει τον αριθμό των ορατών ετικετών δεδομένων στη συλλογή. |
| [getCount()](#getCount--) | Λαμβάνει τον αριθμό όλων των ετικετών δεδομένων στη συλλογή. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Λαμβάνει τη προεπιλεγμένη μορφή ετικέτας δεδομένων. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Αντιπροσωπεύει τη μορφή γραμμών οδηγού ετικετών δεδομένων. |
| [getParentSeries()](#getParentSeries--) | Λαμβάνει τη γονική σειρά. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Επιστρέφει ένα δείκτη της καθορισμένης DataLabel στη συλλογή. |
| [get_Item(int index)](#get-Item-int-) | Λαμβάνει την ετικέτα δεδομένων για το σημείο δεδομένων με το καθορισμένο δείκτη. |
| [getSlide()](#getSlide--) | Επιστρέφει τη γονική διαφάνεια ενός FillFormat. |
| [getPresentation()](#getPresentation--) | Επιστρέφει την γονική παρουσίαση ενός FillFormat. |
### getChart() {#getChart--}
```
public final IChart getChart()
```


Επιστρέφει το γονικό διάγραμμα. Μόνο για ανάγνωση [IChart](../../com.aspose.slides/ichart).

**Επιστρέφει:**
[IChart](../../com.aspose.slides/ichart)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iterator()
```


Επιστρέφει έναν enumerator που διατρέχει τη συλλογή.

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


False σημαίνει ότι η ετικέτα δεδομένων δεν είναι ορατή εξ ορισμού (και έτσι όλες οι σημαίες Show*- (ShowValue, ...) της ιδιότητας DefaultDataLabelFormat είναι false). Μόνο για ανάγνωση boolean.

--------------------

Αν η ετικέτα δεδομένων είναι ορατή εξ ορισμού, μπορείτε να τη θέσετε κρυφή εξ ορισμού με τη μέθοδο Hide(). Αλλά εάν η ετικέτα δεδομένων δεν είναι ορατή εξ ορισμού (IsVisible είναι false), μπορείτε να κάνετε την ετικέτα δεδομένων «ορατή εξ ορισμού» ορίζοντας τις σημαίες Show*- (ShowValue, ...) της ιδιότητας DefaultDataLabelFormat στην κατάσταση true.

**Επιστρέφει:**
boolean
### hide() {#hide--}
```
public final void hide()
```


Κάντε την ετικέτα δεδομένων κρυφή εξ ορισμού ορίζοντας όλες τις σημαίες Show*- (ShowValue, ...) της ιδιότητας DefaultDataLabelFormat στην κατάσταση false. IsVisible θα είναι false μετά από αυτό.

--------------------

Αν η ετικέτα δεδομένων δεν είναι ορατή εξ ορισμού (IsVisible είναι false), μπορείτε να κάνετε την ετικέτα δεδομένων «ορατή εξ ορισμού» ορίζοντας τις σημαίες Show*- (ShowValue, ...) της ιδιότητας DefaultDataLabelFormat στην κατάσταση true.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public final int getCountOfVisibleDataLabels()
```


Λαμβάνει τον αριθμό των ορατών ετικετών δεδομένων στη συλλογή. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### getCount() {#getCount--}
```
public final int getCount()
```


Λαμβάνει τον αριθμό όλων των ετικετών δεδομένων στη συλλογή. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public final IDataLabelFormat getDefaultDataLabelFormat()
```


Λαμβάνει τη προεπιλεγμένη μορφή ετικέτας δεδομένων. Μόνο για ανάγνωση [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Επιστρέφει:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public final IChartLinesFormat getLeaderLinesFormat()
```


Αντιπροσωπεύει τη μορφή γραμμών οδηγού ετικετών δεδομένων. Μόνο για ανάγνωση [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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


Λαμβάνει τη γονική σειρά. Μόνο για ανάγνωση [IChartSeries](../../com.aspose.slides/ichartseries).

**Επιστρέφει:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public final int indexOf(IDataLabel value)
```


Επιστρέφει ένα δείκτη της καθορισμένης DataLabel στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel προς εύρεση. |

**Επιστρέφει:**
int - Index of a DataLabel or -1 if DataLabel not from this collection.
### get_Item(int index) {#get-Item-int-}
```
public final IDataLabel get_Item(int index)
```


Λαμβάνει την ετικέτα δεδομένων για το σημείο δεδομένων με το καθορισμένο δείκτη.

--------------------

Εναλλακτικός τρόπος πρόσβασης στην ετικέτα δεδομένων είναι: - series.getDataPoints().get_Item(i).getLabel() - διαχείριση ιδιοτήτων ετικέτας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[IDataLabel](../../com.aspose.slides/idatalabel)
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