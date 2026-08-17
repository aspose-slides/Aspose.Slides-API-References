---
title: IDataLabelCollection
second_title: Αναφορά API Aspose.Slides για Java
description: Αντιπροσωπεύει τις ετικέτες σειράς.
type: docs
url: /el/com.aspose.slides/idatalabelcollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IDataLabelCollection extends System.Collections.Generic.IGenericEnumerable<IDataLabel>, IChartComponent
```

Αντιπροσωπεύει τις ετικέτες σειράς.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Λαμβάνει την ετικέτα δεδομένων για το σημείο δεδομένων με το συγκεκριμένο δείκτη. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Επιστρέφει τη προεπιλεγμένη μορφοποίηση όλων των ετικετών δεδομένων στη συλλογή. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Αντιπροσωπεύει τη μορφοποίηση γραμμών οδηγού των ετικετών δεδομένων. |
| [isVisible()](#isVisible--) | False σημαίνει ότι η ετικέτα δεδομένων δεν είναι ορατή εξ ορισμού (και έτσι όλες οι σημαίες Show* (ShowValue, ...) της ιδιότητας DefaultDataLabelFormat είναι ψευδείς). |
| [hide()](#hide--) | Κάνει την ετικέτα δεδομένων κρυφή εξ ορισμού ορίζοντας όλες τις σημαίες Show* (ShowValue, ...) της ιδιότητας DefaultDataLabelFormat σε ψευδική κατάσταση. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Λαμβάνει τον αριθμό των ορατών ετικετών δεδομένων στη συλλογή. |
| [getCount()](#getCount--) | Λαμβάνει τον αριθμό όλων των ετικετών δεδομένων στη συλλογή. |
| [getParentSeries()](#getParentSeries--) | Επιστρέφει τη γονική σειρά διαγράμματος. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Επιστρέφει έναν δείκτη της συγκεκριμένης DataLabel στη συλλογή. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```

Λαμβάνει την ετικέτα δεδομένων για το σημείο δεδομένων με το συγκεκριμένο δείκτη.

--------------------

Εναλλακτικός τρόπος πρόσβασης στην ετικέτα δεδομένων είναι: - getSeries().getDataPoints().get_Item(i).getLabel() - διαχείριση ιδιοτήτων ετικέτας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public abstract IDataLabelFormat getDefaultDataLabelFormat()
```

Επιστρέφει τη προεπιλεγμένη μορφοποίηση όλων των ετικετών δεδομένων στη συλλογή. Μόνο για ανάγνωση [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Επιστρέφει:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public abstract IChartLinesFormat getLeaderLinesFormat()
```

Αντιπροσωπεύει τη μορφοποίηση γραμμών οδηγού των ετικετών δεδομένων. Μόνο για ανάγνωση [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False σημαίνει ότι η ετικέτα δεδομένων δεν είναι ορατή εξ ορισμού (και έτσι όλες οι σημαίες Show* (ShowValue, ...) της ιδιότητας DefaultDataLabelFormat είναι ψευδείς). Μόνο για ανάγνωση boolean .

--------------------

Αν η ετικέτα δεδομένων είναι ορατή εξ ορισμού, μπορείτε να την κάνετε κρυφή εξ ορισμού με τη μέθοδο Hide(). Ωστόσο, εάν η ετικέτα δεδομένων δεν είναι ορατή εξ ορισμού (IsVisible είναι false), μπορείτε να την κάνετε «ορατή εξ ορισμού» ορίζοντας τις σημαίες Show* (ShowValue, ...) της ιδιότητας DefaultDataLabelFormat σε κατάσταση true.

**Επιστρέφει:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Κάνει την ετικέτα δεδομένων κρυφή εξ ορισμού ορίζοντας όλες τις σημαίες Show* (ShowValue, ...) της ιδιότητας DefaultDataLabelFormat σε ψευδική κατάσταση. IsVisible θα είναι false μετά από αυτό.

--------------------

Αν η ετικέτα δεδομένων δεν είναι ορατή εξ ορισμού (IsVisible είναι false), μπορείτε να την κάνετε «ορατή εξ ορισμού» ορίζοντας τις σημαίες Show* (ShowValue, ...) της ιδιότητας DefaultDataLabelFormat σε κατάσταση true.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```

Λαμβάνει τον αριθμό των ορατών ετικετών δεδομένων στη συλλογή. Μόνο για ανάγνωση int .

**Επιστρέφει:**
int
### getCount() {#getCount--}
```
public abstract int getCount()
```

Λαμβάνει τον αριθμό όλων των ετικετών δεδομένων στη συλλογή. Μόνο για ανάγνωση int .

**Επιστρέφει:**
int
### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```

Επιστρέφει τη γονική σειρά διαγράμματος. Μόνο για ανάγνωση [IChartSeries](../../com.aspose.slides/ichartseries).

**Επιστρέφει:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public abstract int indexOf(IDataLabel value)
```

Επιστρέφει έναν δείκτη της συγκεκριμένης DataLabel στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel to find. |

**Επιστρέφει:**
int - Index of a DataLabel or -1 if DataLabel not from this collection.