---
title: IChartSeriesGroup
second_title: Aspose.Sildes για .NET API Αναφορά
description: Αναπαριστά ομάδα σειρών.
type: docs
weight: 1930
url: /el/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup διασύνδεση

Αναπαριστά ομάδα σειρών.

```csharp
public interface IChartSeriesGroup : IChartComponent
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | Επιστρέφει την βασική διεπαφή IChartComponent. Μόνο για ανάγνωση [`IChartComponent`](../ichartcomponent). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | Καθορίζει πώς αντιπροσωπεύονται οι τιμές μεγέθους φυσαλίδων στο γράφημα φυσαλίδων. Ανάγνωση/Εγγραφή [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | Καθορίζει τον συντελεστή κλίμακας για το γράφημα φυσαλίδων (μπορεί να είναι μεταξύ 0 και 300 τοις εκατό του προεπιλεγμένου μεγέθους). Ανάγνωση/Εγγραφή Int32. |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | Καθορίζει το μέγεθος της τρύπας σε γράφημα δακτυλίου (μπορεί να είναι μεταξύ 10 και 90 τοις εκατό του μεγέθους της περιοχής σχεδίασης). Ανάγνωση/Εγγραφή Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | Ανακτά ή ορίζει τη γωνία του πρώτου κομματιού του πίτας ή του δακτυλίου, σε μοίρες (δεξιόστροφα από την κορυφή, από 0 έως 360 μοίρες). Ανάγνωση/Εγγραφή UInt16. |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | Ανακτά ή ορίζει την απόσταση, ως ποσοστό του πλάτους του δείκτη, μεταξύ των σειρών δεδομένων σε γράφημα 3Δ. Ανάγνωση/Εγγραφή UInt16. |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | Καθορίζει το διάστημα μεταξύ ομάδων ράβδων ή στηλών, ως ποσοστό του πλάτους της ράβδου ή της στήλης. Ανάγνωση/Εγγραφή UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | Αληθές εάν το γράφημα περιέχει γραμμές σειρών. Εφαρμόζεται σε στοίβαξη ράβδων και γραφήματα OfPie. Ανάγνωση/Εγγραφή Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | Καθορίζει τη μορφή HiLowLines. HiLowLines εφαρμόζεται με τους τύπους γραφημάτων HiLowClose, OpenHiLowClose, VolumeHiLowClose και VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | Καθορίζει ότι κάθε δείκτης δεδομένων στη σειρά έχει διαφορετικό χρώμα. Ανάγνωση/Εγγραφή Boolean. |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | Ανακτά το στοιχείο στο καθορισμένο δείκτη. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | Καθορίζει το πόσο θα επικαλύπτονται οι ράβδοι και οι στήλες σε 2-Δ γραφήματα, ως ποσοστό (από -100% έως 100%). - -100%: Μέγιστο διάστημα (οι ράβδοι είναι πλήρως διαχωρισμένες). - 0%: Οι ράβδοι τοποθετούνται δίπλα-δίπλα χωρίς επικάλυψη ή διάστημα. - 100%: Μέγιστη επικάλυψη (οι ράβδοι επικάλυπτουν πλήρως η μία την άλλη). Αυτή η ιδιότητα είναι ανάγνωση/εγγραφή SByte. |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | Καθορίζει πώς να προσδιοριστούν τα σημεία δεδομένων που βρίσκονται στο δεύτερο κομμάτι ή ράβδο σε γράφημα pie-of-pie ή bar-of-pie. Ανάγνωση/Εγγραφή [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | Οι προσαρμοσμένες πληροφορίες διαίρεσης για γράφημα pie-of-pie ή bar-of-pie με προσαρμοσμένη διαίρεση. Περιέχει τα σημεία δεδομένων που θα σχεδιαστούν στο δεύτερο κομμάτι ή ράβδο σε γράφημα pie-of-pie ή bar-of-pie. Μόνο για ανάγνωση [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | Καθορίζει μια τιμή που θα χρησιμοποιηθεί για τον προσδιορισμό των σημείων δεδομένων που βρίσκονται στο δεύτερο κομμάτι ή ράβδο σε γράφημα pie-of-pie ή bar-of-pie. Χρησιμοποιείται μαζί με την ιδιότητα PieSplitBy. Ανάγνωση/Εγγραφή Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | Δείχνει εάν οι σειρές αυτής της ομάδας σχεδιάζονται σε δευτερεύοντα άξονα. Μόνο για ανάγνωση Boolean. |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | Καθορίζει το μέγεθος του δεύτερου κομματιού ή ράβδου σε γράφημα pie-of-pie ή bar-of-pie, ως ποσοστό του μεγέθους της πρώτης πίτας (μπορεί να είναι μεταξύ 5 και 200 τοις εκατό). Ανάγνωση/Εγγραφή UInt16. |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | Ανακτά μια συλλογή μόνο για ανάγνωση των σειρών γραφήματος. Μόνο για ανάγνωση [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | Ανακτά έναν τύπο αυτής της ομάδας σειρών. Μόνο για ανάγνωση [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | Παρέχει πρόσβαση στις γραμμές άνω/κάτω των γραφημάτων Γραμμής ή Στοκ. Μόνο για ανάγνωση [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Παρατηρήσεις

1) Δείτε τη σύνοψη και τις παρατηρήσεις για την κλάση ChartSeriesGroupCollection και το enum CombinableSeriesTypesGroup. 2) Η ομάδα σειρών περιέχει ορισμένες ιδιότητες σειρών που είναι κοινές για κάθε σειρά στην ομάδα («ιδιότητες ομάδας σειρών»). Οι «ιδιότητες ομάδας σειρών» στην κλάση ChartSeriesGroup είναι ανάγνωση/εγγραφή. Κάθε μία από τις «ιδιότητες ομάδας σειρών» μπορεί να έχει μια προβολή μόνο για ανάγνωση στην κλάση ChartSeries.

### Δείτε επίσης

* διασύνδεση [IChartComponent](../ichartcomponent)
* χώρο ονομάτων [Aspose.Slides.Charts](../../aspose.slides.charts)
* συγκρότηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->