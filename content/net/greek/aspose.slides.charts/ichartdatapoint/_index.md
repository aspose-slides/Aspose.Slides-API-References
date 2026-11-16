---
title: IChartDataPoint
second_title: Aspose.Sildes για .NET API Αναφορά
description: Αντιπροσωπεύει το σημείο δεδομένων σειράς.
type: docs
weight: 1840
url: /el/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint διασύνδεση

Αντιπροσωπεύει το σημείο δεδομένων σειράς.

```csharp
public interface IChartDataPoint : IActualLayout
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AsIActualLayout](../../aspose.slides.charts/ichartdatapoint/asiactuallayout) { get; } | Επιστρέφει τη διεπαφή IActualLayout. |
| [BubbleSize](../../aspose.slides.charts/ichartdatapoint/bubblesize) { get; } | Λαμβάνει το μέγεθος της φυσαλίδας ενός σημείου δεδομένων γραφήματος. Μόνο για ανάγνωση [`IDoubleChartValue`](../idoublechartvalue). |
| [CachedBubbleSize](../../aspose.slides.charts/ichartdatapoint/cachedbubblesize) { get; } | Λαμβάνει το αποθηκευμένο μέγεθος της φυσαλίδας ενός σημείου δεδομένων γραφήματος. Μόνο για ανάγνωση [`ICachedChartValue`](../icachedchartvalue). |
| [CachedValue](../../aspose.slides.charts/ichartdatapoint/cachedvalue) { get; } | Λαμβάνει την αποθηκευμένη τιμή ενός σημείου δεδομένων γραφήματος. Μόνο για ανάγνωση [`ICachedChartValue`](../icachedchartvalue). |
| [CachedXValue](../../aspose.slides.charts/ichartdatapoint/cachedxvalue) { get; } | Λαμβάνει την αποθηκευμένη τιμή X ενός σημείου δεδομένων γραφήματος. Μόνο για ανάγνωση [`ICachedChartValue`](../icachedchartvalue). |
| [CachedYValue](../../aspose.slides.charts/ichartdatapoint/cachedyvalue) { get; } | Λαμβάνει την αποθηκευμένη τιμή Y ενός σημείου δεδομένων γραφήματος. Μόνο για ανάγνωση [`ICachedChartValue`](../icachedchartvalue). |
| [ColorValue](../../aspose.slides.charts/ichartdatapoint/colorvalue) { get; } | Λαμβάνει την τιμή χρώματος ενός σημείου δεδομένων γραφήματος. Χρησιμοποιείται με γραφήματα Χάρτη. Μόνο για ανάγνωση [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/ichartdatapoint/datapointlevels) { get; } | Επιστρέφει το δοχείο των επιπέδων σημείου δεδομένων. Εφαρμόζεται για σειρές Treeamp και Sunburst. Η αρίθμηση των επιπέδων σημείου δεδομένων είναι μηδενική. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/ichartdatapoint/errorbarscustomvalues) { get; } | Αναπαριστά τις τιμές των γραμμών σφάλματος της σειράς σε περίπτωση τιμής τύπου Custom. Μόνο για ανάγνωση [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/ichartdatapoint/explosion) { get; set; } | Καθορίζει το ποσό κατά το οποίο το σημείο δεδομένων θα μετακινηθεί από το κέντρο του πίτας. Ανάγνωση/εγγραφή Int32. |
| [Format](../../aspose.slides.charts/ichartdatapoint/format) { get; set; } | Αναπαριστά τις ιδιότητες μορφοποίησης. Ανάγνωση/εγγραφή [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/ichartdatapoint/index) { get; } | Καθορίζει σε ποια συλλογή παιδιών του γονέα εφαρμόζεται αυτό το σημείο δεδομένων. Ανάγνωση UInt32. |
| [InvertIfNegative](../../aspose.slides.charts/ichartdatapoint/invertifnegative) { get; set; } | Καθορίζει ότι το σημείο δεδομένων θα αντιστρέψει τα χρώματά του εάν η τιμή είναι αρνητική. Ανάγνωση/εγγραφή Boolean. |
| [IsBubble3D](../../aspose.slides.charts/ichartdatapoint/isbubble3d) { get; set; } | Καθορίζει ότι οι φυσαλίδες έχουν εφαρμοσμένο εφέ 3D. Ανάγνωση/εγγραφή Boolean. |
| [Label](../../aspose.slides.charts/ichartdatapoint/label) { get; } | Αναπαριστά την ετικέτα του σημείου δεδομένων γραφήματος. Μόνο για ανάγνωση [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/ichartdatapoint/marker) { get; } | Καθορίζει έναν δείκτη δεδομένων. Μόνο για ανάγνωση [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartdatapoint/relatedlegendentry) { get; } | Ιδιότητες της αντίστοιχης εγγραφής υπομνήματος σε περίπτωση τύπου γραφήματος από αυτή τη λίστα: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Μόνο για ανάγνωση [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/ichartdatapoint/setastotal) { get; set; } | Ορίζει το σημείο δεδομένων ως σύνολο. Εφαρμόζεται μόνο για τύπο σειράς Waterfall. |
| [SizeValue](../../aspose.slides.charts/ichartdatapoint/sizevalue) { get; } | Λαμβάνει την τιμή μεγέθους ενός σημείου δεδομένων γραφήματος. Χρησιμοποιείται με γραφήματα Treemap και Sunburst. Μόνο για ανάγνωση [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/ichartdatapoint/value) { get; } | Λαμβάνει την τιμή ενός σημείου δεδομένων γραφήματος. Μόνο για ανάγνωση [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/ichartdatapoint/xvalue) { get; } | Λαμβάνει την τιμή x ενός σημείου δεδομένων γραφήματος. Μόνο για ανάγνωση [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/ichartdatapoint/yvalue) { get; } | Λαμβάνει την τιμή y ενός σημείου δεδομένων γραφήματος. Μόνο για ανάγνωση [`IDoubleChartValue`](../idoublechartvalue). |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/ichartdatapoint/getautomaticdatapointcolor)() | Επιστρέφει ένα αυτόματο χρώμα του σημείου δεδομένων βάσει του δείκτη σειράς, του δείκτη σημείου δεδομένων, της ιδιότητας ParentSeriesGroup.IsColorVaried και του στυλ γραφήματος. Αυτό το χρώμα χρησιμοποιείται εξ ορισμού εάν το FillType είναι ίσο με NotDefined. |
| [Remove](../../aspose.slides.charts/ichartdatapoint/remove)() | Αφαιρεί το DataPoint από τη σειρά γραφήματος. |

### Δείτε επίσης

* διασύνδεση [IActualLayout](../iactuallayout)
* χώρο ονομάτων [Aspose.Slides.Charts](../../aspose.slides.charts)
* συγκρότημα [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->