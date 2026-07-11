---
title: ChartDataPointCollection
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αναπαριστά τη συλλογή ενός σημείου δεδομένων σειράς.
type: docs
url: /el/com.aspose.slides/chartdatapointcollection/
---
**Κληρονομικότητα:**
java.lang.Object, com.aspose.slides.DomObject

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)
```
public class ChartDataPointCollection extends DomObject<ChartSeries> implements IChartDataPointCollection
```

Αναπαριστά τη συλλογή ενός σημείου δεδομένων σειράς.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει το σημείο δεδομένων της σειράς βάσει δείκτη (τον σειριακό αριθμό του σε αυτή τη συλλογή). |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | Επιστρέφει τον δείκτη (σειριακό αριθμό) του σημείου δεδομένων σε αυτή τη συλλογή. |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | Καθορίζει αν η ιδιότητα AsCell ή AsLiteralString ή AsLiteralDouble είναι ενεργή στο αντικείμενο ιδιότητας XValue των σημείων δεδομένων. |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | Καθορίζει αν η ιδιότητα AsCell ή AsLiteralString ή AsLiteralDouble είναι ενεργή στο αντικείμενο ιδιότητας XValue των σημείων δεδομένων. |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | Καθορίζει αν η ιδιότητα AsCell ή AsLiteralString ή AsLiteralDouble είναι ενεργή στο αντικείμενο ιδιότητας YValue των σημείων δεδομένων. |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | Καθορίζει αν η ιδιότητα AsCell ή AsLiteralString ή AsLiteralDouble είναι ενεργή στο αντικείμενο ιδιότητας YValue των σημείων δεδομένων. |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | Καθορίζει αν η ιδιότητα AsCell ή AsLiteralString ή AsLiteralDouble είναι ενεργή στο αντικείμενο ιδιότητας BubbleSize των σημείων δεδομένων. |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | Καθορίζει αν η ιδιότητα AsCell ή AsLiteralString ή AsLiteralDouble είναι ενεργή στο αντικείμενο ιδιότητας BubbleSize των σημείων δεδομένων. |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | Καθορίζει αν η ιδιότητα AsCell ή AsLiteralString ή AsLiteralDouble είναι ενεργή στο αντικείμενο ιδιότητας Value των σημείων δεδομένων. |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | Καθορίζει αν η ιδιότητα AsCell ή AsLiteralString ή AsLiteralDouble είναι ενεργή στο αντικείμενο ιδιότητας Value των σημείων δεδομένων. |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | Καθορίζει τους τύπους των τιμών στη λίστα ιδιοτήτων ChartDataPoint.ErrorBarsCustomValues. |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | Εάν η συλλογή περιέχει ήδη σημείο δεδομένων με το δείκτη index, τότε επιστρέφει αυτό το σημείο δεδομένων. |
| [size()](#size--) | Αποκτά τον αριθμό των στοιχείων που πραγματικά περιέχονται στη συλλογή. |
| [copyTo(System.Array array, int arrayIndex)](#copyTo-com.aspose.ms.System.Array-int-) | Αντιγράφει σε καθορισμένο πίνακα. |
| [isSynchronized()](#isSynchronized--) | Επιστρέφει τιμή που υποδεικνύει αν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Επιστρέφει τη ρίζα του συγχρονισμού. |
| [iterator()](#iterator--) | Επιστρέφει έναν ενομέα που διατρέχει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. |
| [clear()](#clear--) | Αφαιρεί όλα τα στοιχεία από τη συλλογή. |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | Αφαιρεί την καθορισμένη τιμή. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί το στοιχείο στον δεδομένο δείκτη. |

### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

Επιστρέφει το σημείο δεδομένων της σειράς βάσει δείκτη (τον σειριακό αριθμό του σε αυτή τη συλλογή).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)

### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public final int get_Item(IChartDataPoint pt)
```

Επιστρέφει τον δείκτη (σειριακό αριθμό) του σημείου δεδομένων σε αυτή τη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**Επιστρέφει:**
int

### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public final int getDataSourceTypeForXValues()
```

Καθορίζει αν η ιδιότητα AsCell ή AsLiteralString ή AsLiteralDouble είναι ενεργή στο αντικείμενο ιδιότητας XValue των σημείων δεδομένων. Με άλλα λόγια καθορίζει τον τύπο της τιμής της ιδιότητας ChartDataPoint.XValue.Data. Ανάγνωση/Εγγραφή [DataSourceType](../../com.aspose.slides/datasourcetype).

**Επιστρέφει:**
int

### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public final void setDataSourceTypeForXValues(int value)
```

Καθορίζει αν η ιδιότητα AsCell ή AsLiteralString ή AsLiteralDouble είναι ενεργή στο αντικείμενο ιδιότητας XValue των σημείων δεδομένων. Με άλλα λόγια καθορίζει τον τύπο της τιμής της ιδιότητας ChartDataPoint.XValue.Data. Ανάγνωση/Εγγραφή [DataSourceType](../../com.aspose.slides/datasourcetype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public final int getDataSourceTypeForYValues()
```

Καθορίζει αν η ιδιότητα AsCell ή AsLiteralString ή AsLiteralDouble είναι ενεργή στο αντικείμενο ιδιότητας YValue των σημείων δεδομένων. Με άλλα λόγια καθορίζει τον τύπο της τιμής της ιδιότητας ChartDataPoint.YValue.Data. Ανάγνωση/Εγγραφή [DataSourceType](../../com.aspose.slides/datasourcetype).

**Επιστρέφει:**
int

### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public final void setDataSourceTypeForYValues(int value)
```

Καθορίζει αν η ιδιότητα AsCell ή AsLiteralString ή AsLiteralDouble είναι ενεργή στο αντικείμενο ιδιότητας YValue των σημείων δεδομένων. Με άλλα λόγια καθορίζει τον τύπο της τιμής της ιδιότητας ChartDataPoint.YValue.Data. Ανάγνωση/Εγγραφή [DataSourceType](../../com.aspose.slides/datasourcetype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public final int getDataSourceTypeForBubbleSizes()
```

Καθορίζει αν η ιδιότητα AsCell ή AsLiteralString ή AsLiteralDouble είναι ενεργή στο αντικείμενο ιδιότητας BubbleSize των σημείων δεδομένων. Με άλλα λόγια καθορίζει τον τύπο της τιμής της ιδιότητας ChartDataPoint.BubbleSize.Data. Ανάγνωση/Εγγραφή [DataSourceType](../../com.aspose.slides/datasourcetype).

**Επιστρέφει:**
int

### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public final void setDataSourceTypeForBubbleSizes(int value)
```

Καθορίζει αν η ιδιότητα AsCell ή AsLiteralString ή AsLiteralDouble είναι ενεργή στο αντικείμενο ιδιότητας BubbleSize των σημείων δεδομένων. Με άλλα λόγια καθορίζει τον τύπο της τιμής της ιδιότητας ChartDataPoint.BubbleSize.Data. Ανάγνωση/Εγγραφή [DataSourceType](../../com.aspose.slides/datasourcetype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public final int getDataSourceTypeForValues()
```

Καθορίζει αν η ιδιότητα AsCell ή AsLiteralString ή AsLiteralDouble είναι ενεργή στο αντικείμενο ιδιότητας Value των σημείων δεδομένων. Με άλλα λόγια καθορίζει τον τύπο της τιμής της ιδιότητας ChartDataPoint.Value.Data. Ανάγνωση/Εγγραφή [DataSourceType](../../com.aspose.slides/datasourcetype).

**Επιστρέφει:**
int

### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public final void setDataSourceTypeForValues(int value)
```

Καθορίζει αν η ιδιότητα AsCell ή AsLiteralString ή AsLiteralDouble είναι ενεργή στο αντικείμενο ιδιότητας Value των σημείων δεδομένων. Με άλλα λόγια καθορίζει τον τύπο της τιμής της ιδιότητας ChartDataPoint.Value.Data. Ανάγνωση/Εγγραφή [DataSourceType](../../com.aspose.slides/datasourcetype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public final IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

Καθορίζει τους τύπους των τιμών στη λίστα ιδιοτήτων ChartDataPoint.ErrorBarsCustomValues. Μόνο για ανάγνωση [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues).

**Επιστρέφει:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)

### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public final IChartDataPoint getOrCreateDataPointByIdx(long index)
```

Εάν η συλλογή περιέχει ήδη σημείο δεδομένων με το δείκτη index, τότε επιστρέφει αυτό το σημείο δεδομένων. Εάν η συλλογή δεν περιέχει σημείο δεδομένων με δείκτη index==N (όταν ο αριθμός των σημείων δεδομένων στη συλλογή είναι μικρότερος ή ίσος με N) τότε προσθέτει ελλιπές σημεία δεδομένων και επιστρέφει το τελευταίο (που έχει τον ζητούμενο δείκτη). Για παράδειγμα, οι δείκτες της συλλογής είναι {0, 1, 2}, και ο ζητούμενος δείκτης είναι 5. Τότε η μέθοδος προσθέτει ελλιπές σημεία δεδομένων: {0, 1, 2, 3, 4, 5}. Και επιστρέφει το σημείο δεδομένων με δείκτη 5.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | long | Δείκτης. |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Επιστρέφει το σημείο δεδομένων με τον ζητούμενο δείκτη.

### size() {#size--}
```
public final int size()
```

Αποκτά τον αριθμό των στοιχείων που πραγματικά περιέχονται στη συλλογή. Μόνο για ανάγνωση int.

**Επιστρέφει:**
int

### copyTo(System.Array array, int arrayIndex) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int arrayIndex)
```

Αντιγράφει σε καθορισμένο πίνακα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Πίνακας στον οποίο θα γίνει η αντιγραφή. |
| arrayIndex | int | Δείκτης εκκίνησης αντιγραφής. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Επιστρέφει τιμή που υποδεικνύει αν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Επιστρέφει τη ρίζα του συγχρονισμού. Μόνο για ανάγνωση Object.

**Επιστρέφει:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

Επιστρέφει έναν ενομέα που διατρέχει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - Ένας IGenericEnumerator που μπορεί να χρησιμοποιηθεί για την επανάληψη της συλλογής.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - Ένας java.util.Iterator για ολόκληρη τη συλλογή.

### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένας από τους υποτύπους Stock (δείτε επίσης τη μέθοδο [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-)).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Τιμή του σημείου δεδομένων. |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.

### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public final IChartDataPoint addDataPointForStockSeries(double value)
```

Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένας από τους υποτύπους Stock (δείτε επίσης τη μέθοδο [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-)).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double | Τιμή του σημείου δεδομένων. |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.

### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένας από τους υποτύπους Line (δείτε επίσης τη μέθοδο [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-)).

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Τιμή του σημείου δεδομένων. |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.

### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public final IChartDataPoint addDataPointForLineSeries(double value)
```

Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένας από τους υποτύπους Line (δείτε επίσης τη μέθοδο [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-)).

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double | Τιμή του σημείου δεδομένων. |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.

### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένας από τους υποτύπους Scatter (δείτε επίσης τη μέθοδο [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue σημείου δεδομένων |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.

### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένας από τους υποτύπους Scatter (δείτε επίσης τη μέθοδο [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xValue | double | XValue σημείου δεδομένων |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.

### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένας από τους υποτύπους Scatter (δείτε επίσης τη μέθοδο [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xValue | java.lang.String | XValue σημείου δεδομένων |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.

### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένας από τους υποτύπους Scatter (δείτε επίσης τη μέθοδο [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue σημείου δεδομένων |
| yValue | double | YValue σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.

### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένας από τους υποτύπους Scatter (δείτε επίσης τη μέθοδο [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xValue | double | XValue σημείου δεδομένων |
| yValue | double | YValue σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.

### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένας από τους υποτύπους Scatter (δείτε επίσης τη μέθοδο [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xValue | java.lang.String | XValue σημείου δεδομένων |
| yValue | double | YValue σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.

### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένας από τους υποτύπους Radar (δείτε επίσης τη μέθοδο [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-)).

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Τιμή του σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.

### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public final IChartDataPoint addDataPointForRadarSeries(double value)
```

Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένας από τους υποτύπους Radar (δείτε επίσης τη μέθοδο [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-)).

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double | Τιμή του σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.

### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένας από τους υποτύπους Column ή Bar (δείτε επίσης τις μεθόδους [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) και [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)).

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Τιμή του σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.

### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public final IChartDataPoint addDataPointForBarSeries(double value)
```

Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένας από τους υποτύπους Column ή Bar (δείτε επίσης τις μεθόδους [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) και [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)).

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double | Τιμή του σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.

### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένας από τους υποτύπους Area (δείτε επίσης τη μέθοδο [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-)).

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Τιμή του σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.

### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public final IChartDataPoint addDataPointForAreaSeries(double value)
```

Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένας από τους υποτύπους Area (δείτε επίσης τη μέθοδο [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-)).

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double | Τιμή του σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.

### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένας από τους υποτύπους Pie (δείτε επίσης τη μέθοδο [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-)).

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Τιμή του σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.

### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public final IChartDataPoint addDataPointForPieSeries(double value)
```

Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένας από τους υποτύπους Pie (δείτε επίσης τη μέθοδο [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-)).

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double | Τιμή του σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.

### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένας από τους υποτύπους Doughnut (δείτε επίσης τη μέθοδο [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-)).

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Τιμή του σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.

### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(double value)
```

Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένας από τους υποτύπους Doughnut (δείτε επίσης τη μέθοδο [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-)).

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double | Τιμή του σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένας από τους υποτύπους Bubble (δείτε επίσης τη μέθοδο [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue σημείου δεδομένων |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue σημείου δεδομένων |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένας από τους υποτύπους Bubble (δείτε επίσης τη μέθοδο [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xValue | double | XValue σημείου δεδομένων |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue σημείου δεδομένων |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένας από τους υποτύπους Bubble (δείτε επίσης τη μέθοδο [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xValue | java.lang.String | XValue σημείου δεδομένων |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue σημείου δεδομένων |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένας από τους υποτύπους Bubble (δείτε επίσης τη μέθοδο [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue σημείου δεδομένων |
| yValue | double | YValue σημείου δεδομένων |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.

### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένας από τους υποτύπους Bubble (δείτε επίσης τη μέθοδο [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xValue | double | XValue σημείου δεδομένων |
| yValue | double | YValue σημείου δεδομένων |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.

### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένας από τους υποτύπους Bubble (δείτε επίσης τη μέθοδο [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xValue | java.lang.String | XValue σημείου δεδομένων |
| yValue | double | YValue σημείου δεδομένων |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```

Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένας από τους υποτύπους Bubble (δείτε επίσης τη μέθοδο [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue σημείου δεδομένων |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue σημείου δεδομένων |
| bubbleSize | double | BubbleSize σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```

Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένας από τους υποτύπους Bubble (δείτε επίσης τη μέθοδο [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xValue | double | XValue σημείου δεδομένων |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue σημείου δεδομένων |
| bubbleSize | double | BubbleSize σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```

Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένας από τους υποτύπους Bubble (δείτε επίσης τη μέθοδο [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xValue | java.lang.String | XValue σημείου δεδομένων |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue σημείου δεδομένων |
| bubbleSize | double | BubbleSize σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```

Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένας από τους υποτύπους Bubble (δείτε επίσης τη μέθοδο [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue σημείου δεδομένων |
| yValue | double | YValue σημείου δεδομένων |
| bubbleSize | double | BubbleSize σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.

### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```

Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένας από τους υποτύπους Bubble (δείτε επίσης τη μέθοδο [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xValue | double | XValue σημείου δεδομένων |
| yValue | double | YValue σημείου δεδομένων |
| bubbleSize | double | BubbleSize σημίου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.

### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```

Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένας από τους υποτύπους Bubble (δείτε επίσης τη μέθοδο [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xValue | java.lang.String | XValue σημείου δεδομένων |
| yValue | double | YValue σημείου δεδομένων |
| bubbleSize | double | BubbleSize σημίου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.

### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```

Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένας από τους υποτύπους Surface (δείτε επίσης τη μέθοδο [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-)).

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Τιμή του σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.

### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(double value)
```

Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων το chartType είναι ένας από τους υποτύπους Surface (δείτε επίσης τη μέθοδο [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-)).

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double | Τιμή του σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.

### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```

Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων ο τύπος γραφήματος είναι Sunburst.

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | SizeValue σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.

### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```

Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων ο τύπος γραφήματος είναι Treemap.

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | SizeValue σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.

### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```

Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων ο τύπος γραφήματος είναι BoxAndWhisker.

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Τιμή του σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.

### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```

Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων ο τύπος γραφήματος είναι Waterfall.

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Τιμή του σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.

### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```

Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων ο τύπος γραφήματος είναι Histogram.

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Τιμή του σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.

### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων ο τύπος γραφήματος είναι Funnel.

**Παράμετρος:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Τιμή του σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.

### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```

Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Εφαρμόσιμο για σειρές των οποίων ο τύπος γραφήματος είναι Map.

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
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | ColorValue σημείου δεδομένων |

**Επιστρέφει:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Νέο σημείο δεδομένων.

### clear() {#clear--}
```
public final void clear()
```

Αφαιρεί όλα τα στοιχεία από τη συλλογή.

### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public final void remove(IChartDataPoint value)
```

Αφαιρεί την καθορισμένη τιμή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Η τιμή. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Αφαιρεί το στοιχείο στον δεδομένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης σημείου δεδομένων για αφαίρεση. |