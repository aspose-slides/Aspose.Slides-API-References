---
title: IChartSeriesGroup
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Αναπαριστά ομάδα σειρών.
type: docs
url: /el/com.aspose.slides/ichartseriesgroup/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeriesGroup extends IChartComponent
```

Αναπαριστά ομάδα σειρών.

--------------------

1) Δείτε τη σύνοψη και τις παρατηρήσεις για την κλάση ChartSeriesGroupCollection και το enum CombinableSeriesTypesGroup. 2) Η ομάδα σειρών περιέχει μερικές ιδιότητες σειράς που είναι κοινές για κάθε σειρά στην ομάδα ("series group properties"). "Series group properties" στην κλάση ChartSeriesGroup είναι ανάγνωση/εγγραφή. Κάθε "series group properties" μπορεί να έχει μια ανάγνωση-μόνο προβολή στην κλάση ChartSeries.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getType()](#getType--) | Επιστρέφει έναν τύπο αυτής της ομάδας σειράς. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Δείχνει αν οι σειρές αυτής της ομάδας σχεδιάζονται σε δευτερεύοντα άξονα. |
| [getSeries()](#getSeries--) | Επιστρέφει μια συλλογή μόνο για ανάγνωση από σειρές διαγράμματος. |
| [get_Item(int index)](#get-Item-int-) | Λαμβάνει το στοιχείο στον καθορισμένο δείκτη. |
| [getUpDownBars()](#getUpDownBars--) | Παρέχει πρόσβαση στις γραμμές πάνω/κάτω των διαγραμμάτων Line ή Stock. |
| [getGapWidth()](#getGapWidth--) | Καθορίζει το κενό μεταξύ ομάδων ράβδων ή στηλών, ως ποσοστό του πλάτους της ράβδου ή της στήλης. |
| [setGapWidth(int value)](#setGapWidth-int-) | Καθορίζει το κενό μεταξύ ομάδων ράβδων ή στηλών, ως ποσοστό του πλάτους της ράβδου ή της στήλης. |
| [getGapDepth()](#getGapDepth--) | Επιστρέφει ή ορίζει την απόσταση, ως ποσοστό του πλάτους του δείκτη, μεταξύ των σειρών δεδομένων σε διάγραμμα 3D. |
| [setGapDepth(int value)](#setGapDepth-int-) | Επιστρέφει ή ορίζει την απόσταση, ως ποσοστό του πλάτους του δείκτη, μεταξύ των σειρών δεδομένων σε διάγραμμα 3D. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Λαμβάνει ή ορίζει τη γωνία του πρώτου κομματιού πίτας ή δακτυλίου διαγράμματος, σε μοίρες (δεξιόστροφα από την κορυφή, από 0 έως 360 μοίρες). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Λαμβάνει ή ορίζει τη γωνία του πρώτου κομματιού πίτας ή δακτυλίου διαγράμματος, σε μοίρες (δεξιόστροφα από την κορυφή, από 0 έως 360 μοίρες). |
| [isColorVaried()](#isColorVaried--) | Καθορίζει ότι κάθε δείκτης δεδομένων στη σειρά έχει διαφορετικό χρώμα. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Καθορίζει ότι κάθε δείκτης δεδομένων στη σειρά έχει διαφορετικό χρώμα. |
| [hasSeriesLines()](#hasSeriesLines--) | Αληθές εάν το διάγραμμα έχει γραμμές σειράς. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Αληθές εάν το διάγραμμα έχει γραμμές σειράς. |
| [getOverlap()](#getOverlap--) | Καθορίζει πόσο θα επικαλύπτονται οι ράβδοι και στήλες σε 2Δ διαγράμματα, ως ποσοστό (από -100% έως 100%). |
| [setOverlap(byte value)](#setOverlap-byte-) | Καθορίζει πόσο θα επικαλύπτονται οι ράβδοι και στήλες σε 2Δ διαγράμματα, ως ποσοστό (από -100% έως 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Καθορίζει το μέγεθος του δεύτερου κομματιού πίτας ή ράβδου σε διάγραμμα πίτας-πίτας ή ράβδου-πίτας, ως ποσοστό του μεγέθους της πρώτης πίτας (μπορεί να είναι μεταξύ 5% και 200%). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Καθορίζει το μέγεθος του δεύτερου κομματιού πίτας ή ράβδου σε διάγραμμα πίτας-πίτας ή ράβδου-πίτας, ως ποσοστό του μεγέθους της πρώτης πίτας (μπορεί να είναι μεταξύ 5% και 200%). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Καθορίζει μια τιμή που θα χρησιμοποιηθεί για τον προσδιορισμό των σημείων δεδομένων που βρίσκονται στη δεύτερη πίτα ή ράβδο σε διάγραμμα πίτας-πίτας ή ράβδου-πίτας. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Καθορίζει μια τιμή που θα χρησιμοποιηθεί για τον προσδιορισμό των σημείων δεδομένων που βρίσκονται στη δεύτερη πίτα ή ράβδο σε διάγραμμα πίτας-πίτας ή ράβδου-πίτας. |
| [getPieSplitBy()](#getPieSplitBy--) | Καθορίζει πώς να προσδιοριστούν τα σημεία δεδομένων που βρίσκονται στη δεύτερη πίτα ή ράβδο σε διάγραμμα πίτας-πίτας ή ράβδου-πίτας. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Καθορίζει πώς να προσδιοριστούν τα σημεία δεδομένων που βρίσκονται στη δεύτερη πίτα ή ράβδο σε διάγραμμα πίτας-πίτας ή ράβδου-πίτας. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Οι προσαρμοσμένες πληροφορίες διαίρεσης για ένα διάγραμμα πίτας-πίτας ή ράβδου-πίτας με προσαρμοσμένη διαίρεση. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Καθορίζει το μέγεθος της τρύπας σε διάγραμμα δακτυλίου (μπορεί να είναι μεταξύ 10% και 90% του μεγέθους της περιοχής σχεδίασης). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Καθορίζει το μέγεθος της τρύπας σε διάγραμμα δακτυλίου (μπορεί να είναι μεταξύ 10% και 90% του μεγέθους της περιοχής σχεδίασης). |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Καθορίζει τον συντελεστή κλίμακας για το διάγραμμα φυσαλίδων (μπορεί να είναι μεταξύ 0% και 300% του προεπιλεγμένου μεγέθους). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Καθορίζει τον συντελεστή κλίμακας για το διάγραμμα φυσαλίδων (μπορεί να είναι μεταξύ 0% και 300% του προεπιλεγμένου μεγέθους). |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Καθορίζει τη μορφή HiLowLines. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Καθορίζει πώς οι τιμές μεγέθους των φυσαλίδων αντιπροσωπεύονται στο διάγραμμα φυσαλίδων. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Καθορίζει πώς οι τιμές μεγέθους των φυσαλίδων αντιπροσωπεύονται στο διάγραμμα φυσαλίδων. |

### getType() {#getType--}
```
public abstract int getType()
```

Επιστρέφει έναν τύπο αυτής της ομάδας σειράς. Μόνο για ανάγνωση [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

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

Επιστρέφει μια συλλογή μόνο για ανάγνωση από σειρές διαγράμματος. Μόνο για ανάγνωση [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Επιστρέφει:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

Λαμβάνει το στοιχείο στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public abstract IUpDownBarsManager getUpDownBars()
```

Παρέχει πρόσβαση στις γραμμές πάνω/κάτω των διαγραμμάτων Line ή Stock. Μόνο για ανάγνωση [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Επιστρέφει:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Καθορίζει το κενό μεταξύ ομάδων ράβδων ή στηλών, ως ποσοστό του πλάτους της ράβδου ή της στήλης. Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

Καθορίζει το κενό μεταξύ ομάδων ράβδων ή στηλών, ως ποσοστό του πλάτους της ράβδου ή της στήλης. Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Επιστρέφει ή ορίζει την απόσταση, ως ποσοστό του πλάτους του δείκτη, μεταξύ των σειρών δεδομένων σε διάγραμμα 3D. Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

Επιστρέφει ή ορίζει την απόσταση, ως ποσοστό του πλάτους του δείκτη, μεταξύ των σειρών δεδομένων σε διάγραμμα 3D. Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Λαμβάνει ή ορίζει τη γωνία του πρώτου κομματιού πίτας ή δακτυλίου διαγράμματος, σε μοίρες (δεξιόστροφα από την κορυφή, από 0 έως 360 μοίρες). Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

Λαμβάνει ή ορίζει τη γωνία του πρώτου κομματιού πίτας ή δακτυλίου διαγράμματος, σε μοίρες (δεξιόστροφα από την κορυφή, από 0 έως 360 μοίρες). Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Αληθές εάν το διάγραμμα έχει γραμμές σειράς. Εφαρμόζεται σε διαγράμματα στοίβας μπαρ και OfPie. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

Αληθές εάν το διάγραμμα έχει γραμμές σειράς. Εφαρμόζεται σε διαγράμματα στοίβας μπαρ και OfPie. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Καθορίζει πόσο θα επικαλύπτονται οι ράβδοι και στήλες σε 2Δ διαγράμματα, ως ποσοστό (από -100% έως 100%). - -100%: Μέγιστη απόσταση (οι ράβδοι είναι εντελώς χωρισμένες). - 0%: Οι ράβδοι τοποθετούνται πλάι-πλάι χωρίς επικάλυψη ή απόσταση. - 100%: Μέγιστη επικάλυψη (οι ράβδοι επικαλύπτονται πλήρως). Αυτό το χαρακτηριστικό είναι ανάγνωση/εγγραφή byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Ορισμός επικάλυψης στο 55%
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

Καθορίζει πόσο θα επικαλύπτονται οι ράβδοι και στήλες σε 2Δ διαγράμματα, ως ποσοστό (από -100% έως 100%). - -100%: Μέγιστη απόσταση (οι ράβδοι είναι εντελώς χωρισμένες). - 0%: Οι ράβδοι τοποθετούνται πλάι-πλάι χωρίς επικάλυψη ή απόσταση. - 100%: Μέγιστη επικάλυψη (οι ράβδοι επικαλύπτονται πλήρως). Αυτό το χαρακτηριστικό είναι ανάγνωση/εγγραφή byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Ορισμός επικάλυψης στο 55%
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
public abstract int getSecondPieSize()
```

Καθορίζει το μέγεθος του δεύτερου κομματιού πίτας ή ράβδου σε διάγραμμα πίτας-πίτας ή ράβδου-πίτας, ως ποσοστό του μεγέθους της πρώτης πίτας (μπορεί να είναι μεταξύ 5% και 200%). Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

Καθορίζει το μέγεθος του δεύτερου κομματιού πίτας ή ράβδου σε διάγραμμα πίτας-πίτας ή ράβδου-πίτας, ως ποσοστό του μεγέθους της πρώτης πίτας (μπορεί να είναι μεταξύ 5% και 200%). Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Καθορίζει μια τιμή που θα χρησιμοποιηθεί για τον προσδιορισμό των σημείων δεδομένων που βρίσκονται στη δεύτερη πίτα ή ράβδο σε διάγραμμα πίτας-πίτας ή ράβδου-πίτας. Χρησιμοποιείται μαζί με την ιδιότητα PieSplitBy. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

Καθορίζει μια τιμή που θα χρησιμοποιηθεί για τον προσδιορισμό των σημείων δεδομένων που βρίσκονται στη δεύτερη πίτα ή ράβδο σε διάγραμμα πίτας-πίτας ή ράβδου-πίτας. Χρησιμοποιείται μαζί με την ιδιότητα PieSplitBy. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Καθορίζει πώς να προσδιοριστούν τα σημεία δεδομένων που βρίσκονται στη δεύτερη πίτα ή ράβδο σε διάγραμμα πίτας-πίτας ή ράβδου-πίτας. Ανάγνωση/εγγραφή [PieSplitType](../../com.aspose.slides/piesplittype).

**Επιστρέφει:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

Καθορίζει πώς να προσδιοριστούν τα σημεία δεδομένων που βρίσκονται στη δεύτερη πίτα ή ράβδο σε διάγραμμα πίτας-πίτας ή ράβδου-πίτας. Ανάγνωση/εγγραφή [PieSplitType](../../com.aspose.slides/piesplittype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Οι προσαρμοσμένες πληροφορίες διαίρεσης για ένα διάγραμμα πίτας-πίτας ή ράβδου-πίτας με προσαρμοσμένη διαίρεση. Περιέχει σημεία δεδομένων που θα σχεδιαστούν στη δεύτερη πίτα ή ράβδο. Μόνο για ανάγνωση [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

**Επιστρέφει:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Καθορίζει το μέγεθος της τρύπας σε διάγραμμα δακτυλίου (μπορεί να είναι μεταξύ 10% και 90% του μεγέθους της περιοχής σχεδίασης). Ανάγνωση/εγγραφή byte.

**Επιστρέφει:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

Καθορίζει το μέγεθος της τρύπας σε διάγραμμα δακτυλίου (μπορεί να είναι μεταξύ 10% και 90% του μεγέθους της περιοχής σχεδίασης). Ανάγνωση/εγγραφή byte.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Καθορίζει τον συντελεστή κλίμακας για το διάγραμμα φυσαλίδων (μπορεί να είναι μεταξύ 0% και 300% του προεπιλεγμένου μεγέθους). Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

Καθορίζει τον συντελεστή κλίμακας για το διάγραμμα φυσαλίδων (μπορεί να είναι μεταξύ 0% και 300% του προεπιλεγμένου μεγέθους). Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```

Καθορίζει τη μορφή HiLowLines. Η HiLowLines εφαρμόζεται σε τύπους διαγραμμάτων HiLowClose, OpenHiLowClose, VolumeHiLowClose και VolumeOpenHiLowClose.

**Επιστρέφει:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

Καθορίζει πώς οι τιμές μεγέθους των φυσαλίδων αντιπροσωπεύονται στο διάγραμμα φυσαλίδων. Ανάγνωση/εγγραφή [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Επιστρέφει:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```

Καθορίζει πώς οι τιμές μεγέθους των φυσαλίδων αντιπροσωπεύονται στο διάγραμμα φυσαλίδων. Ανάγνωση/εγγραφή [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |