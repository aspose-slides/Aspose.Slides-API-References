---
title: IDataLabelCollection
second_title: Aspose.Slides για Android μέσω Αναφοράς Java API
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
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Λαμβάνει την ετικέτα δεδομένων για το σημείο δεδομένων με το καθορισμένο ευρετήριο. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Επιστρέφει την προεπιλεγμένη μορφή όλων των ετικετών δεδομένων στη συλλογή. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Αντιπροσωπεύει τη μορφή των γραμμών οδηγού των ετικετών δεδομένων. |
| [isVisible()](#isVisible--) | False σημαίνει ότι η ετικέτα δεδομένων δεν είναι ορατή από προεπιλογή (και έτσι όλες οι σημαίες Show* (ShowValue, ...) της ιδιότητας DefaultDataLabelFormat είναι false). |
| [hide()](#hide--) | Κάνει την ετικέτα δεδομένων κρυφή από προεπιλογή ορίζοντας όλες τις σημαίες Show* (ShowValue, ...) της ιδιότητας DefaultDataLabelFormat σε κατάσταση false. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Λαμβάνει τον αριθμό των ορατών ετικετών δεδομένων στη συλλογή. |
| [getCount()](#getCount--) | Λαμβάνει τον αριθμό όλων των ετικετών δεδομένων στη συλλογή. |
| [getParentSeries()](#getParentSeries--) | Επιστρέφει τη γονική σειρά διαγράμματος. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Επιστρέφει το ευρετήριο της καθορισμένης DataLabel στη συλλογή. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```


Λαμβάνει την ετικέτα δεδομένων για το σημείο δεδομένων με το καθορισμένο ευρετήριο.

--------------------

Εναλλακτικός τρόπος πρόσβασης στην ετικέτα δεδομένων είναι:
- getSeries().getDataPoints().get_Item(i).getLabel()
- διαχείριση ιδιοτήτων ετικέτας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστροφή:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public abstract IDataLabelFormat getDefaultDataLabelFormat()
```


Επιστρέφει την προεπιλεγμένη μορφή όλων των ετικετών δεδομένων στη συλλογή. Μόνο για ανάγνωση [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Επιστροφή:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public abstract IChartLinesFormat getLeaderLinesFormat()
```


Αντιπροσωπεύει τη μορφή των γραμμών οδηγού των ετικετών δεδομένων. Μόνο για ανάγνωση [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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
>      labels.getLeaderLinesFormat().getLine().getFillFormat().getSolidFillColor().setColor(Color.RED);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστροφή:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


False σημαίνει ότι η ετικέτα δεδομένων δεν είναι ορατή από προεπιλογή (και έτσι όλες οι σημαίες Show* (ShowValue, ...) της ιδιότητας DefaultDataLabelFormat είναι false). Μόνο για ανάγνωση boolean.

Εάν η ετικέτα δεδομένων είναι ορατή από προεπιλογή, μπορείτε να την κάνετε κρυφή από προεπιλογή με τη μέθοδο Hide(). Ωστόσο, εάν η ετικέτα δεδομένων δεν είναι ορατή από προεπιλογή (IsVisible είναι false), μπορείτε να κάνετε την ετικέτα "ορατή από προεπιλογή" ορίζοντας τις σημαίες Show* (ShowValue, ...) της ιδιότητας DefaultDataLabelFormat σε κατάσταση true.

**Επιστροφή:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```


Κάνει την ετικέτα δεδομένων κρυφή από προεπιλογή ορίζοντας όλες τις σημαίες Show* (ShowValue, ...) της ιδιότητας DefaultDataLabelFormat σε κατάσταση false. Η IsVisible θα είναι false μετά από αυτό.

Εάν η ετικέτα δεδομένων δεν είναι ορατή από προεπιλογή (IsVisible είναι false), μπορείτε να κάνετε την ετικέτα "ορατή από προεπιλογή" ορίζοντας τις σημαίες Show* (ShowValue, ...) της ιδιότητας DefaultDataLabelFormat σε κατάσταση true.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```


Λαμβάνει τον αριθμό των ορατών ετικετών δεδομένων στη συλλογή. Μόνο για ανάγνωση int.

**Επιστροφή:**
int
### getCount() {#getCount--}
```
public abstract int getCount()
```


Λαμβάνει τον αριθμό όλων των ετικετών δεδομένων στη συλλογή. Μόνο για ανάγνωση int.

**Επιστροφή:**
int
### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```


Επιστρέφει τη γονική σειρά διαγράμματος. Μόνο για ανάγνωση [IChartSeries](../../com.aspose.slides/ichartseries).

**Επιστροφή:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public abstract int indexOf(IDataLabel value)
```


Επιστρέφει το ευρετήριο της καθορισμένης DataLabel στη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel προς εύρεση. |

**Επιστροφή:**
int - Το ευρετήριο μιας DataLabel ή -1 εάν η DataLabel δεν προέρχεται από αυτή τη συλλογή.