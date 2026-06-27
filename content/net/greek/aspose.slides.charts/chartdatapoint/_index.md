---
title: ChartDataPoint
second_title: Aspose.Sildes για .NET API Αναφορά
description: Αναπαριστά το σημείο δεδομένων σειράς.
type: docs
weight: 1310
url: /el/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint κλάση

Represents series data point.

```csharp
public class ChartDataPoint : IChartDataPoint
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/chartdatapoint/actualheight) { get; } | Καθορίζει το πραγματικό ύψος του στοιχείου του διαγράμματος. Καλέστε τη μέθοδο IChart.ValidateChartLayout() πριν για να λάβετε τις πραγματικές τιμές. Διαβάστε Single. |
| [ActualWidth](../../aspose.slides.charts/chartdatapoint/actualwidth) { get; } | Καθορίζει το πραγματικό πλάτος του στοιχείου του διαγράμματος. Καλέστε τη μέθοδο IChart.ValidateChartLayout() πριν για να λάβετε τις πραγματικές τιμές. Διαβάστε Single. |
| [ActualX](../../aspose.slides.charts/chartdatapoint/actualx) { get; } | Καθορίζει την πραγματική θέση x (αριστερά) του στοιχείου του διαγράμματος σε σχέση με την αριστερή άνω γωνία του διαγράμματος. Καλέστε τη μέθοδο IChart.ValidateChartLayout() πριν για να λάβετε τις πραγματικές τιμές. Διαβάστε Single. |
| [ActualY](../../aspose.slides.charts/chartdatapoint/actualy) { get; } | Καθορίζει το πραγματικό πάνω μέρος του στοιχείου του διαγράμματος σε σχέση με την αριστερή άνω γωνία του διαγράμματος. Καλέστε τη μέθοδο IChart.ValidateChartLayout() πριν για να λάβετε τις πραγματικές τιμές. Διαβάστε Single. |
| [BubbleSize](../../aspose.slides.charts/chartdatapoint/bubblesize) { get; } | BubbleSize. Μόνο-ανάγνωση [`IDoubleChartValue`](../idoublechartvalue). |
| [ColorValue](../../aspose.slides.charts/chartdatapoint/colorvalue) { get; } | Επιστρέφει την τιμή χρώματος του σημείου δεδομένων του διαγράμματος. Χρησιμοποιείται με διαγράμματα Χάρτη. Μόνο-ανάγνωση [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/chartdatapoint/datapointlevels) { get; } | Επιστρέφει το περιεχόμενο των επιπέδων του σημείου δεδομένων. Εφαρμόζεται για σειρές Treeamp και Sunburst. Η αρίθμηση των επιπέδων του σημείου δεδομένων είναι μηδενική. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/chartdatapoint/errorbarscustomvalues) { get; } | Αναπαριστά τις τιμές των ράβδων σφάλματος σειράς σε περίπτωση τύπου τιμής Custom. Μόνο-ανάγνωση [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/chartdatapoint/explosion) { get; set; } | Καθορίζει το ποσό κατά το οποίο το σημείο δεδομένων θα μετακινηθεί από το κέντρο του πίτας. Ανάγνωση/εγγραφή Int32. |
| [Format](../../aspose.slides.charts/chartdatapoint/format) { get; set; } | Αναπαριστά τις ιδιότητες μορφοποίησης. Ανάγνωση/εγγραφή [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/chartdatapoint/index) { get; } |  |
| [InvertIfNegative](../../aspose.slides.charts/chartdatapoint/invertifnegative) { get; set; } | Καθορίζει ότι το σημείο δεδομένων θα αντιστρέψει τα χρώματά του αν η τιμή είναι αρνητική. Ανάγνωση/εγγραφή Boolean. |
| [IsBubble3D](../../aspose.slides.charts/chartdatapoint/isbubble3d) { get; set; } | Καθορίζει ότι οι φούσκες έχουν εφαρμοσμένο εφέ 3Δ. Ανάγνωση/εγγραφή Boolean. |
| [Label](../../aspose.slides.charts/chartdatapoint/label) { get; } | Label. Μόνο-ανάγνωση [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/chartdatapoint/marker) { get; } | Καθορίζει έναν δείκτη δεδομένων. Μόνο-ανάγνωση [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/chartdatapoint/relatedlegendentry) { get; } | Ιδιότητες της αντίστοιχης καταχώρησης λεζάντας σε περίπτωση τύπου διαγράμματος από αυτή τη λίστα: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Μόνο-ανάγνωση [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/chartdatapoint/setastotal) { get; set; } | Ορίζει το σημείο δεδομένων ως συνολικό. Εφαρμόζεται μόνο για σειρά τύπου Waterfall. |
| [SizeValue](../../aspose.slides.charts/chartdatapoint/sizevalue) { get; } | Επιστρέφει την τιμή μεγέθους του σημείου δεδομένων του διαγράμματος. Χρησιμοποιείται με διαγράμματα Treemap και Sunburst. Μόνο-ανάγνωση [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/chartdatapoint/value) { get; } | Value. Μόνο-ανάγνωση [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/chartdatapoint/xvalue) { get; } | XValue. Μόνο-ανάγνωση [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/chartdatapoint/yvalue) { get; } | YValue. Μόνο-ανάγνωση [`IDoubleChartValue`](../idoublechartvalue). |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/chartdatapoint/getautomaticdatapointcolor)() | Επιστρέφει ένα αυτόματο χρώμα του σημείου δεδομένων βάσει του δείκτη σειράς, του δείκτη σημείου δεδομένων, της ιδιότητας ParentSeriesGroup.IsColorVaried και του στυλ διαγράμματος. Αυτό το χρώμα χρησιμοποιείται εξ ορισμού εάν το FillType είναι ίσο με NotDefined. |
| [Remove](../../aspose.slides.charts/chartdatapoint/remove)() | Αφαιρεί το DataPoint από τη σειρά του διαγράμματος. |

### Δείτε επίσης

* διεπαφή [IChartDataPoint](../ichartdatapoint)
* χώρο ονομάτων [Aspose.Slides.Charts](../../aspose.slides.charts)
* συναρμολόγηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->