---
title: DataLabelFormat
second_title: Aspose.Sildes για .NET – Αναφορά API
description: Αναπαριστά τις επιλογές μορφοποίησης για το DataLabel.
type: docs
weight: 1550
url: /el/aspose.slides.charts/datalabelformat/
---
## DataLabelFormat κλάση

Αναπαριστά τις επιλογές μορφοποίησης για το DataLabel.

```csharp
public sealed class DataLabelFormat : PVIObject, IDataLabelFormat
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Επιτρέπει τη λήψη της βασικής διεπαφής IPresentationComponent. Μόνο για ανάγνωση [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [Chart](../../aspose.slides.charts/datalabelformat/chart) { get; } | Επιστρέφει το γράφημα. Μόνο για ανάγνωση [`IChart`](../ichart). |
| [Format](../../aspose.slides.charts/datalabelformat/format) { get; } | Αναπαριστά τη μορφή της ετικέτας δεδομένων. Μόνο για ανάγνωση [`IFormat`](../iformat). |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/datalabelformat/isnumberformatlinkedtosource) { get; set; } | Ανάγνωση/εγγραφή Boolean. |
| [NumberFormat](../../aspose.slides.charts/datalabelformat/numberformat) { get; set; } | Αναπαριστά τη συμβολοσειρά μορφής για το αντικείμενο DataLabels. Ανάγνωση/εγγραφή String. |
| [Position](../../aspose.slides.charts/datalabelformat/position) { get; set; } | Αναπαριστά τη θέση της ετικέτας δεδομένων. Ανάγνωση/εγγραφή [`LegendDataLabelPosition`](../legenddatalabelposition). |
| [Separator](../../aspose.slides.charts/datalabelformat/separator) { get; set; } | Ορίζει ή επιστρέφει ένα Variant που αντιπροσωπεύει τον διαχωριστή που χρησιμοποιείται για τις ετικέτες δεδομένων σε ένα γράφημα. Ανάγνωση/εγγραφή String. |
| [ShowBubbleSize](../../aspose.slides.charts/datalabelformat/showbubblesize) { get; set; } | Αναπαριστά τη συμπεριφορά εμφάνισης της τιμής μεγέθους φυσαλίδας της ετικέτας δεδομένων σε ένα συγκεκριμένο γράφημα. True εμφανίζει την τιμή μεγέθους φυσαλίδας. False για απόκρυψη. Ανάγνωση/εγγραφή Boolean. |
| [ShowCategoryName](../../aspose.slides.charts/datalabelformat/showcategoryname) { get; set; } | Αναπαριστά τη συμπεριφορά εμφάνισης του ονόματος κατηγορίας των ετικετών δεδομένων σε ένα συγκεκριμένο γράφημα. True για εμφάνιση του ονόματος κατηγορίας. False για απόκρυψη. Ανάγνωση/εγγραφή Boolean. |
| [ShowLabelAsDataCallout](../../aspose.slides.charts/datalabelformat/showlabelasdatacallout) { get; set; } | Καθορίζει εάν η ετικέτα δεδομένων ενός συγκεκριμένου γραφήματος θα εμφανίζεται ως επισήμανση δεδομένων ή ως ετικέτα δεδομένων. Αν το γονικό αντικείμενο αυτού του DataLabelFormat είναι μια συλλογή DataLabelCollection των ετικετών δεδομένων, τότε αυτή η ιδιότητα παίρνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowLabelAsDataCallout για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ορίζοντας αυτή την ιδιότητα με τιμή, ορίζεται επίσης αυτή η τιμή στην ιδιότητα ShowLabelAsDataCallout για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" προκαλεί ώστε όλα τα DataLabels[i].ShowLabelAsDataCallout να είναι ίσα με val). |
| [ShowLabelValueFromCell](../../aspose.slides.charts/datalabelformat/showlabelvaluefromcell) { get; set; } | Αναπαριστά τη συμπεριφορά εμφάνισης της τιμής κελιού της ετικέτας δεδομένων σε ένα συγκεκριμένο γράφημα. True εμφανίζει την τιμή κελιού. False για απόκρυψη. Ανάγνωση/εγγραφή Boolean. |
| [ShowLeaderLines](../../aspose.slides.charts/datalabelformat/showleaderlines) { get; set; } | Αναπαριστά τη συμπεριφορά εμφάνισης των γραμμών οδηγού της ετικέτας δεδομένων σε ένα συγκεκριμένο γράφημα. True εμφανίζει τις γραμμές οδηγού. False για απόκρυψη. Ανάγνωση/εγγραφή Boolean. |
| [ShowLegendKey](../../aspose.slides.charts/datalabelformat/showlegendkey) { get; set; } | Αναπαριστά τη συμπεριφορά εμφάνισης του κλειδιού υπομνήματος της ετικέτας δεδομένων σε ένα συγκεκριμένο γράφημα. True αν το κλειδί υπομνήματος είναι ορατό. Ανάγνωση/εγγραφή Boolean. |
| [ShowPercentage](../../aspose.slides.charts/datalabelformat/showpercentage) { get; set; } | Αναπαριστά τη συμπεριφορά εμφάνισης της τιμής ποσοστού της ετικέτας δεδομένων σε ένα συγκεκριμένο γράφημα. True εμφανίζει την τιμή ποσοστού. False για απόκρυψη. Ανάγνωση/εγγραφή Boolean. |
| [ShowSeriesName](../../aspose.slides.charts/datalabelformat/showseriesname) { get; set; } | Επιστρέφει ή ορίζει ένα Boolean για τον τρόπο εμφάνισης του ονόματος σειράς στις ετικέτες δεδομένων του γραφήματος. True για εμφάνιση του ονόματος σειράς. False για απόκρυψη. Ανάγνωση/εγγραφή Boolean. |
| [ShowValue](../../aspose.slides.charts/datalabelformat/showvalue) { get; set; } | Αναπαριστά τη συμπεριφορά εμφάνισης της τιμής ποσοστού της ετικέτας δεδομένων σε ένα συγκεκριμένο γράφημα. True εμφανίζει την τιμή ποσοστού. False για απόκρυψη. Ανάγνωση/εγγραφή Boolean. |
| [TextFormat](../../aspose.slides.charts/datalabelformat/textformat) { get; } | Επιστρέφει τη μορφή κειμένου γραφήματος. Μόνο για ανάγνωση [`IChartTextFormat`](../icharttextformat). |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Συγκρίνει με το συγκεκριμένο αντικείμενο. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Επιστρέφει τον κωδικό κατακερματισμού. |

### Δείτε επίσης

* κλάση [PVIObject](../../aspose.slides/pviobject)
* διασύνδεση [IDataLabelFormat](../idatalabelformat)
* χώρος ονομάτων [Aspose.Slides.Charts](../../aspose.slides.charts)
* συγκρότημα [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->