---
title: ChartDataPoint
second_title: Aspose.Sildes για .NET API Αναφορά
description: Αντιπροσωπεύει το σημείο δεδομένων σειράς.
type: docs
weight: 1340
url: /el/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint κλάση

Represents series data point.

```csharp
public class ChartDataPoint : IChartDataPoint
```

## Ιδιότητες

| Name | Description |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/chartdatapoint/actualheight) { get; } | Καθορίζει το πραγματικό ύψος του στοιχείου γραφήματος. Καλέστε τη μέθοδο IChart.ValidateChartLayout() πριν για να λάβετε τις πραγματικές τιμές. Μόνο-ανάγνωση Single. |
| [ActualWidth](../../aspose.slides.charts/chartdatapoint/actualwidth) { get; } | Καθορίζει το πραγματικό πλάτος του στοιχείου γραφήματος. Καλέστε τη μέθοδο IChart.ValidateChartLayout() πριν για να λάβετε τις πραγματικές τιμές. Μόνο-ανάγνωση Single. |
| [ActualX](../../aspose.slides.charts/chartdatapoint/actualx) { get; } | Καθορίζει την πραγματική θέση x (αριστερά) του στοιχείου γραφήματος σε σχέση με την αριστερή επάνω γωνία του γραφήματος. Καλέστε τη μέθοδο IChart.ValidateChartLayout() πριν για να λάβετε τις πραγματικές τιμές. Μόνο-ανάγνωση Single. |
| [ActualY](../../aspose.slides.charts/chartdatapoint/actualy) { get; } | Καθορίζει το πραγματικό πάνω μέρος του στοιχείου γραφήματος σε σχέση με την αριστερή επάνω γωνία του γραφήματος. Καλέστε τη μέθοδο IChart.ValidateChartLayout() πριν για να λάβετε τις πραγματικές τιμές. Μόνο-ανάγνωση Single. |
| [BubbleSize](../../aspose.slides.charts/chartdatapoint/bubblesize) { get; } | BubbleSize. Μόνο-ανάγνωση [`IDoubleChartValue`](../idoublechartvalue). |
| [CachedBubbleSize](../../aspose.slides.charts/chartdatapoint/cachedbubblesize) { get; } | Λαμβάνει το αποθηκευμένο μέγεθος φυσαλίδας ενός σημείου δεδομένων γραφήματος. Μόνο-ανάγνωση [`ICachedChartValue`](../icachedchartvalue). |
| [CachedValue](../../aspose.slides.charts/chartdatapoint/cachedvalue) { get; } | Λαμβάνει την αποθηκευμένη τιμή ενός σημείου δεδομένων γραφήματος. Μόνο-ανάγνωση [`ICachedChartValue`](../icachedchartvalue). |
| [CachedXValue](../../aspose.slides.charts/chartdatapoint/cachedxvalue) { get; } | Λαμβάνει την αποθηκευμένη τιμή X ενός σημείου δεδομένων γραφήματος. Μόνο-ανάγνωση [`ICachedChartValue`](../icachedchartvalue). |
| [CachedYValue](../../aspose.slides.charts/chartdatapoint/cachedyvalue) { get; } | Λαμβάνει την αποθηκευμένη τιμή Y ενός σημείου δεδομένων γραφήματος. Μόνο-ανάγνωση [`ICachedChartValue`](../icachedchartvalue). |
| [ColorValue](../../aspose.slides.charts/chartdatapoint/colorvalue) { get; } | Επιστρέφει την τιμή χρώματος του σημείου δεδομένων γραφήματος. Χρησιμοποιείται με χάρτες Map. Μόνο-ανάγνωση [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/chartdatapoint/datapointlevels) { get; } | Επιστρέφει το κοντέινερ των επιπέδων σημείων δεδομένων. Εφαρμόζεται για σειρές Treeamp και Sunburst. Η αρίθμηση των επιπέδων σημείου δεδομένων είναι μηδενική. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/chartdatapoint/errorbarscustomvalues) { get; } | Αναπαριστά τις τιμές των γραμμών σφάλματος σειράς σε περίπτωση προσαρμοσμένου τύπου τιμής. Μόνο-ανάγνωση [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/chartdatapoint/explosion) { get; set; } | Καθορίζει το ποσό με το οποίο το σημείο δεδομένων πρέπει να μετακινηθεί από το κέντρο της πίτας. Ανάγνωση/εγγραφή Int32. |
| [Format](../../aspose.slides.charts/chartdatapoint/format) { get; set; } | Αναπαριστά τις ιδιότητες μορφοποίησης. Ανάγνωση/εγγραφή [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/chartdatapoint/index) { get; } |  |
| [InvertIfNegative](../../aspose.slides.charts/chartdatapoint/invertifnegative) { get; set; } | Καθορίζει ότι το σημείο δεδομένων θα αντιστρέψει τα χρώματά του εάν η τιμή είναι αρνητική. Ανάγνωση/εγγραφή Boolean. |
| [IsBubble3D](../../aspose.slides.charts/chartdatapoint/isbubble3d) { get; set; } | Καθορίζει ότι οι φυσαλίδες έχουν εφαρμοσμένο εφέ 3-Δ. Ανάγνωση/εγγραφή Boolean. |
| [Label](../../aspose.slides.charts/chartdatapoint/label) { get; } | Label. Μόνο-ανάγνωση [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/chartdatapoint/marker) { get; } | Καθορίζει έναν δείκτη δεδομένων. Μόνο-ανάγνωση [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/chartdatapoint/relatedlegendentry) { get; } | Ιδιότητες της αντίστοιχης εισόδου υπομνήματος σε περίπτωση τύπου γραφήματος από αυτή τη λίστα: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Μόνο-ανάγνωση [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/chartdatapoint/setastotal) { get; set; } | Ορίζει το σημείο δεδομένων ως σύνολο. Εφαρμόζεται μόνο για τύπο σειράς Waterfall. |
| [SizeValue](../../aspose.slides.charts/chartdatapoint/sizevalue) { get; } | Επιστρέφει την τιμή μεγέθους του σημείου δεδομένων γραφήματος. Χρησιμοποιείται με γραφήματα Treemap και Sunburst. Μόνο-ανάγνωση [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/chartdatapoint/value) { get; } | Value. Μόνο-ανάγνωση [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/chartdatapoint/xvalue) { get; } | XValue. Μόνο-ανάγνωση [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/chartdatapoint/yvalue) { get; } | YValue. Μόνο-ανάγνωση [`IDoubleChartValue`](../idoublechartvalue). |

## Μέθοδοι

| Name | Description |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/chartdatapoint/getautomaticdatapointcolor)() | Επιστρέφει ένα αυτόματο χρώμα του σημείου δεδομένων βάσει του δείκτη σειράς, του δείκτη σημείου δεδομένων, της ιδιότητας ParentSeriesGroup.IsColorVaried και του στυλ γραφήματος. Αυτό το χρώμα χρησιμοποιείται από προεπιλογή εάν το FillType είναι NotDefined. |
| [Remove](../../aspose.slides.charts/chartdatapoint/remove)() | Αφαιρεί το DataPoint από τη σειρά γραφήματος. |

### Δείτε επίσης

* διασύνδεση [IChartDataPoint](../ichartdatapoint)
* χώρο ονομάτων [Aspose.Slides.Charts](../../aspose.slides.charts)
* συστατικό [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->