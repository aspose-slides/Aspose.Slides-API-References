---
title: IChartSeriesGroup
second_title: Aspose.Sildes για .NET API Αναφορά
description: Αντιπροσωπεύει την ομάδα σειρών.
type: docs
weight: 1950
url: /el/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup διεπαφή

Αντιπροσωπεύει την ομάδα σειρών.

```csharp
public interface IChartSeriesGroup : IChartComponent
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | Επ αίνει την ανάκτηση της βασικής διεπαφής IChartComponent. Μόνο για ανάγνωση [`IChartComponent`](../ichartcomponent). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | Καθορίζει πώς οι τιμές μεγέθους φυσαλίδων παρουσιάζονται στο γράφημα φυσαλίδων. Ανάγνωση/εγγραφή [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | Καθορίζει τον παράγοντα κλίμακας για το γράφημα φυσαλίδων (μπορεί να κυμαίνεται μεταξύ 0 και 300 τοις εκατό του προεπιλεγμένου μεγέθους). Ανάγνωση/εγγραφή Int32. |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | Καθορίζει το μέγεθος της τρύπας σε διάγραμμα δακτυλίου (μπορεί να κυμαίνεται μεταξύ 10 και 90 τοις εκατό του μεγέθους της περιοχής σχεδίασης). Ανάγνωση/εγγραφή Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | Ανακτά ή ορίζει τη γωνία του πρώτου τμήματος πίτας ή δακτυλίου, σε μοίρες (δεξιόστροφα από την κορυφή, από 0 έως 360 μοίρες). Ανάγνωση/εγγραφή UInt16. |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | Ανακτά ή ορίζει την απόσταση, ως ποσοστό του πλάτους του δείκτη, μεταξύ των σειρών δεδομένων σε 3D γράφημα. Ανάγνωση/εγγραφή UInt16. |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | Καθορίζει το κενό μεταξύ ομάδων ράβδων ή στηλών, ως ποσοστό του πλάτους της ράβδου ή της στήλης. Ανάγνωση/εγγραφή UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | Αληθές εάν το γράφημα διαθέτει γραμμές σειρών. Εφαρμόζεται σε στοίβαγμα ράβδων και διαγράμματα OfPie. Ανάγνωση/εγγραφή Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | Καθορίζει τη μορφή HiLowLines. Οι HiLowLines εφαρμόζονται με τους τύπους διαγραμμάτων HiLowClose, OpenHiLowClose, VolumeHiLowClose και VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | Καθορίζει ότι κάθε δείκτης δεδομένων στη σειρά έχει διαφορετικό χρώμα. Ανάγνωση/εγγραφή Boolean. |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | Ανακτά το στοιχείο στο καθορισμένο δείκτη. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | Καθορίζει το πόσο οι ράβδοι και οι στήλες θα επικαλύπτονται σε 2-Δ γραφήματα, ως ποσοστό (από -100% έως 100%). - -100%: Μέγιστο κενό (οι ράβδοι είναι εντελώς χωρισμένες). - 0%: Οι ράβδοι τοποθετούνται δίπλα-πλάι χωρίς επικάλυψη ή κενό. - 100%: Μέγιστη επικάλυψη (οι ράβδοι επικαλύπτονται πλήρως). Αυτή η ιδιότητα είναι ανάγνωση/εγγραφή SByte. |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | Καθορίζει πώς να προσδιοριστούν τα σημεία δεδομένων που βρίσκονται στη δεύτερη πίτα ή ράβδο σε διάγραμμα pie-of-pie ή bar-of-pie. Ανάγνωση/εγγραφή [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | Οι προσαρμοσμένες πληροφορίες διαχωρισμού για ένα διάγραμμα pie-of-pie ή bar-of-pie με προσαρμοσμένο διαχωρισμό. Περιέχει τα σημεία δεδομένων που θα σχεδιαστούν στη δεύτερη πίτα ή ράβδο σε τέτοιο διάγραμμα. Μόνο για ανάγνωση [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | Καθορίζει μια τιμή που θα χρησιμοποιηθεί για τον προσδιορισμό των σημείων δεδομένων που βρίσκονται στη δεύτερη πίτα ή ράβδο σε διάγραμμα pie-of-pie ή bar-of-pie. Χρησιμοποιείται μαζί με την ιδιότητα PieSplitBy. Ανάγνωση/εγγραφή Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | Δείχνει αν οι σειρές αυτής της ομάδας σχεδιάζονται στον δευτερεύοντα άξονα. Μόνο για ανάγνωση Boolean. |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | Καθορίζει το μέγεθος της δεύτερης πίτας ή ράβδου σε διάγραμμα pie-of-pie ή bar-of-pie, ως ποσοστό του μεγέθους της πρώτης πίτας (μπορεί να κυμαίνεται μεταξύ 5 και 200 τοις εκατό). Ανάγνωση/εγγραφή UInt16. |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | Ανακτά μια αμετάβλητη συλλογή σειρών γραφήματος. Μόνο για ανάγνωση [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | Ανακτά τον τύπο αυτής της ομάδας σειρών. Μόνο για ανάγνωση [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | Παρέχει πρόσβαση σε επάνω/κάτω ράβδους γραμμικού ή χρηματιστηριακού διαγράμματος. Μόνο για ανάγνωση [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Σχόλια

1) Δείτε την περίληψη και τα σχόλια για την κλάση ChartSeriesGroupCollection και το enum CombinableSeriesTypesGroup. 2) Η ομάδα σειρών περιέχει ορισμένες ιδιότητες σειρών που είναι κοινές για κάθε σειρά στην ομάδα («ιδιότητες ομάδας σειρών»). Οι «ιδιότητες ομάδας σειρών» στην κλάση ChartSeriesGroup είναι ανάγνωση/εγγραφή. Κάθε μία από τις «ιδιότητες ομάδας σειρών» μπορεί να έχει μια αμετάβλητη προβολή στην κλάση ChartSeries.

### Δείτε επίσης

* διεπαφή [IChartComponent](../ichartcomponent)
* χώρος ονομάτων [Aspose.Slides.Charts](../../aspose.slides.charts)
* συναρμολόγηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->