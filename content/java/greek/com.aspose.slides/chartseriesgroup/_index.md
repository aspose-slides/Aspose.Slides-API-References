---
title: ChartSeriesGroup
second_title: Αναφορά API Aspose.Slides για Java
description: Αναπαριστά ομάδα σειρών.
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

Αντιπροσωπεύει ομάδα σειρών.

--------------------

1) Δείτε τη σύνοψη και τις παρατηρήσεις για την κλάση ChartSeriesGroupCollection και το enum CombinableSeriesTypesGroup. 2) Η ομάδα σειρών περιέχει ορισμένες ιδιότητες σειρών που είναι κοινές για κάθε σειρά στην ομάδα («ιδιότητες ομάδας σειρών»). Οι «ιδιότητες ομάδας σειρών» στην κλάση ChartSeriesGroup είναι ανάγνωση/εγγραφή. Κάθε μία από τις «ιδιότητες ομάδας σειρών» μπορεί να έχει μια προβολή μόνο για ανάγνωση στην κλάση ChartSeries.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getType()](#getType--) | Επιστρέφει έναν τύπο αυτής της ομάδας σειρών. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Δείχνει εάν οι σειρές αυτής της ομάδας σχεδιάζονται σε δευτερεύον άξονα. |
| [getSeries()](#getSeries--) | Επιστρέφει μια συλλογή σειρών. |
| [get_Item(int index)](#get-Item-int-) | Λαμβάνει το στοιχείο στον καθορισμένο δείκτη. |
| [getUpDownBars()](#getUpDownBars--) | Παρέχει πρόσβαση σε μπαρ πάνω/κάτω γραμμές γραφήματος Γραμμής ή Στοκ. |
| [getGapWidth()](#getGapWidth--) | Λαμβάνει ή ορίζει το διάστημα μεταξύ ομάδων μπαρ ή στηλών, ως ποσοστό του πλάτους του μπαρ ή της στήλης. |
| [setGapWidth(int value)](#setGapWidth-int-) | Λαμβάνει ή ορίζει το διάστημα μεταξύ ομάδων μπαρ ή στηλών, ως ποσοστό του πλάτους του μπαρ ή της στήλης. |
| [getGapDepth()](#getGapDepth--) | Λαμβάνει ή ορίζει την απόσταση μεταξύ σειρών δεδομένων σε 3D γράφημα, ως ποσοστό του πλάτους του δείκτη. |
| [setGapDepth(int value)](#setGapDepth-int-) | Λαμβάνει ή ορίζει την απόσταση μεταξύ σειρών δεδομένων σε 3D γράφημα, ως ποσοστό του πλάτους του δείκτη. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Λαμβάνει ή ορίζει τη γωνία του πρώτου κομματιού σε γράφημα πίτας ή δακτυλίου, σε μοίρες (δεξιόστροφα από πάνω, από 0 έως 360 μοίρες). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Λαμβάνει ή ορίζει τη γωνία του πρώτου κομματιού σε γράφημα πίτας ή δακτυλίου, σε μοίρες (δεξιόστροφα από πάνω, από 0 έως 360 μοίρες). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Καθορίζει το μέγεθος της τρύπας σε γράφημα δακτυλίου (μπορεί να είναι μεταξύ 0 και 90 τοις εκατό του μεγέθους της περιοχής σχεδίασης). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Καθορίζει το μέγεθος της τρύπας σε γράφημα δακτυλίου (μπορεί να είναι μεταξύ 0 και 90 τοις εκατό του μεγέθους της περιοχής σχεδίασης). |
| [getOverlap()](#getOverlap--) | Καθορίζει πόσο θα επικαλύπτονται μπαρ και στήλες σε 2-Δ γραφήματα, ως ποσοστό (από -100% έως 100%). |
| [setOverlap(byte value)](#setOverlap-byte-) | Καθορίζει πόσο θα επικαλύπτονται μπαρ και στήλες σε 2-Δ γραφήματα, ως ποσοστό (από -100% έως 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Καθορίζει το μέγεθος του δεύτερου κομματιού ή μπαρ σε γράφημα «pie-of-pie» ή «bar-of-pie», ως ποσοστό του μεγέθους του πρώτου κομματιού (μπορεί να είναι μεταξύ 5 και 200 τοις εκατό). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Καθορίζει το μέγεθος του δεύτερου κομματιού ή μπαρ σε γράφημα «pie-of-pie» ή «bar-of-pie», ως ποσοστό του μεγέθους του πρώτου κομματιού (μπορεί να είναι μεταξύ 5 και 200 τοις εκατό). |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Καθορίζει πώς θα αναπαρίστανται οι τιμές μεγέθους φυσαλίδων στο γράφημα φυσαλίδων. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Καθορίζει πώς θα αναπαρίστανται οι τιμές μεγέθους φυσαλίδων στο γράφημα φυσαλίδων. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Καθορίζει μια τιμή που θα χρησιμοποιηθεί για τον προσδιορισμό των σημείων δεδομένων που ανήκουν στο δεύτερο κομμάτι ή μπαρ σε γράφημα «pie-of-pie» ή «bar-of-pie». |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Καθορίζει μια τιμή που θα χρησιμοποιηθεί για τον προσδιορισμό των σημείων δεδομένων που ανήκουν στο δεύτερο κομμάτι ή μπαρ σε γράφημα «pie-of-pie» ή «bar-of-pie». |
| [getPieSplitBy()](#getPieSplitBy--) | Καθορίζει πώς θα προσδιοριστούν τα σημεία δεδομένων που ανήκουν στο δεύτερο κομμάτι ή μπαρ σε γράφημα «pie-of-pie» ή «bar-of-pie». |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Καθορίζει πώς θα προσδιοριστούν τα σημεία δεδομένων που ανήκουν στο δεύτερο κομμάτι ή μπαρ σε γράφημα «pie-of-pie» ή «bar-of-pie». |
| [isColorVaried()](#isColorVaried--) | Καθορίζει ότι κάθε δείκτη δεδομένων στη σειρά έχει διαφορετικό χρώμα. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Καθορίζει ότι κάθε δείκτη δεδομένων στη σειρά έχει διαφορετικό χρώμα. |
| [hasSeriesLines()](#hasSeriesLines--) | Αληθές εάν το γράφημα έχει γραμμές σειράς. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Αληθές εάν το γράφημα έχει γραμμές σειράς. |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Καθορίζει μορφή HiLowLines. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Καθορίζει τον συντελεστή κλίμακας για το γράφημα φυσαλίδων (μπορεί να είναι μεταξύ 0 και 300 τοις εκατό του προεπιλεγμένου μεγέθους). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Καθορίζει τον συντελεστή κλίμακας για το γράφημα φυσαλίδων (μπορεί να είναι μεταξύ 0 και 300 τοις εκατό του προεπιλεγμένου μεγέθους). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Οι προσαρμοσμένες πληροφορίες διαχωρισμού για ένα γράφημα «pie-of-pie» ή «bar-of-pie» με προσαρμοσμένο διαχωρισμό. |
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

Δείχνει εάν οι σειρές αυτής της ομάδας σχεδιάζονται σε δευτερεύον άξονα. Μόνο για ανάγνωση boolean.

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

Λαμβάνει το στοιχείο στον καθορισμένο δείκτη.

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

Παρέχει πρόσβαση σε μπαρ πάνω/κάτω γραμμές γραφήματος Γραμμής ή Στοκ. Μόνο για ανάγνωση [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Επιστρέφει:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)
### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Λαμβάνει ή ορίζει το διάστημα μεταξύ ομάδων μπαρ ή στηλών, ως ποσοστό του πλάτους του μπαρ ή της στήλης. Η τιμή πρέπει να είναι μεταξύ 0 και 500. Ανάγνωση/Εγγραφή int.

--------------------

Αυτή η ιδιότητα ισχύει για σειρές των ακόλουθων τύπων: Υποτύποι Bar (δείτε επίσης τη μέθοδο [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)), υποτύποι Column (δείτε επίσης τη μέθοδο [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-)), [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**Επιστρέφει:**
int
### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

Λαμβάνει ή ορίζει το διάστημα μεταξύ ομάδων μπαρ ή στηλών, ως ποσοστό του πλάτους του μπαρ ή της στήλης. Η τιμή πρέπει να είναι μεταξύ 0 και 500. Ανάγνωση/Εγγραφή int.

--------------------

Αυτή η ιδιότητα ισχύει για σειρές των ακόλουθων τύπων: Υποτύποι Bar (δείτε επίσης τη μέθοδο [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)), υποτύποι Column (δείτε επίσης τη μέθοδο [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-)), [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Λαμβάνει ή ορίζει την απόσταση μεταξύ σειρών δεδομένων σε 3D γράφημα, ως ποσοστό του πλάτους του δείκτη. Η τιμή πρέπει να είναι μεταξύ 0 και 500. Ανάγνωση/Εγγραφή int.

--------------------

Αυτή η ιδιότητα ισχύει για σειρές των ακόλουθων τύπων: Υποτύποι 3D Bar και Column (δείτε επίσης τη μέθοδο [ChartTypeCharacterizer.isBar3DChart(int)](../../com.aspose.slides/charttypecharacterizer\#isBar3DChart-int-)), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**Επιστρέφει:**
int
### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

Λαμβάνει ή ορίζει την απόσταση μεταξύ σειρών δεδομένων σε 3D γράφημα, ως ποσοστό του πλάτους του δείκτη. Η τιμή πρέπει να είναι μεταξύ 0 και 500. Ανάγνωση/Εγγραφή int.

--------------------

Αυτή η ιδιότητα ισχύει για σειρές των ακόλουθων τύπων: Υποτύποι 3D Bar και Column (δείτε επίσης τη μέθοδο [ChartTypeCharacterizer.isBar3DChart(int)](../../com.aspose.slides/charttypecharacterizer\#isBar3DChart-int-)), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Λαμβάνει ή ορίζει τη γωνία του πρώτου κομματιού σε γράφημα πίτας ή δακτυλίου, σε μοίρες (δεξιόστροφα από πάνω, από 0 έως 360 μοίρες). Ανάγνωση/Εγγραφή int.

**Επιστρέφει:**
int
### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

Λαμβάνει ή ορίζει τη γωνία του πρώτου κομματιού σε γράφημα πίτας ή δακτυλίου, σε μοίρες (δεξιόστροφα από πάνω, από 0 έως 360 μοίρες). Ανάγνωση/Εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Καθορίζει το μέγεθος της τρύπας σε γράφημα δακτυλίου (μπορεί να είναι μεταξύ 0 και 90 τοις εκατό του μεγέθους της περιοχής σχεδίασης). Ανάγνωση/Εγγραφή byte.

**Επιστρέφει:**
byte
### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```

Καθορίζει το μέγεθος της τρύπας σε γράφημα δακτυλίου (μπορεί να είναι μεταξύ 0 και 90 τοις εκατό του μεγέθους της περιοχής σχεδίασης). Ανάγνωση/Εγγραφή byte.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |
### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Καθορίζει πόσο θα επικαλύπτονται μπαρ και στήλες σε 2-Δ γραφήματα, ως ποσοστό (από -100% έως 100%). -100%: Μέγιστη απόσταση (τα μπαρ είναι πλήρως χωρισμένα). -0%: Τα μπαρ τοποθετούνται πλάι-πλάι χωρίς επικάλυψη ή απόσταση. 100%: Μέγιστη επικάλυψη (τα μπαρ επικαλύπτονται πλήρως). Αυτή η ιδιότητα είναι ανάγνωση/εγγραφή byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Ορίστε την επικάλυψη σε 55%
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

Καθορίζει πόσο θα επικαλύπτονται μπαρ και στήλες σε 2-Δ γραφήματα, ως ποσοστό (από -100% έως 100%). -100%: Μέγιστη απόσταση (τα μπαρ είναι πλήρως χωρισμένα). -0%: Τα μπαρ τοποθετούνται πλάι-πλάι χωρίς επικάλυψη ή απόσταση. 100%: Μέγιστη επικάλυψη (τα μπαρ επικαλύπτονται πλήρως). Αυτή η ιδιότητα είναι ανάγνωση/εγγραφή byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Ορίστε την επικάλυψη σε 55%
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

Καθορίζει το μέγεθος του δεύτερου κομματιού ή μπαρ σε γράφημα «pie-of-pie» ή «bar-of-pie», ως ποσοστό του μεγέθους του πρώτου κομματιού (μπορεί να είναι μεταξύ 5 και 200 τοις εκατό). Ανάγνωση/Εγγραφή int.

**Επιστρέφει:**
int
### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

Καθορίζει το μέγεθος του δεύτερου κομματιού ή μπαρ σε γράφημα «pie-of-pie» ή «bar-of-pie», ως ποσοστό του μεγέθους του πρώτου κομματιού (μπορεί να είναι μεταξύ 5 και 200 τοις εκατό). Ανάγνωση/Εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Καθορίζει πώς θα αναπαρίστανται οι τιμές μεγέθους φυσαλίδων στο γράφημα φυσαλίδων. Ανάγνωση/Εγγραφή [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Επιστρέφει:**
int
### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```

Καθορίζει πώς θα αναπαρίστανται οι τιμές μεγέθους φυσαλίδων στο γράφημα φυσαλίδων. Ανάγνωση/Εγγραφή [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Καθορίζει μια τιμή που θα χρησιμοποιηθεί για τον προσδιορισμό των σημείων δεδομένων που ανήκουν στο δεύτερο κομμάτι ή μπαρ σε γράφημα «pie-of-pie» ή «bar-of-pie». Χρησιμοποιείται μαζί με την ιδιότητα PieSplitBy. Ανάγνωση/Εγγραφή double.

**Επιστρέφει:**
double
### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

Καθορίζει μια τιμή που θα χρησιμοποιηθεί για τον προσδιορισμό των σημείων δεδομένων που ανήκουν στο δεύτερο κομμάτι ή μπαρ σε γράφημα «pie-of-pie» ή «bar-of-pie». Χρησιμοποιείται μαζί με την ιδιότητα PieSplitBy. Ανάγνωση/Εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |
### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Καθορίζει πώς θα προσδιοριστούν τα σημεία δεδομένων που ανήκουν στο δεύτερο κομμάτι ή μπαρ σε γράφημα «pie-of-pie» ή «bar-of-pie». Ανάγνωση/Εγγραφή [PieSplitType](../../com.aspose.slides/piesplittype).

**Επιστρέφει:**
int
### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

Καθορίζει πώς θα προσδιοριστούν τα σημεία δεδομένων που ανήκουν στο δεύτερο κομμάτι ή μπαρ σε γράφημα «pie-of-pie» ή «bar-of-pie». Ανάγνωση/Εγγραφή [PieSplitType](../../com.aspose.slides/piesplittype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

Καθορίζει ότι κάθε δείκτη δεδομένων στη σειρά έχει διαφορετικό χρώμα. Ανάγνωση/Εγγραφή boolean.

**Επιστρέφει:**
boolean
### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```

Καθορίζει ότι κάθε δείκτη δεδομένων στη σειρά έχει διαφορετικό χρώμα. Ανάγνωση/Εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

Αληθές εάν το γράφημα έχει γραμμές σειράς. Εφαρμόζεται σε στοιβαγμένα μπαρ και γραφήματα OfPie. Ανάγνωση/Εγγραφή boolean.

**Επιστρέφει:**
boolean
### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```

Αληθές εάν το γράφημα έχει γραμμές σειράς. Εφαρμόζεται σε στοιβαγμένα μπαρ και γραφήματα OfPie. Ανάγνωση/Εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```

Καθορίζει μορφή HiLowLines. Τα HiLowLines εφαρμόζονται με τύπους γραφήματος HiLowClose, OpenHiLowClose, VolumeHiLowClose και VolumeOpenHiLowClose.

**Επιστρέφει:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Καθορίζει τον συντελεστή κλίμακας για το γράφημα φυσαλίδων (μπορεί να είναι μεταξύ 0 και 300 τοις εκατό του προεπιλεγμένου μεγέθους). Ανάγνωση/Εγγραφή int.

**Επιστρέφει:**
int
### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```

Καθορίζει τον συντελεστή κλίμακας για το γράφημα φυσαλίδων (μπορεί να είναι μεταξύ 0 και 300 τοις εκατό του προεπιλεγμένου μεγέθους). Ανάγνωση/Εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Οι προσαρμοσμένες πληροφορίες διαχωρισμού για ένα γράφημα «pie-of-pie» ή «bar-of-pie» με προσαρμοσμένο διαχωρισμό. Περιέχει σημεία δεδομένων που θα σχεδιαστούν στο δεύτερο κομμάτι ή μπαρ σε γράφημα «pie-of-pie» ή «bar-of-pie». Μόνο για ανάγνωση [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

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