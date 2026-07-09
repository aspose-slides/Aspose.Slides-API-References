---
title: IChartSeries
second_title: Aspose.Sildes για .NET API Αναφορά
description: Αντιπροσωπεύει μια σειρά γραφήματος.
type: docs
weight: 1930
url: /el/aspose.slides.charts/ichartseries/
---
## IChartSeries διασύνδεση

Represents a chart series.

```csharp
public interface IChartSeries : IChartComponent
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseries/asichartcomponent) { get; } | Επιτρέπει την ανάκτηση της βασικής διασύνδεσης IChartComponent. Μόνο για ανάγνωση [`IChartComponent`](../ichartcomponent). |
| [Bar3DShape](../../aspose.slides.charts/ichartseries/bar3dshape) { get; set; } | Καθορίζει το σχήμα μιας σειράς ενός 3-Δ γραφήματος ράβδων. Η αλλαγή της τιμής αυτής της ιδιότητας μπορεί να προκαλέσει αυτόματη αλλαγή του τύπου της σειράς. Ανάγνωση/εγγραφή [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseries/bubblesizerepresentation) { get; } | Καθορίζει πώς αντιπροσωπεύονται οι τιμές μεγέθους της φυσαλίδας στο γράφημα φυσαλίδων. Αυτή η ιδιότητα δεν αφορά μόνο αυτή τη σειρά αλλά και όλες τις σειρές της γονικής ομάδας σειρών - είναι προβολή της αντίστοιχης ιδιότητας της ομάδας. Επομένως αυτή η ιδιότητα είναι μόνο για ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στη γονική ομάδα σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.BubbleSizeRepresentation ανάγνωση/εγγραφή για αλλαγή τιμής. |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseries/bubblesizescale) { get; } | Καθορίζει τον συντελεστή κλίμακας για το γράφημα φυσαλίδων (μπορεί να βρίσκεται μεταξύ 0 και 300 τοις εκατό του προεπιλεγμένου μεγέθους). Αυτή η ιδιότητα δεν αφορά μόνο αυτή τη σειρά αλλά και όλες τις σειρές της γονικής ομάδας σειρών - είναι προβολή της αντίστοιχης ιδιότητας της ομάδας. Επομένως αυτή η ιδιότητα είναι μόνο για ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στη γονική ομάδα σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.BubbleSizeScale ανάγνωση/εγγραφή για αλλαγή τιμής. |
| [DataPoints](../../aspose.slides.charts/ichartseries/datapoints) { get; } | Επιστρέφει τη συλλογή σημείων δεδομένων αυτής της σειράς. Μόνο για ανάγνωση [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseries/doughnutholesize) { get; } | Καθορίζει το μέγεθος της τρύπας σε γράφημα δαχτυλιδιού (μπορεί να είναι μεταξύ 10 και 90 τοις εκατό του μεγέθους της περιοχής σχεδίασης). Αυτή η ιδιότητα δεν αφορά μόνο αυτή τη σειρά αλλά και όλες τις σειρές της γονικής ομάδας σειρών - είναι προβολή της αντίστοιχης ιδιότητας της ομάδας. Επομένως αυτή η ιδιότητα είναι μόνο για ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στη γονική ομάδα σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.DoughnutHoleSize ανάγνωση/εγγραφή για αλλαγή τιμής. Μόνο για ανάγνωση Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/ichartseries/errorbarsxformat) { get; } | Αντιπροσωπεύει τις ErrorBars της σειράς με κατεύθυνση X. Οι ErrorBars με κατεύθυνση X είναι διαθέσιμες για σειρές τύπου area, bar, scatter και bubble. Για οποιουσδήποτε άλλους τύπους γραφήματος αυτή η ιδιότητα επιστρέφει null (συμπεριλαμβανομένων των 3D γραφημάτων). Σε περίπτωση προσαρμοσμένων τιμών χρησιμοποιήστε τη συλλογή DataPoints για να ορίσετε την τιμή (με την ιδιότητα [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). Μόνο για ανάγνωση [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/ichartseries/errorbarsyformat) { get; } | Αντιπροσωπεύει τις ErrorBars της σειράς με κατεύθυνση Y. Οι ErrorBars με κατεύθυνση Y είναι διαθέσιμες για σειρές τύπου area, bar, line, scatter και bubble. Για οποιουσδήποτε άλλους τύπους γραφήματος αυτή η ιδιότητα επιστρέφει null (συμπεριλαμβανομένων των 3D γραφημάτων). Σε περίπτωση προσαρμοσμένων τιμών χρησιμοποιήστε τη συλλογή DataPoints για να ορίσετε την τιμή (με την ιδιότητα [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). Μόνο για ανάγνωση [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/ichartseries/explosion) { get; set; } | Η απόσταση ενός ανοιχτού κομματιού πίτας από το κέντρο του γραφήματος πίτας εκφράζεται ως ποσοστό της διάμετρου της πίτας. Ανάγνωση/εγγραφή Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseries/firstsliceangle) { get; } | Καθορίζει τη γωνία του πρώτου κομματιού πίτας ή δαχτυλιδιού, σε μοίρες (δεξιόστροφα από την κορυφή, από 0 έως 360 μοίρες). Αυτή η ιδιότητα δεν αφορά μόνο αυτή τη σειρά αλλά και όλες τις σειρές της γονικής ομάδας σειρών - είναι προβολή της αντίστοιχης ιδιότητας της ομάδας. Επομένως αυτή η ιδιότητα είναι μόνο για ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στη γονική ομάδα σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.FirstSliceAngle ανάγνωση/εγγραφή για αλλαγή τιμής. Μόνο για ανάγνωση UInt16. |
| [Format](../../aspose.slides.charts/ichartseries/format) { get; } | Επιστρέφει τη μορφή μιας σειράς. Μόνο για ανάγνωση [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/ichartseries/gapdepth) { get; } | Επιστρέφει ή ορίζει την απόσταση, ως ποσοστό του πλάτους του δείκτη, μεταξύ των σειρών δεδομένων σε 3D γράφημα. Αυτή η ιδιότητα δεν αφορά μόνο αυτή τη σειρά αλλά και όλες τις σειρές της γονικής ομάδας σειρών - είναι προβολή της αντίστοιχης ιδιότητας της ομάδας. Επομένως αυτή η ιδιότητα είναι μόνο για ανάγνωση. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup για πρόσβαση στη γονική ομάδα σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.GapDepth ανάγνωση/εγγραφή για αλλαγή τιμής. Μόνο για ανάγνωση Int32. |
| [GapWidth](../../aspose.slides.charts/ichartseries/gapwidth) { get; } | Καθορίζει το κενό μεταξύ ομάδων ράβδων ή στηλών, ως ποσοστό του πλάτους της ράβδου ή της στήλης. Αυτή η ιδιότητα δεν αφορά μόνο αυτή τη σειρά αλλά και όλες τις σειρές της γονικής ομάδας σειρών - είναι προβολή της αντίστοιχης ιδιότητας της ομάδας. Μόνο για ανάγνωση Int32. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseries/hasserieslines) { get; } | Καθορίζει αν υπάρχουν γραμμές σειράς για αυτή τη σειρά και συναφείς σειρές. Αυτή η ιδιότητα δεν αφορά μόνο αυτή τη σειρά αλλά και όλες τις σειρές της γονικής ομάδας σειρών - είναι προβολή της αντίστοιχης ιδιότητας της ομάδας. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.HasSeriesLines ανάγνωση/εγγραφή για αλλαγή τιμής. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.SeriesLinesFormat για μορφοποίηση των γραμμών σειράς. Μόνο για ανάγνωση Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/ichartseries/hasupdownbars) { get; } | Καθορίζει αν ένα διάγραμμα γραμμής ή αποθέματος έχει μπάρες ανοδικής/καθοδικής κίνησης. Αυτή η ιδιότητα δεν αφορά μόνο αυτή τη σειρά αλλά και όλες τις σειρές της γονικής ομάδας σειρών - είναι προβολή της αντίστοιχης ιδιότητας της ομάδας. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.UpDownBars.HasUpDownBars ανάγνωση/εγγραφή για αλλαγή τιμής. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.UpDownBars για μορφοποίηση των μπάρων ανοδικής/καθοδικής κίνησης. Μόνο για ανάγνωση Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/ichartseries/invertedsolidfillcolor) { get; } | Καθορίζει την αντιστροφή του συμπαγούς χρώματος για τη σειρά. Για την εφαρμογή της ρύθμισης χρώματος ορίστε το FillType της μορφής σειράς σε FillType.Solid. Ανάγνωση/εγγραφή [`IColorFormat`](../../aspose.slides/icolorformat). |
| [InvertIfNegative](../../aspose.slides.charts/ichartseries/invertifnegative) { get; set; } | Καθορίζει ότι η σειρά ράβδων, στηλών ή φυσαλίδων θα αντιστρέφει τα χρώματά της εάν η τιμή είναι αρνητική. Ανάγνωση/εγγραφή Boolean. |
| [IsColorVaried](../../aspose.slides.charts/ichartseries/iscolorvaried) { get; } | Καθορίζει ότι κάθε δείκτης δεδομένων στη σειρά έχει διαφορετικό χρώμα. Αυτή η ιδιότητα δεν αφορά μόνο αυτή τη σειρά αλλά και όλες τις σειρές της γονικής ομάδας σειρών - είναι προβολή της αντίστοιχης ιδιότητας της ομάδας. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.IsColorVaried ανάγνωση/εγγραφή για αλλαγή τιμής. Μόνο για ανάγνωση Boolean. |
| [Labels](../../aspose.slides.charts/ichartseries/labels) { get; } | Επιστρέφει τις ετικέτες (Labels) μιας σειράς. Μόνο για ανάγνωση [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/ichartseries/marker) { get; } | Επιστρέφει τον δείκτη σειράς. Μόνο για ανάγνωση [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/ichartseries/name) { get; } | Επιστρέφει το όνομα της σειράς. Μόνο για ανάγνωση [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/ichartseries/numberformatofbubblesizes) { get; set; } | Επιστρέφει ή ορίζει τη μορφή αριθμού για τα μεγέθη φυσαλίδων της σειράς. Ανάγνωση/εγγραφή String. |
| [NumberFormatOfValues](../../aspose.slides.charts/ichartseries/numberformatofvalues) { get; set; } | Επιστρέφει ή ορίζει τη μορφή αριθμού για τις τιμές της σειράς. Ανάγνωση/εγγραφή String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/ichartseries/numberformatofxvalues) { get; set; } | Επιστρέφει ή ορίζει τη μορφή αριθμού για τις τιμές x της σειράς. Ανάγνωση/εγγραφή String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/ichartseries/numberformatofyvalues) { get; set; } | Επιστρέφει ή ορίζει τη μορφή αριθμού για τις τιμές y της σειράς. Ανάγνωση/εγγραφή String. |
| [Order](../../aspose.slides.charts/ichartseries/order) { get; set; } | Επιστρέφει τη σειρά (order) μιας σειράς. Ανάγνωση/εγγραφή Int32. |
| [Overlap](../../aspose.slides.charts/ichartseries/overlap) { get; } | Καθορίζει το πόσο επικάλυψη έχουν οι ράβδοι και οι στήλες σε 2-Δ γραφήματα, ως ποσοστό (από -100% έως 100%). Αυτή η ιδιότητα δεν αφορά μόνο αυτή τη σειρά αλλά και όλες τις σειρές της γονικής ομάδας σειρών - είναι προβολή της αντίστοιχης ιδιότητας της ομάδας. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.Overlap ανάγνωση/εγγραφή. Μόνο για ανάγνωση SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/ichartseries/parentlabellayout) { get; set; } | Αντιπροσωπεύει τη διάταξη των ετικετών της γονικής κατηγορίας. Ισχύει μόνο για γραφήματα Treemap. |
| [ParentSeriesGroup](../../aspose.slides.charts/ichartseries/parentseriesgroup) { get; } | Επιστρέφει τη γονική ομάδα σειρών. Μόνο για ανάγνωση [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/ichartseries/piesplitby) { get; } | Καθορίζει πώς να προσδιοριστεί ποια σημεία δεδομένων βρίσκονται στη δεύτερη πίτα ή μπάρα σε γράφημα pie-of-pie ή bar-of-pie. Αυτή η ιδιότητα δεν αφορά μόνο αυτή τη σειρά αλλά και όλες τις σειρές της γονικής ομάδας σειρών. Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.PieSplitBy ανάγνωση/εγγραφή για αλλαγή τιμής. Μόνο για ανάγνωση [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseries/piesplitcustompoints) { get; } | Οι προσαρμοσμένες πληροφορίες διαχωρισμού για γράφημα pie-of-pie ή bar-of-pie με προσαρμοσμένο διαχωρισμό. Περιέχει σημεία δεδομένων που θα σχεδιαστούν στη δεύτερη πίτα ή μπάρα σε γράφημα pie-of-pie ή bar-of-pie. Αυτή η ιδιότητα ... Μόνο για ανάγνωση [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseries/piesplitposition) { get; } | Καθορίζει μια τιμή που θα χρησιμοποιηθεί για τον προσδιορισμό ποια σημεία δεδομένων βρίσκονται στη δεύτερη πίτα ή μπάρα σε γράφημα pie-of-pie ή bar-of-pie. Χρησιμοποιείται μαζί με την ιδιότητα PieSplitBy. Αυτή η ιδιότητα ... Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.PieSplitPosition ανάγνωση/εγγραφή για αλλαγή τιμής. Μόνο για ανάγνωση Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseries/plotonsecondaxis) { get; set; } | Δείχνει αν αυτή η σειρά σχεδιάζεται στον δεύτερο άξονα τιμών. Ανάγνωση/εγγραφή Boolean. |
| [QuartileMethod](../../aspose.slides.charts/ichartseries/quartilemethod) { get; set; } | Αντιπροσωπεύει τη μέθοδο τεταρτοδείκτη. Ισχύει μόνο για γραφήματα BoxAndWhisker. |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartseries/relatedlegendentry) { get; } | Αντιπροσωπεύει την καταχώρηση υπομνήματος που σχετίζεται με αυτή τη σειρά. Μόνο για ανάγνωση [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/ichartseries/secondpiesize) { get; } | Καθορίζει το μέγεθος της δεύτερης πίτας ή μπάρας σε γράφημα pie-of-pie ή bar-of-pie, ως ποσοστό του μεγέθους της πρώτης πίτας (μπορεί να είναι μεταξύ 5 και 200 τοις εκατό). Αυτή η ιδιότητα ... Χρησιμοποιήστε την ιδιότητα ParentSeriesGroup.SecondPieSize ανάγνωση/εγγραφή για αλλαγή τιμής. Μόνο για ανάγνωση UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/ichartseries/showconnectorlines) { get; set; } | Αντιπροσωπεύει τις γραμμές σύνδεσης. Ισχύει μόνο για γραφήματα Waterfall. |
| [ShowInnerPoints](../../aspose.slides.charts/ichartseries/showinnerpoints) { get; set; } | Αντιπροσωπεύει εσωτερικά σημεία. Αληθές εάν εμφανίζονται εσωτερικά σημεία στο γράφημα BoxAndWhisker. Ισχύει μόνο για γραφήματα BoxAndWhisker. Ανάγνωση/εγγραφή Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/ichartseries/showmeanline) { get; set; } | Αντιπροσωπεύει δείκτες μέσου όρου. Αληθές εάν η γραμμή μέσου εμφανίζεται στο γράφημα BoxAndWhisker. Ισχύει μόνο για γραφήματα BoxAndWhisker. Ανάγνωση/εγγραφή Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/ichartseries/showmeanmarkers) { get; set; } | Αντιπροσωπεύει δείκτες μέσου. Αληθές εάν οι δείκτες μέσου εμφανίζονται στο γράφημα BoxAndWhisker. Ισχύει μόνο για γραφήματα BoxAndWhisker. Ανάγνωση/εγγραφή Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/ichartseries/showoutlierpoints) { get; set; } | Αντιπροσωπεύει σημεία εκτόξευσης. Αληθές εάν τα σημεία εκτόξευσης εμφανίζονται στο γράφημα BoxAndWhisker. Ισχύει μόνο για γραφήματα BoxAndWhisker. Ανάγνωση/εγγραφή Boolean. |
| [Smooth](../../aspose.slides.charts/ichartseries/smooth) { get; set; } | Αντιπροσωπεύει την εξομάλυνση καμπύλης. Αληθές εάν η εξομάλυνση καμπύλης είναι ενεργοποιημένη για το διάγραμμα γραμμής ή scatter. Ισχύει μόνο για γραφήματα γραμμής και scatter σύνδεσης με γραμμές. Ανάγνωση/εγγραφή Boolean. |
| [TrendLines](../../aspose.slides.charts/ichartseries/trendlines) { get; } | Συλλογή γραμμών τάσης σειράς. Μόνο για ανάγνωση [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/ichartseries/type) { get; set; } | Επιστρέφει έναν τύπο αυτής της σειράς. Ανάγνωση/εγγραφή [`ChartType`](../charttype). |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/ichartseries/getautomaticseriescolor)() | Επιστρέφει ένα αυτόματο χρώμα σειράς βάσει του δείκτη σειράς και του στυλ γραφήματος. Αυτό το χρώμα χρησιμοποιείται εξ'ορισμού εάν το FillType είναι ίσο με NotDefined. |

### Δείτε επίσης

* διασύνδεση [IChartComponent](../ichartcomponent)
* χώρο ονομάτων [Aspose.Slides.Charts](../../aspose.slides.charts)
* συναρμολόγηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->