---
title: ChartSeriesGroup
second_title: Aspose.Slides για την Αναφορά API Java
description: Αντιπροσωπεύει την ομάδα σειρών.
type: docs
url: /el/com.aspose.slides/chartseriesgroup/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup), com.aspose.slides.IDOMObject
```
public class ChartSeriesGroup implements IChartSeriesGroup, IDOMObject
```

Αντιπροσωπεύει την ομάδα σειρών.

--------------------

1) Δείτε τη σύνοψη και τα σχόλια για την κλάση ChartSeriesGroupCollection και το enum CombinableSeriesTypesGroup. 2) Η ομάδα σειρών περιέχει ορισμένες ιδιότητες σειρών που είναι κοινές για κάθε σειρά στην ομάδα («series group properties»). Οι «Series group properties» στην κλάση ChartSeriesGroup είναι ανάγνωση/εγγραφή. Κάθε «Series group properties» μπορεί να έχει μια μόνο για ανάγνωση προβολή στην κλάση ChartSeries.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getType()](#getType--) | Επιστρέφει έναν τύπο αυτής της ομάδας σειρών. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Δείχνει εάν οι σειρές αυτής της ομάδας απεικονίζονται σε δευτερεύον άξονα. |
| [getSeries()](#getSeries--) | Επιστρέφει μια συλλογή σειρών. |
| [get_Item(int index)](#get-Item-int-) | Λαμβάνει το στοιχείο στο συγκεκριμένο δείκτη. |
| [getUpDownBars()](#getUpDownBars--) | Παρέχει πρόσβαση σε γραμμές πάνω/κάτω σε γράφημα γραμμής ή αποθέματος. |
| [getGapWidth()](#getGapWidth--) | Καθορίζει το κενό μεταξύ ομάδων ψηφίων ή στηλών, ως ποσοστό του πλάτους του ψηφίου ή της στήλης. |
| [setGapWidth(int value)](#setGapWidth-int-) | Καθορίζει το κενό μεταξύ ομάδων ψηφίων ή στηλών, ως ποσοστό του πλάτους του ψηφίου ή της στήλης. |
| [getGapDepth()](#getGapDepth--) | Επιστρέφει ή ορίζει την απόσταση, ως ποσοστό του πλάτους του δείκτη, μεταξύ των σειρών δεδομένων σε 3Δ γράφημα. |
| [setGapDepth(int value)](#setGapDepth-int-) | Επιστρέφει ή ορίζει την απόσταση, ως ποσοστό του πλάτους του δείκτη, μεταξύ των σειρών δεδομένων σε 3Δ γράφημα. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Λαμβάνει ή ορίζει τη γωνία του πρώτου κομματιού πίτας ή δακτυλίου σε μοίρες (δεξιόστροφα από πάνω, από 0 έως 360 μοίρες). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Λαμβάνει ή ορίζει τη γωνία του πρώτου κομματιού πίτας ή δακτυλίου σε μοίρες (δεξιόστροφα από πάνω, από 0 έως 360 μοίρες). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Καθορίζει το μέγεθος της τρύπας σε γράφημα δακτυλίου (μπορεί να είναι μεταξύ 0 και 90 τοις εκατό του μεγέθους της περιοχής σχεδίασης). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Καθορίζει το μέγεθος της τρύπας σε γράφημα δακτυλίου (μπορεί να είναι μεταξύ 0 και 90 τοις εκατό του μεγέθους της περιοχής σχεδίασης). |
| [getOverlap()](#getOverlap--) | Καθορίζει πόσο πρέπει να επικαλύπτονται τα ψηφία και οι στήλες σε 2Δ γραφήματα, ως ποσοστό (από -100% έως 100%). |
| [setOverlap(byte value)](#setOverlap-byte-) | Καθορίζει πόσο πρέπει να επικαλύπτονται τα ψηφία και οι στήλες σε 2Δ γραφήματα, ως ποσοστό (από -100% έως 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Καθορίζει το μέγεθος της δεύτερης πίτας ή μπάρου ενός γραφήματος πίτας-μέσα-πίτας ή μπάρου-μέσα-πίτας, ως ποσοστό του μεγέθους της πρώτης πίτας (μπορεί να είναι μεταξύ 5 και 200 τοις εκατό). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Καθορίζει το μέγεθος της δεύτερης πίτας ή μπάρου ενός γραφήματος πίτας-μέσα-πίτας ή μπάρου-μέσα-πίτας, ως ποσοστό του μεγέθους της πρώτης πίτας (μπορεί να είναι μεταξύ 5 και 200 τοις εκατό). |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Καθορίζει πώς οι τιμές μεγέθους φυσαλίδας εμφανίζονται στο γράφημα φυσαλίδων. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Καθορίζει πώς οι τιμές μεγέθους φυσαλίδας εμφανίζονται στο γράφημα φυσαλίδων. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Καθορίζει μια τιμή που θα χρησιμοποιηθεί για να προσδιορίσει ποια σημεία δεδομένων βρίσκονται στη δεύτερη πίτα ή μπάρα σε γράφημα πίτας-μέσα-πίτας ή μπάρα-μέσα-πίτας. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Καθορίζει μια τιμή που θα χρησιμοποιηθεί για να προσδιορίσει ποια σημεία δεδομένων βρίσκονται στη δεύτερη πίτα ή μπάρα σε γράφημα πίτας-μέσα-πίτας ή μπάρα-μέσα-πίτας. |
| [getPieSplitBy()](#getPieSplitBy--) | Καθορίζει πώς να προσδιοριστεί ποια σημεία δεδομένων ανήκουν στη δεύτερη πίτα ή μπάρα σε γράφημα πίτας-μέσα-πίτας ή μπάρα-μέσα-πίτας. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Καθορίζει πώς να προσδιοριστεί ποια σημεία δεδομένων ανήκουν στη δεύτερη πίτα ή μπάρα σε γράφημα πίτας-μέσα-πίτας ή μπάρα-μέσα-πίτας. |
| [isColorVaried()](#isColorVaried--) | Καθορίζει ότι κάθε δείκτης δεδομένων στη σειρά έχει διαφορετικό χρώμα. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Καθορίζει ότι κάθε δείκτης δεδομένων στη σειρά έχει διαφορετικό χρώμα. |
| [hasSeriesLines()](#hasSeriesLines--) | Αληθές εάν το γράφημα έχει γραμμές σειράς. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Αληθές εάν το γράφημα έχει γραμμές σειράς. |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Καθορίζει τη μορφή HiLowLines. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Καθορίζει τον συντελεστή κλίμακας για το γράφημα φυσαλίδων (μπορεί να είναι μεταξύ 0 και 300 τοις εκατό του προεπιλεγμένου μεγέθους). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Καθορίζει τον συντελεστή κλίμακας για το γράφημα φυσαλίδων (μπορεί να είναι μεταξύ 0 και 300 τοις εκατό του προεπιλεγμένου μεγέθους). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Οι προσαρμοσμένες πληροφορίες διαίρεσης για ένα γράφημα πίτας-μέσα-πίτας ή μπάρα-μέσα-πιτας με προσαρμοσμένη διαίρεση. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Επιστρέφει το γονικό γράφημα. |
| [getSlide()](#getSlide--) | Επιστρέφει τη γονική διαφάνεια ενός FillFormat. |
| [getPresentation()](#getPresentation--) | Επιστρέφει την γονική παρουσίαση ενός FillFormat. |

### getType() {#getType--}
```
public final int getType()
```

Επιστρέφει έναν τύπο αυτής της ομάδας σειρών. Μόνο για ανάγνωση [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Επιστρέφει:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

Δείχνει εάν οι σειρές αυτής της ομάδας απεικονίζονται σε δευτερεύον άξονα. Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean

### getSeries() {#getSeries--}
```
public final IChartSeriesReadonlyCollection getSeries()
```

Επιστρέφει μια συλλογή σειρών. Μόνο για ανάγνωση [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Επιστρέφει:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

Λαμβάνει το στοιχείο στο συγκεκριμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public final IUpDownBarsManager getUpDownBars()
```

Παρέχει πρόσβαση σε γραμμές πάνω/κάτω σε γράφημα γραμμής ή αποθέματος. Μόνο για ανάγνωση [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Επιστρέφει:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Καθορίζει το κενό μεταξύ ομάδων ψηφίων ή στηλών, ως ποσοστό του πλάτους του ψηφίου ή της στήλης. Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

Καθορίζει το κενό μεταξύ ομάδων ψηφίων ή στηλών, ως ποσοστό του πλάτους του ψηφίου ή της στήλης. Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Επιστρέφει ή ορίζει την απόσταση, ως ποσοστό του πλάτους του δείκτη, μεταξύ των σειρών δεδομένων σε 3Δ γράφημα. Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

Επιστρέφει ή ορίζει την απόσταση, ως ποσοστό του πλάτους του δείκτη, μεταξύ των σειρών δεδομένων σε 3Δ γράφημα. Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Λαμβάνει ή ορίζει τη γωνία του πρώτου κομματιού πίτας ή δακτυλίου σε μοίρες (δεξιόστροφα από πάνω, από 0 έως 360 μοίρες). Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

Λαμβάνει ή ορίζει τη γωνία του πρώτου κομματιού πίτας ή δακτυλίου σε μοίρες (δεξιόστροφα από πάνω, από 0 έως 360 μοίρες). Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Καθορίζει το μέγεθος της τρύπας σε γράφημα δακτυλίου (μπορεί να είναι μεταξύ 0 και 90 τοις εκατό του μεγέθους της περιοχής σχεδίασης). Ανάγνωση/εγγραφή byte.

**Επιστρέφει:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```

Καθορίζει το μέγεθος της τρύπας σε γράφημα δακτυλίου (μπορεί να είναι μεταξύ 0 και 90 τοις εκατό του μεγέθους της περιοχής σχεδίασης). Ανάγνωση/εγγραφή byte.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Καθορίζει πόσο πρέπει να επικαλύπτονται τα ψηφία και οι στήλες σε 2Δ γραφήματα, ως ποσοστό (από -100% έως 100%). - -100%: Μέγιστο κενό (τα ψηφία είναι εντελώς χωρισμένα). - 0%: Τα ψηφία τοποθετούνται δίπλα-δίπλα χωρίς επικαλύψεις ή κενά. - 100%: Μέγιστη επικάλυψη (τα ψηφία επικαλύπτονται πλήρως μεταξύ τους). Αυτή η ιδιότητα είναι ανάγνωση/εγγραφή byte.

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


**Επιστρέφει:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public final void setOverlap(byte value)
```

Καθορίζει πόσο πρέπει να επικαλύπτονται τα ψηφία και οι στήλες σε 2Δ γραφήματα, ως ποσοστό (από -100% έως 100%). - -100%: Μέγιστο κενό (τα ψηφία είναι εντελώς χωρισμένα). - 0%: Τα ψηφία τοποθετούνται δίπλα-δίπλα χωρίς επικαλύψεις ή κενά. - 100%: Μέγιστη επικάλυψη (τα ψηφία επικαλύπτονται πλήρως μεταξύ τους). Αυτή η ιδιότητα είναι ανάγνωση/εγγραφή byte.

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

Καθορίζει το μέγεθος της δεύτερης πίτας ή μπάρου ενός γραφήματος πίτας-μέσα-πίτας ή μπάρου-μέσα-πίτας, ως ποσοστό του μεγέθους της πρώτης πίτας (μπορεί να είναι μεταξύ 5 και 200 τοις εκατό). Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

Καθορίζει το μέγεθος της δεύτερης πίτας ή μπάρου ενός γραφήματος πίτας-μέσα-πίτας ή μπάρου-μέσα-πίτας, ως ποσοστό του μεγέθους της πρώτης πίτας (μπορεί να είναι μεταξύ 5 και 200 τοις εκατό). Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Καθορίζει πώς οι τιμές μεγέθους φυσαλίδας εμφανίζονται στο γράφημα φυσαλίδων. Ανάγνωση/εγγραφή [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Επιστρέφει:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```

Καθορίζει πώς οι τιμές μεγέθους φυσαλίδας εμφανίζονται στο γράφημα φυσαλίδων. Ανάγνωση/εγγραφή [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Καθορίζει μια τιμή που θα χρησιμοποιηθεί για να προσδιορίσει ποια σημεία δεδομένων βρίσκονται στη δεύτερη πίτα ή μπάρα σε γράφημα πίτας-μέσα-πίτας ή μπάρα-μέσα-πίτας. Χρησιμοποιείται μαζί με την ιδιότητα PieSplitBy. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

Καθορίζει μια τιμή που θα χρησιμοποιηθεί για να προσδιορίσει ποια σημεία δεδομένων βρίσκονται στη δεύτερη πίτα ή μπάρα σε γράφημα πίτας-μέσα-πίτας ή μπάρα-μέσα-πίτας. Χρησιμοποιείται μαζί με την ιδιότητα PieSplitBy. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Καθορίζει πώς να προσδιοριστεί ποια σημεία δεδομένων ανήκουν στη δεύτερη πίτα ή μπάρα σε γράφημα πίτας-μέσα-πίτας ή μπάρα-μέσα-πίτας. Ανάγνωση/εγγραφή [PieSplitType](../../com.aspose.slides/piesplittype).

**Επιστρέφει:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

Καθορίζει πώς να προσδιοριστεί ποια σημεία δεδομένων ανήκουν στη δεύτερη πίτα ή μπάρα σε γράφημα πίτας-μέσα-πίτας ή μπάρα-μέσα-πίτας. Ανάγνωση/εγγραφή [PieSplitType](../../com.aspose.slides/piesplittype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

Καθορίζει ότι κάθε δείκτης δεδομένων στη σειρά έχει διαφορετικό χρώμα. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```

Καθορίζει ότι κάθε δείκτης δεδομένων στη σειρά έχει διαφορετικό χρώμα. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

Αληθές εάν το γράφημα έχει γραμμές σειράς. Εφαρμόζεται σε στοιβαγμένα μπάρες και γραφήματα OfPie. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```

Αληθές εάν το γράφημα έχει γραμμές σειράς. Εφαρμόζεται σε στοιβαγμένα μπάρες και γραφήματα OfPie. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```

Καθορίζει τη μορφή HiLowLines. HiLowLines εφαρμόζεται με τους τύπους γραφημάτων HiLowClose, OpenHiLowClose, VolumeHiLowClose και VolumeOpenHiLowClose.

**Επιστρέφει:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Καθορίζει τον συντελεστή κλίμακας για το γράφημα φυσαλίδων (μπορεί να είναι μεταξύ 0 και 300 τοις εκατό του προεπιλεγμένου μεγέθους). Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```

Καθορίζει τον συντελεστή κλίμακας για το γράφημα φυσαλίδων (μπορεί να είναι μεταξύ 0 και 300 τοις εκατό του προεπιλεγμένου μεγέθους). Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Οι προσαρμοσμένες πληροφορίες διαίρεσης για ένα γράφημα πίτας-μέσα-πίτας ή μπάρα-μέσα-πίτας με προσαρμοσμένη διαίρεση. Περιέχει σημεία δεδομένων που θα σχεδιαστούν στη δεύτερη πίτα ή μπάρα. Μόνο για ανάγνωση [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

**Επιστρέφει:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Επιστρέφει το αντικείμενο Parent_Immediate. Μόνο για ανάγνωση IDOMObject.

**Επιστρέφει:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

Επιστρέφει το γονικό γράφημα. Μόνο για ανάγνωση [IChart](../../com.aspose.slides/ichart).

**Επιστρέφει:**
[IChart](../../com.aspose.slides/ichart)

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