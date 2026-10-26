---
title: IChartDataPointCollection
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αναπαριστά τη συλλογή ενός σημείου δεδομένων σειράς.
type: docs
url: /el/com.aspose.slides/ichartdatapointcollection/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
com.aspose.slides.IGenericCollection
```
public interface IChartDataPointCollection extends IGenericCollection<IChartDataPoint>
```

Αναπαριστά συλλογή ενός σημείου δεδομένων σειράς.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει το σημείο δεδομένων σειράς με βάση το ευρετήριο (αριθμό σειράς σε αυτή τη συλλογή). |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | Επιστρέφει το ευρετήριο (αριθμό σειράς σε αυτή τη συλλογή) του σημείου δεδομένων σε αυτή τη συλλογή. |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | Καθορίζει εάν η ιδιότητα AsCell ή AsLiteralString ή AsLiteralDouble είναι ενεργή στο αντικείμενο ιδιότητας XValue των σημείων δεδομένων. |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | Καθορίζει εάν η ιδιότητα AsCell ή AsLiteralString ή AsLiteralDouble είναι ενεργή στο αντικείμενο ιδιότητας XValue των σημείων δεδομένων. |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | Καθορίζει εάν η ιδιότητα AsCell ή AsLiteralString ή AsLiteralDouble είναι ενεργή στο αντικείμενο ιδιότητας YValue των σημείων δεδομένων. |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | Καθορίζει εάν η ιδιότητα AsCell ή AsLiteralString ή AsLiteralDouble είναι ενεργή στο αντικείμενο ιδιότητας YValue των σημείων δεδομένων. |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | Καθορίζει εάν η ιδιότητα AsCell ή AsLiteralString ή AsLiteralDouble είναι ενεργή στο αντικείμενο ιδιότητας BubbleSize των σημείων δεδομένων. |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | Καθορίζει εάν η ιδιότητα AsCell ή AsLiteralString ή AsLiteralDouble είναι ενεργή στο αντικείμενο ιδιότητας BubbleSize των σημείων δεδομένων. |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | Καθορίζει εάν η ιδιότητα AsCell ή AsLiteralString ή AsLiteralDouble είναι ενεργή στο αντικείμενο ιδιότητας Value των σημείων δεδομένων. |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | Καθορίζει εάν η ιδιότητα AsCell ή AsLiteralString ή AsLiteralDouble είναι ενεργή στο αντικείμενο ιδιότητας Value των σημείων δεδομένων. |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | Καθορίζει τον τύπο των τιμών στη λίστα ιδιοτήτων ChartDataPoint.ErrorBarsCustomValues. |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | Εάν η συλλογή περιέχει ήδη σημείο δεδομένων με το ευρετήριο index, τότε επιστρέφει αυτό το σημείο δεδομένων. |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [clear()](#clear--) | Αφαιρεί όλα τα στοιχεία από τη συλλογή. |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | Αφαιρεί την καθορισμένη τιμή. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί το στοιχείο στο συγκεκριμένο ευρετήριο. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```

Επιστρέφει το σημείο δεδομένων σειράς με βάση το ευρετήριο (αριθμό σειράς σε αυτή τη συλλογή).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)
### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public abstract int get_Item(IChartDataPoint pt)
```

Επιστρέφει το ευρετήριο (αριθμό σειράς σε αυτή τη συλλογή) του σημείου δεδομένων σε αυτή τη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**Επιστρέφει:**
int
### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public abstract int getDataSourceTypeForXValues()
```

Καθορίζει εάν η ιδιότητα AsCell ή AsLiteralString ή AsLiteralDouble είναι ενεργή στο αντικείμενο ιδιότητας XValue των σημείων δεδομένων. Με άλλα λόγια καθορίζει τον τύπο της τιμής της ιδιότητας ChartDataPointEx.XValue.Data. Ανάγνωση/εγγραφή [DataSourceType](../../com.aspose.slides/datasourcetype).

**Επιστρέφει:**
int
### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public abstract void setDataSourceTypeForXValues(int value)
```

Καθορίζει εάν η ιδιότητα AsCell ή AsLiteralString ή AsLiteralDouble είναι ενεργή στο αντικείμενο ιδιότητας XValue των σημείων δεδομένων. Με άλλα λόγια καθορίζει τον τύπο της τιμής της ιδιότητας ChartDataPointEx.XValue.Data. Ανάγνωση/εγγραφή [DataSourceType](../../com.aspose.slides/datasourcetype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public abstract int getDataSourceTypeForYValues()
```

Καθορίζει εάν η ιδιότητα AsCell ή AsLiteralString ή AsLiteralDouble είναι ενεργή στο αντικείμενο ιδιότητας YValue των σημείων δεδομένων. Με άλλα λόγια καθορίζει τον τύπο της τιμής της ιδιότητας ChartDataPointEx.YValue.Data. Ανάγνωση/εγγραφή [DataSourceType](../../com.aspose.slides/datasourcetype).

**Επιστρέφει:**
int
### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public abstract void setDataSourceTypeForYValues(int value)
```

Καθορίζει εάν η ιδιότητα AsCell ή AsLiteralString ή AsLiteralDouble είναι ενεργή στο αντικείμενο ιδιότητας YValue των σημείων δεδομένων. Με άλλα λόγια καθορίζει τον τύπο της τιμής της ιδιότητας ChartDataPointEx.YValue.Data. Ανάγνωση/εγγραφή [DataSourceType](../../com.aspose.slides/datasourcetype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public abstract int getDataSourceTypeForBubbleSizes()
```

Καθορίζει εάν η ιδιότητα AsCell ή AsLiteralString ή AsLiteralDouble είναι ενεργή στο αντικείμενο ιδιότητας BubbleSize των σημείων δεδομένων. Με άλλα λόγια καθορίζει τον τύπο της τιμής της ιδιότητας ChartDataPointEx.BubbleSize.Data. Ανάγνωση/εγγραφή [DataSourceType](../../com.aspose.slides/datasourcetype).

**Επιστρέφει:**
int
### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public abstract void setDataSourceTypeForBubbleSizes(int value)
```

Καθορίζει εάν η ιδιότητα AsCell ή AsLiteralString ή AsLiteralDouble είναι ενεργή στο αντικείμενο ιδιότητας BubbleSize των σημείων δεδομένων. Με άλλα λόγια καθορίζει τον τύπο της τιμής της ιδιότητας ChartDataPointEx.BubbleSize.Data. Ανάγνωση/εγγραφή [DataSourceType](../../com.aspose.slides/datasourcetype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public abstract int getDataSourceTypeForValues()
```

Καθορίζει εάν η ιδιότητα AsCell ή AsLiteralString ή AsLiteralDouble είναι ενεργή στο αντικείμενο ιδιότητας Value των σημείων δεδομένων. Με άλλα λόγια καθορίζει τον τύπο της τιμής της ιδιότητας ChartDataPoint.Value.Data. Ανάγνωση/εγγραφή [DataSourceType](../../com.aspose.slides/datasourcetype).

**Επιστρέφει:**
int
### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public abstract void setDataSourceTypeForValues(int value)
```

Καθορίζει εάν η ιδιότητα AsCell ή AsLiteralString ή AsLiteralDouble είναι ενεργή στο αντικείμενο ιδιότητας Value των σημείων δεδομένων. Με άλλα λόγια καθορίζει τον τύπο της τιμής της ιδιότητας ChartDataPoint.Value.Data. Ανάγνωση/εγγραφή [DataSourceType](../../com.aspose.slides/datasourcetype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public abstract IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

Καθορίζει τον τύπο των τιμών στη λίστα ιδιοτήτων ChartDataPoint.ErrorBarsCustomValues. Μόνο για ανάγνωση [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues).

**Επιστρέφει:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)
### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public abstract IChartDataPoint getOrCreateDataPointByIdx(long index)
```

Εάν η συλλογή περιέχει ήδη σημείο δεδομένων με το ευρετήριο index, τότε επιστρέφει αυτό το σημείο δεδομένων. Εάν η συλλογή δεν περιέχει σημείο δεδομένων με index==N (όταν ο αριθμός σημείων δεδομένων σε αυτή τη συλλογή είναι μικρότερος ή ίσος του N), τότε προσθέτει ελλιπή σημεία δεδομένων και επιστρέφει το τελευταίο (το οποίο έχει το ζητούμενο ευρετήριο). Για παράδειγμα, τα ευρετήρια της συλλογής είναι {0, 1, 2}, και το ζητούμενο ευρετήριο είναι 5. Τότε η μέθοδος προσθέτει ελλιπή σημεία: {0, 1, 2, 3, 4, 5}. Και επιστρέφει το σημείο δεδομένων με ευρετήριο 5.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | long | Δείκτης. |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Επιστρέφει το σημείο δεδομένων με το ζητούμενο ευρετήριο.
### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένα από τα υποτύπους Stock (δείτε επίσης τη μέθοδο ChartTypeCharacterizer.IsChartTypeStock(ChartType)).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Τιμή σημείου δεδομένων. |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.
### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public abstract IChartDataPoint addDataPointForStockSeries(double value)
```

Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένα από τα υποτύπους Stock (δείτε επίσης τη μέθοδο ChartTypeCharacterizer.IsChartTypeStock(ChartType)).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double | Τιμή σημείου δεδομένων. |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.
### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένα από τα υποτύπων Line (δείτε επίσης τη μέθοδο ChartTypeCharacterizer.IsChartTypeLine(ChartType)).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Τιμή σημείου δεδομένων. |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.
### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public abstract IChartDataPoint addDataPointForLineSeries(double value)
```

Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένα από τα υποτύπων Line (δείτε επίσης τη μέθοδο ChartTypeCharacterizer.IsChartTypeLine(ChartType)).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double | Τιμή σημείου δεδομένων. |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.
### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένα από τα υποτύπων Scatter (δείτε επίσης τη μέθοδο ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue του σημείου δεδομένων |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue του σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.
### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένα από τα υποτύπων Scatter (δείτε επίσης τη μέθοδο ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xValue | double | XValue του σημείου δεδομένων |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue του σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.
### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένα από τα υποτύπων Scatter (δείτε επίσης τη μέθοδο ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xValue | java.lang.String | XValue του σημείου δεδομένων |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue του σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.
### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένα από τα υποτύπων Scatter (δείτε επίσης τη μέθοδο ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue του σημείου δεδομένων |
| yValue | double | YValue του σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.
### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένα από τα υποτύπων Scatter (δείτε επίσης τη μέθοδο ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xValue | double | XValue του σημείου δεδομένων |
| yValue | double | YValue του σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.
### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένα από τα υποτύπων Scatter (δείτε επίσης τη μέθοδο ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xValue | java.lang.String | XValue του σημείου δεδομένων |
| yValue | double | YValue του σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.
### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένα από τα υποτύπων Radar (δείτε επίσης τη μέθοδο ChartTypeCharacterizer.IsChartTypeRadar(ChartType)).

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Τιμή σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.
### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(double value)
```

Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένα από τα υποτύπων Radar (δείτε επίσης τη μέθοδο ChartTypeCharacterizer.IsChartTypeRadar(ChartType)).

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double | Τιμή σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.
### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένα από τα υποτύπων Column ή Bar (δείτε επίσης τις μεθόδους ChartTypeCharacterizer.IsChartTypeColumn(ChartType) και ChartTypeCharacterizer.IsChartTypeBar(ChartType)).

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Τιμή σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.
### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public abstract IChartDataPoint addDataPointForBarSeries(double value)
```

Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένα από τα υποτύπων Column ή Bar (δείτε επίσης τις μεθόδους ChartTypeCharacterizer.IsChartTypeColumn(ChartType) και ChartTypeCharacterizer.IsChartTypeBar(ChartType)).

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double | Τιμή σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.
### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένα από τα υποτύπων Area (δείτε επίσης τη μέθοδο ChartTypeCharacterizer.IsChartTypeArea(ChartType)).

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Τιμή σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.
### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(double value)
```

Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένα από τα υποτύπων Area (δείτε επίσης τη μέθοδο ChartTypeCharacterizer.IsChartTypeArea(ChartType)).

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double | Τιμή σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.
### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένα από τα υποτύπων Pie (δείτε επίσης τη μέθοδο ChartTypeCharacterizer.IsChartTypePie(ChartType)).

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Τιμή σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.
### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public abstract IChartDataPoint addDataPointForPieSeries(double value)
```

Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένα από τα υποτύπων Pie (δείτε επίσης τη μέθοδο ChartTypeCharacterizer.IsChartTypePie(ChartType)).

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double | Τιμή σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.
### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένα από τα υποτύπων Doughnut (δείτε επίσης τη μέθοδο ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType)).

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Τιμή σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.
### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(double value)
```

Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένα από τα υποτύπων Doughnut (δείτε επίσης τη μέθοδο ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType)).

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double | Τιμή σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένα από τα υποτύπων Bubble (δείτε επίσης τη μέθοδο ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue του σημείου δεδομένων |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue του σημείου δεδομένων |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize του σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένα από τα υποτύπων Bubble (δείτε επίσης τη μέθοδο ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xValue | double | XValue του σημείου δεδομένων |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue του σημείου δεδομένων |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize του σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένα από τα υποτύπων Bubble (δείτε επίσης τη μέθοδο ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xValue | java.lang.String | XValue του σημείου δεδομένων |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue του σημείου δεδομένων |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize του σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένα από τα υποτύπων Bubble (δείτε επίσης τη μέθοδο ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue του σημείου δεδομένων |
| yValue | double | YValue του σημείου δεδομένων |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize του σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.
### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένα από τα υποτύπων Bubble (δείτε επίσης τη μέθοδο ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xValue | double | XValue του σημείου δεδομένων |
| yValue | double | YValue του σημείου δεδομένων |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize του σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.
### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένα από τα υποτύπων Bubble (δείτε επίσης τη μέθοδο ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xValue | java.lang.String | XValue του σημείου δεδομένων |
| yValue | double | YValue του σημείου δεδομένων |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize του σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```

Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένα από τα υποτύπων Bubble (δείτε επίσης τη μέθοδο ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue του σημείου δεδομένων |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue του σημείου δεδομένων |
| bubbleSize | double | BubbleSize του σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```

Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένα από τα υποτύπων Bubble (δείτε επίσης τη μέθοδο ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xValue | double | XValue του σημείου δεδομένων |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue του σημείου δεδομένων |
| bubbleSize | double | BubbleSize του σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```

Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένα από τα υποτύπων Bubble (δείτε επίσης τη μέθοδο ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xValue | java.lang.String | XValue του σημείου δεδομένων |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue του σημείου δεδομένων |
| bubbleSize | double | BubbleSize του σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```

Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένα από τα υποτύπων Bubble (δείτε επίσης τη μέθοδο ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue του σημείου δεδομένων |
| yValue | double | YValue του σημείου δεδομένων |
| bubbleSize | double | BubbleSize του σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.
### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```

Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένα από τα υποτύπων Bubble (δείτε επίσης τη μέθοδο ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xValue | double | XValue του σημείου δεδομένων |
| yValue | double | YValue του σημείου δεδομένων |
| bubbleSize | double | BubbleSize του σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.
### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```

Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένα από τα υποτύπων Bubble (δείτε επίσης τη μέθοδο ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xValue | java.lang.String | XValue του σημείου δεδομένων |
| yValue | double | YValue του σημείου δεδομένων |
| bubbleSize | double | BubbleSize του σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.
### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```

Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένα από τα υποτύπων Surface (δείτε επίσης τη μέθοδο ChartTypeCharacterizer.IsChartTypeSurface(ChartType)).

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Τιμή σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.
### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(double value)
```

Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένα από τα υποτύπων Surface (δείτε επίσης τη μέθοδο ChartTypeCharacterizer.IsChartTypeSurface(ChartType)).

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double | Τιμή σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.
### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```

Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές του τύπου Sunburst.

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | SizeValue του σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.
### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```

Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές του τύπου Waterfall.

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Τιμή σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.
### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public abstract I 
```

Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές του τύπου BoxAndWhisker.

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Τιμή σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.
### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```

Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές του τύπου Treemap.

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | SizeValue του σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.
### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```

Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές του τύπου Histogram.

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Τιμή σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.
### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές του τύπου Funnel.

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Τιμή σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.
### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```

Δημιουργεί ένα νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές του τύπου Map.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Map, 50, 50, 500, 400, false);
>      IChartDataWorkbook wb = chart.getChartData().getChartDataWorkbook();
>      IChartSeries series = chart.getChartData().getSeries().add(ChartType.Map);
>      series.getDataPoints().addDataPointForMapSeries(wb.getCell(0, "B2", 5));
>      series.getDataPoints().addDataPointForMapSeries(wb.getCell(0, "B3", 1));
>      series.getDataPoints().addDataPointForMapSeries(wb.getCell(0, "B4", 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | ColorValue του σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.
### clear() {#clear--}
```
public abstract void clear()
```

Αφαιρεί όλα τα στοιχεία από τη συλλογή.
### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public abstract void remove(IChartDataPoint value)
```

Αφαιρεί την καθορισμένη τιμή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Η τιμή. |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Αφαιρεί το στοιχείο στο συγκεκριμένο ευρετήριο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ευρετήριο σημείου δεδομένων για διαγραφή. |