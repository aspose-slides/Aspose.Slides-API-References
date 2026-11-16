---
title: DataLabelFormat
second_title: Aspose.Sildes για .NET API Αναφορά
description: Αναπαριστά τις επιλογές μορφοποίησης για το DataLabel.
type: docs
weight: 1580
url: /el/aspose.slides.charts/datalabelformat/
---
## DataLabelFormat κλάση

Αναπαριστά επιλογές μορφοποίησης για το DataLabel.

```csharp
public sealed class DataLabelFormat : PVIObject, IDataLabelFormat
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Επιτρέπει την ανάκτηση της βασικής διεπαφής IPresentationComponent. Μόνο για ανάγνωση [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [Chart](../../aspose.slides.charts/datalabelformat/chart) { get; } | Επιστρέφει το διάγραμμα. Μόνο για ανάγνωση [`IChart`](../ichart). |
| [Format](../../aspose.slides.charts/datalabelformat/format) { get; } | Αναπαριστά τη μορφή της ετικέτας δεδομένων. Μόνο για ανάγνωση [`IFormat`](../iformat). |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/datalabelformat/isnumberformatlinkedtosource) { get; set; } | Boolean ανάγνωση/εγγραφή. |
| [NumberFormat](../../aspose.slides.charts/datalabelformat/numberformat) { get; set; } | Αναπαριστά τη συμβολοσειρά μορφής για το αντικείμενο DataLabels. Ανάγνωση/εγγραφή String. |
| [Position](../../aspose.slides.charts/datalabelformat/position) { get; set; } | Αναπαριστά τη θέση της ετικέτας δεδομένων. Ανάγνωση/εγγραφή [`LegendDataLabelPosition`](../legenddatalabelposition). |
| [Separator](../../aspose.slides.charts/datalabelformat/separator) { get; set; } | Ορίζει ή επιστρέφει ένα Variant που αντιπροσωπεύει το διαχωριστικό που χρησιμοποιείται για τις ετικέτες δεδομένων σε ένα διάγραμμα. Ανάγνωση/εγγραφή String. |
| [ShowBubbleSize](../../aspose.slides.charts/datalabelformat/showbubblesize) { get; set; } | Αναπαριστά τη συμπεριφορά εμφάνισης της τιμής μεγέθους φυσαλίδας της ετικέτας δεδομένων ενός συγκεκριμένου διαγράμματος. True εμφανίζει την τιμή μεγέθους φυσαλίδας. False κρύβει. Ανάγνωση/εγγραφή Boolean. |
| [ShowCategoryName](../../aspose.slides.charts/datalabelformat/showcategoryname) { get; set; } | Αναπαριστά τη συμπεριφορά εμφάνισης του ονόματος κατηγορίας της ετικέτας δεδομένων ενός συγκεκριμένου διαγράμματος. True εμφανίζει το όνομα κατηγορίας για τις ετικέτες δεδομένων σε ένα διάγραμμα. False κρύβει. Ανάγνωση/εγγραφή Boolean. |
| [ShowLabelAsDataCallout](../../aspose.slides.charts/datalabelformat/showlabelasdatacallout) { get; set; } | Καθορίζει αν η ετικέτα δεδομένων του συγκεκριμένου διαγράμματος θα εμφανίζεται ως υπόδειξη δεδομένων ή ως ετικέτα δεδομένων. Εάν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα λαμβάνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowLabelAsDataCallout για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ο ορισμός αυτής της ιδιότητας με μια τιμή ορίζει επίσης αυτή την τιμή στην ιδιότητα ShowLabelAsDataCallout για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" προκαλεί ώστε όλα τα DataLabels[i].ShowLabelAsDataCallout να είναι ίσα με val). |
| [ShowLabelValueFromCell](../../aspose.slides.charts/datalabelformat/showlabelvaluefromcell) { get; set; } | Αναπαριστά τη συμπεριφορά εμφάνισης της τιμής κελιού της ετικέτας δεδομένων ενός συγκεκριμένου διαγράμματος. True εμφανίζει την τιμή του κελιού. False κρύβει. Ανάγνωση/εγγραφή Boolean. |
| [ShowLeaderLines](../../aspose.slides.charts/datalabelformat/showleaderlines) { get; set; } | Αναπαριστά τη συμπεριφορά εμφάνισης των γραμμών οδηγού της ετικέτας δεδομένων ενός συγκεκριμένου διαγράμματος. True εμφανίζει τις γραμμές οδηγού. False κρύβει. Ανάγνωση/εγγραφή Boolean. |
| [ShowLegendKey](../../aspose.slides.charts/datalabelformat/showlegendkey) { get; set; } | Αναπαριστά τη συμπεριφορά εμφάνισης του κλειδιού υπομνήματος της ετικέτας δεδομένων ενός συγκεκριμένου διαγράμματος. True εάν το κλειδί υπομνήματος ετικέτας δεδομένων είναι ορατό. Ανάγνωση/εγγραφή Boolean. |
| [ShowPercentage](../../aspose.slides.charts/datalabelformat/showpercentage) { get; set; } | Αναπαριστά τη συμπεριφορά εμφάνισης της τιμής ποσοστού της ετικέτας δεδομένων ενός συγκεκριμένου διαγράμματος. True εμφανίζει την τιμή ποσοστού. False κρύβει. Ανάγνωση/εγγραφή Boolean. |
| [ShowSeriesName](../../aspose.slides.charts/datalabelformat/showseriesname) { get; set; } | Επιστρέφει ή ορίζει ένα Boolean για να υποδείξει τη συμπεριφορά εμφάνισης του ονόματος σειράς για τις ετικέτες δεδομένων σε ένα διάγραμμα. True για εμφάνιση του ονόματος σειράς. False για κρυψίματος. Ανάγνωση/εγγραφή Boolean. |
| [ShowValue](../../aspose.slides.charts/datalabelformat/showvalue) { get; set; } | Αναπαριστά τη συμπεριφορά εμφάνισης της τιμής ποσοστού της ετικέτας δεδομένων ενός συγκεκριμένου διαγράμματος. True εμφανίζει την τιμή ποσοστού. False κρύβει. Ανάγνωση/εγγραφή Boolean. |
| [TextFormat](../../aspose.slides.charts/datalabelformat/textformat) { get; } | Επιστρέφει τη μορφή κειμένου διαγράμματος. Μόνο για ανάγνωση [`IChartTextFormat`](../icharttextformat). |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Συγκρίνει με το καθορισμένο αντικείμενο. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Επιστρέφει τον κωδικό κατακερματισμού. |

### Δείτε επίσης

* κλάση [PVIObject](../../aspose.slides/pviobject)
* διεπαφή [IDataLabelFormat](../idatalabelformat)
* χώρο ονομάτων [Aspose.Slides.Charts](../../aspose.slides.charts)
* συναρμολόγηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->