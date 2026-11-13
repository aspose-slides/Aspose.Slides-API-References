---
title: IChartSeriesGroup
second_title: Aspose.Slides για την αναφορά API της Java
description: Αναπαριστά ομάδα σειρών.
type: docs
url: /el/com.aspose.slides/ichartseriesgroup/
---
**All Implemented Interfaces:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeriesGroup extends IChartComponent
```

Αναπαριστά μια ομάδα σειρών.

--------------------

1) Δείτε την περίληψη και τις παρατηρήσεις για την κλάση ChartSeriesGroupCollection και την απαρίθμηση CombinableSeriesTypesGroup. 2) Η ομάδα σειρών περιέχει ορισμένες ιδιότητες σειρών που είναι κοινές για κάθε σειρά στην ομάδα («ιδιότητες ομάδας σειρών»). Οι «ιδιότητες ομάδας σειρών» στην κλάση ChartSeriesGroup είναι ανάγνωση/εγγραφή. Κάθε μία από τις «ιδιότητες ομάδας σειρών» μπορεί να έχει μια μόνο για ανάγνωση προβολή στην κλάση ChartSeries.

## Methods

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getType()](#getType--) | Επιστρέφει έναν τύπο αυτής της ομάδας σειρών. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Δείχνει αν οι σειρές αυτής της ομάδας σχεδιάζονται σε δευτερεύοντα άξονα. |
| [getSeries()](#getSeries--) | Επιστρέφει μια συλλογή μόνο για ανάγνωση από σειρές γραφήματος. |
| [get_Item(int index)](#get-Item-int-) | Λαμβάνει το στοιχείο στον καθορισμένο δείκτη. |
| [getUpDownBars()](#getUpDownBars--) | Παρέχει πρόσβαση στις μπαρ ανοδικής/καθοδικής γραμμής ή διαγράμματος μετοχών. |
| [getGapWidth()](#getGapWidth--) | Λαμβάνει ή ορίζει το διάστημα μεταξύ των ομάδων μπαρ ή στηλών, ως ποσοστό του πλάτους του μπαρ ή της στήλης. |
| [setGapWidth(int value)](#setGapWidth-int-) | Λαμβάνει ή ορίζει το διάστημα μεταξύ των ομάδων μπαρ ή στηλών, ως ποσοστό του πλάτους του μπαρ ή της στήλης. |
| [getGapDepth()](#getGapDepth--) | Λαμβάνει ή ορίζει την απόσταση μεταξύ των σειρών δεδομένων σε διάγραμμα 3Δ, ως ποσοστό του πλάτους του δείκτη. |
| [setGapDepth(int value)](#setGapDepth-int-) | Λαμβάνει ή ορίζει την απόσταση μεταξύ των σειρών δεδομένων σε διάγραμμα 3Δ, ως ποσοστό του πλάτους του δείκτη. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Λαμβάνει ή ορίζει τη γωνία του πρώτου τμήματος πίτας ή δαχτυλιδιού διαγράμματος, σε μοίρες (δεξιόστροφα από την κορυφή, από 0 έως 360 μοίρες). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Λαμβάνει ή ορίζει τη γωνία του πρώτου τμήματος πίτας ή δαχτυλιδιού διαγράμματος, σε μοίρες (δεξιόστροφα από την κορυφή, από 0 έως 360 μοίρες). |
| [isColorVaried()](#isColorVaried--) | Καθορίζει ότι κάθε δείκτης δεδομένων στη σειρά έχει διαφορετικό χρώμα. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Καθορίζει ότι κάθε δείκτης δεδομένων στη σειρά έχει διαφορετικό χρώμα. |
| [hasSeriesLines()](#hasSeriesLines--) | Αληθές αν το διάγραμμα έχει γραμμές σειράς. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Αληθές αν το διάγραμμα έχει γραμμές σειράς. |
| [getOverlap()](#getOverlap--) | Καθορίζει πόσο θα επικάλυπται τα μπαρ και οι στήλες σε διαγράμματα 2Δ, ως ποσοστό (από -100% έως 100%). |
| [setOverlap(byte value)](#setOverlap-byte-) | Καθορίζει πόσο θα επικάλυπται τα μπαρ και οι στήλες σε διαγράμματα 2Δ, ως ποσοστό (από -100% έως 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Καθορίζει το μέγεθος του δεύτερου τμήματος ή μπαρ ενός διαγράμματος πίτας-σε-πίτα ή μπαρ-σε-πίτα, ως ποσοστό του μεγέθους της πρώτης πίτας (μπορεί να είναι μεταξύ 5 και 200 ποσοστών). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Καθορίζει το μέγεθος του δεύτερου τμήματος ή μπαρ ενός διαγράμματος πίτας-σε-πίτα ή μπαρ-σε-πίτα, ως ποσοστό του μεγέθους της πρώτης πίτας (μπορεί να είναι μεταξύ 5 και 200 ποσοστών). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Καθορίζει μια τιμή η οποία θα χρησιμοποιηθεί για να προσδιοριστεί ποια σημεία δεδομένων βρίσκονται στη δεύτερη πίτα ή μπαρ σε διάγραμμα πίτα-σε-πίτα ή μπαρ-σε-πίτα. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Καθορίζει μια τιμή η οποία θα χρησιμοποιηθεί για να προσδιοριστεί ποια σημεία δεδομένων βρίσκονται στη δεύτερη πίτα ή μπαρ σε διάγραμμα πίτα-σε-πίτα ή μπαρ-σε-πίτα. |
| [getPieSplitBy()](#getPieSplitBy--) | Καθορίζει πώς να προσδιορίζεται ποια σημεία δεδομένων βρίσκονται στη δεύτερη πίτα ή μπαρ σε διάγραμμα πίτα-σε-πίτα ή μπαρ-σε-πίτα. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Καθορίζει πώς να προσδιορίζεται ποια σημεία δεδομένων βρίσκονται στη δεύτερη πίτα ή μπαρ σε διάγραμμα πίτα-σε-πίτα ή μπαρ-σε-πίτα. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Οι προσαρμοσμένες πληροφορίες διαίρεσης για ένα διάγραμμα πίτα-σε-πίτα ή μπαρ-σε-πίτα με προσαρμοσμένη διαίρεση. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Καθορίζει το μέγεθος της τρύπας σε διάγραμμα δαχτυλιδιού (μπορεί να είναι μεταξύ 10 και 90 ποσοστών του μεγέθους της περιοχής σχεδίασης). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Καθορίζει το μέγεθος της τρύπας σε διάγραμμα δαχτυλιδιού (μπορεί να είναι μεταξύ 10 και 90 ποσοστών του μεγέθους της περιοχής σχεδίασης). |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Καθορίζει τον συντελεστή κλίμακας για το διάγραμμα φυσαλίδων (μπορεί να είναι μεταξύ 0 και 300 ποσοστών του προεπιλεγμένου μεγέθους). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Καθορίζει τον συντελεστή κλίμακας για το διάγραμμα φυσαλίδων (μπορεί να είναι μεταξύ 0 και 300 ποσοστών του προεπιλεγμένου μεγέθους). |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Καθορίζει τη μορφή HiLowLines. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Καθορίζει πώς θα αναπαραγώνται οι τιμές μεγέθους φυσαλίδας στο διάγραμμα φυσαλίδων. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Καθορίζει πώς θα αναπαραγώνται οι τιμές μεγέθους φυσαλίδας στο διάγραμμα φυσαλίδων. |

### getType() {#getType--}
```
public abstract int getType()
```

Μηδενίζει έναν τύπο αυτής της ομάδας σειρών. Μόνο για ανάγνωση [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Επιστρέφει:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Δείχνει αν οι σειρές αυτής της ομάδας σχεδιάζονται σε δευτερεύοντα άξονα. Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean

### getSeries() {#getSeries--}
```
public abstract IChartSeriesReadonlyCollection getSeries()
```

Επιστρέφει μια συλλογή μόνο για ανάγνωση από σειρές γραφήματος. Μόνο για ανάγνωση [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Επιστρέφει:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

Λαμβάνει το στοιχείο στον καθορισμένο δείκτη.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public abstract IUpDownBarsManager getUpDownBars()
```

Παρέχει πρόσβαση στις μπαρ ανοδικής/καθοδικής γραμμής ή διαγράμματος μετοχών. Μόνο για ανάγνωση [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Επιστρέφει:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Λαμβάνει ή ορίζει το διάστημα μεταξύ των ομάδων μπαρ ή στηλών, ως ποσοστό του πλάτους του μπαρ ή της στήλης. Η τιμή πρέπει να είναι μεταξύ 0 και 500. Ανάγνωση/εγγραφή int.

--------------------

Αυτή η ιδιότητα ισχύει για σειρές των ακόλουθων τύπων: Όλοι οι υποτύποι μπαρ και στηλών, [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**Επιστρέφει:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

Λαμβάνει ή ορίζει το διάστημα μεταξύ των ομάδων μπαρ ή στηλών, ως ποσοστό του πλάτους του μπαρ ή της στήλης. Η τιμή πρέπει να είναι μεταξύ 0 και 500. Ανάγνωση/εγγραφή int.

--------------------

Αυτή η ιδιότητα ισχύει για σειρές των ακόλουθων τύπων: Όλοι οι υποτύποι μπαρ και στηλών, [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Λαμβάνει ή ορίζει την απόσταση μεταξύ των σειρών δεδομένων σε διάγραμμα 3Δ, ως ποσοστό του πλάτους του δείκτη. Η τιμή πρέπει να είναι μεταξύ 0 και 500. Ανάγνωση/εγγραφή int.

--------------------

Αυτή η ιδιότητα ισχύει για σειρές των ακόλουθων τύπων: Υποτύποι 3Δ μπαρ και στηλών, [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**Επιστρέφει:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

Λαμβάνει ή ορίζει την απόσταση μεταξύ των σειρών δεδομένων σε διάγραμμα 3Δ, ως ποσοστό του πλάτους του δείκτη. Η τιμή πρέπει να είναι μεταξύ 0 και 500. Ανάγνωση/εγγραφή int.

--------------------

Αυτή η ιδιότητα ισχύει για σειρές των ακόλουθων τύπων: Υποτύποι 3Δ μπαρ και στηλών, [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Λαμβάνει ή ορίζει τη γωνία του πρώτου τμήματος πίτας ή δαχτυλιδιού διαγράμματος, σε μοίρες (δεξιόστροφα από την κορυφή, από 0 έως 360 μοίρες). Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

Λαμβάνει ή ορίζει τη γωνία του πρώτου τμήματος πίτας ή δαχτυλιδιού διαγράμματος, σε μοίρες (δεξιόστροφα από την κορυφή, από 0 έως 360 μοίρες). Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Καθορίζει ότι κάθε δείκτης δεδομένων στη σειρά έχει διαφορετικό χρώμα. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public abstract void setColorVaried(boolean value)
```

Καθορίζει ότι κάθε δείκτης δεδομένων στη σειρά έχει διαφορετικό χρώμα. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Αληθές αν το διάγραμμα έχει γραμμές σειράς. Εφαρμόζεται σε στοίβαγμα μπαρ και διαγράμματα OfPie. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

Αληθές αν το διάγραμμα έχει γραμμές σειράς. Εφαρμόζεται σε στοίβαγμα μπαρ και διαγράμματα OfPie. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Καθορίζει πόσο θα επικάλυπται τα μπαρ και οι στήλες σε διαγράμματα 2Δ, ως ποσοστό (από -100% έως 100%). - -100%: Μέγιστη απόσταση (τα μπαρ είναι εντελώς χωρισμένα). - 0%: Τα μπαρ τοποθετούνται δίπλα χωρίς επικάλυψη ή απόσταση. - 100%: Μέγιστη επικάλυψη (τα μπαρ επικάλυπταν πλήρως). Αυτή η ιδιότητα είναι ανάγνωση/εγγραφή byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Ορίστε την επικάλυψη στο 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public abstract void setOverlap(byte value)
```

Καθορίζει πόσο θα επικάλυπται τα μπαρ και οι στήλες σε διαγράμματα 2Δ, ως ποσοστό (από -100% έως 100%). - -100%: Μέγιστη απόσταση (τα μπαρ είναι εντελώς χωρισμένα). - 0%: Τα μπαρ τοποθετούνται δίπλα χωρίς επικάλυψη ή απόσταση. - 100%: Μέγιστη επικάλυψη (τα μπαρ επικάλυπταν πλήρως). Αυτή η ιδιότητα είναι ανάγνωση/εγγραφή byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Ορίστε την επικάλυψη στο 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

Καθορίζει το μέγεθος του δεύτερου τμήματος ή μπαρ ενός διαγράμματος πίτας-σε-πίτα ή μπαρ-σε-πίτα, ως ποσοστό του μεγέθους της πρώτης πίτας (μπορεί να είναι μεταξύ 5 και 200 ποσοστών). Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

Καθορίζει το μέγεθος του δεύτερου τμήματος ή μπαρ ενός διαγράμματος πίτας-σε-πίτα ή μπαρ-σε-πίτα, ως ποσοστό του μεγέθους της πρώτης πίτας (μπορεί να είναι μεταξύ 5 και 200 ποσοστών). Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Καθορίζει μια τιμή η οποία θα χρησιμοποιηθεί για να προσδιοριστεί ποια σημεία δεδομένων βρίσκονται στη δεύτερη πίτα ή μπαρ σε διάγραμμα πίτα-σε-πίτα ή μπαρ-σε-πίτα. Χρησιμοποιείται μαζί με την ιδιότητα PieSplitBy. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

Καθορίζει μια τιμή η οποία θα χρησιμοποιηθεί για να προσδιοριστεί ποια σημεία δεδομένων βρίσκονται στη δεύτερη πίτα ή μπαρ σε διάγραμμα πίτα-σε-πίτα ή μπαρ-σε-πίτα. Χρησιμοποιείται μαζί με την ιδιότητα PieSplitBy. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Καθορίζει πώς να προσδιορίζεται ποια σημεία δεδομένων βρίσκονται στη δεύτερη πίτα ή μπαρ σε διάγραμμα πίτα-σε-πίτα ή μπαρ-σε-πίτα. Ανάγνωση/εγγραφή [PieSplitType](../../com.aspose.slides/piesplittype).

**Επιστρέφει:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

Καθορίζει πώς να προσδιορίζεται ποια σημεία δεδομένων βρίσκονται στη δεύτερη πίτα ή μπαρ σε διάγραμμα πίτα-σε-πίτα ή μπαρ-σε-πίτα. Ανάγνωση/εγγραφή [PieSplitType](../../com.aspose.slides/piesplittype).

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Οι προσαρμοσμένες πληροφορίες διαίρεσης για ένα διάγραμμα πίτα-σε-πίτα ή μπαρ-σε-πίτα με προσαρμοσμένη διαίρεση. Περιέχει σημεία δεδομένων που θα σχεδιαστούν στη δεύτερη πίτα ή μπαρ. Μόνο για ανάγνωση [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

**Επιστρέφει:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Καθορίζει το μέγεθος της τρύπας σε διάγραμμα δαχτυλιδιού (μπορεί να είναι μεταξύ 10 και 90 ποσοστών του μεγέθους της περιοχής σχεδίασης). Ανάγνωση/εγγραφή byte.

**Επιστρέφει:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

Καθορίζει το μέγεθος της τρύπας σε διάγραμμα δαχτυλιδιού (μπορεί να είναι μεταξύ 10 και 90 ποσοστών του μεγέθους της περιοχής σχεδίασης). Ανάγνωση/εγγραφή byte.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Καθορίζει τον συντελεστή κλίμακας για το διάγραμμα φυσαλίδων (μπορεί να είναι μεταξύ 0 και 300 ποσοστών του προεπιλεγμένου μεγέθους). Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

Καθορίζει τον συντελεστή κλίμακας για το διάγραμμα φυσαλίδων (μπορεί να είναι μεταξύ 0 και 300 ποσοστών του προεπιλεγμένου μεγέθους). Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```

Καθορίζει μορφή HiLowLines. HiLowLines εφαρμόζεται με τύπους διαγραμμάτων HiLowClose, OpenHiLowClose, VolumeHiLowClose και VolumeOpenHiLowClose.

**Επιστρέφει:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

Καθορίζει πώς θα αναπαραγώνται οι τιμές μεγέθους φυσαλίδας στο διάγραμμα φυσαλίδων. Ανάγνωση/εγγραφή [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Επιστρέφει:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```

Καθορίζει πώς θα αναπαραγώνται οι τιμές μεγέθους φυσαλίδας στο διάγραμμα φυσαλίδων. Ανάγνωση/εγγραφή [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |