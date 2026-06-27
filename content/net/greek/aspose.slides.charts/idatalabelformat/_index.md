---
title: IDataLabelFormat
second_title: Aspose.Sildes για .NET API Αναφορά
description: Αναπαριστά τις επιλογές μορφοποίησης για το DataLabel.
type: docs
weight: 2020
url: /el/aspose.slides.charts/idatalabelformat/
---
## IDataLabelFormat διασύνδεση

Αναπαριστά τις επιλογές μορφοποίησης για το DataLabel.

```csharp
public interface IDataLabelFormat : IFormattedTextContainer
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/idatalabelformat/asiformattedtextcontainer) { get; } | Επιτρέπει τη λήψη της βασικής IFormattedTextContainer διασύνδεσης. Μόνο για ανάγνωση [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [Format](../../aspose.slides.charts/idatalabelformat/format) { get; } | Αναπαριστά τη μορφή της ετικέτας δεδομένων. Μόνο για ανάγνωση [`IFormat`](../iformat). |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/idatalabelformat/isnumberformatlinkedtosource) { get; set; } | Ανάγνωση/Εγγραφή Boolean. |
| [NumberFormat](../../aspose.slides.charts/idatalabelformat/numberformat) { get; set; } | Αναπαριστά το αλφαριθμητικό μορφής για το αντικείμενο DataLabels. Ανάγνωση/Εγγραφή String. |
| [Position](../../aspose.slides.charts/idatalabelformat/position) { get; set; } | Αναπαριστά τη θέση της ετικέτας δεδομένων. Ανάγνωση/Εγγραφή [`LegendDataLabelPosition`](../legenddatalabelposition). |
| [Separator](../../aspose.slides.charts/idatalabelformat/separator) { get; set; } | Ορίζει ή επιστρέφει ένα Variant που αναπαριστά το διαχωριστικό που χρησιμοποιείται για τις ετικέτες δεδομένων σε ένα γράφημα. Ανάγνωση/Εγγραφή String. |
| [ShowBubbleSize](../../aspose.slides.charts/idatalabelformat/showbubblesize) { get; set; } | Αναπαριστά τη συμπεριφορά εμφάνισης της τιμής μεγέθους φυσαλίδας της ετικέτας δεδομένων ενός συγκεκριμένου γραφήματος. True εμφανίζει την τιμή μεγέθους φυσαλίδας. False για απόκρυψη. Ανάγνωση/Εγγραφή Boolean. |
| [ShowCategoryName](../../aspose.slides.charts/idatalabelformat/showcategoryname) { get; set; } | Αναπαριστά τη συμπεριφορά εμφάνισης του ονόματος κατηγορίας της ετικέτας δεδομένων ενός συγκεκριμένου γραφήματος. True για εμφάνιση του ονόματος κατηγορίας. False για απόκρυψη. Ανάγνωση/Εγγραφή Boolean. |
| [ShowLabelAsDataCallout](../../aspose.slides.charts/idatalabelformat/showlabelasdatacallout) { get; set; } | Καθορίζει εάν η ετικέτα δεδομένων ενός συγκεκριμένου γραφήματος θα εμφανίζεται ως υπερσχετικό δεδομένων ή ως ετικέτα δεδομένων. Εάν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα παίρνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowLabelAsDataCallout για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ο ορισμός αυτής της ιδιότητας με τιμή ορίζει επίσης αυτή την τιμή στην ιδιότητα ShowLabelAsDataCallout για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" προκαλεί όλες οι DataLabels[i].ShowLabelAsDataCallout να είναι ίσες με val). |
| [ShowLabelValueFromCell](../../aspose.slides.charts/idatalabelformat/showlabelvaluefromcell) { get; set; } | Αναπαριστά τη συμπεριφορά εμφάνισης της τιμής κελιού της ετικέτας δεδομένων ενός συγκεκριμένου γραφήματος. True εμφανίζει την τιμή του κελιού. False για απόκρυψη. Ανάγνωση/Εγγραφή Boolean. |
| [ShowLeaderLines](../../aspose.slides.charts/idatalabelformat/showleaderlines) { get; set; } | Αναπαριστά τη συμπεριφορά εμφάνισης των γραμμών οδηγού της ετικέτας δεδομένων ενός συγκεκριμένου γραφήματος. True εμφανίζει τις γραμμές οδηγού. False για απόκρυψη. Ανάγνωση/Εγγραφή Boolean. |
| [ShowLegendKey](../../aspose.slides.charts/idatalabelformat/showlegendkey) { get; set; } | Αναπαριστά τη συμπεριφορά εμφάνισης του κλειδιού υπομνήματος της ετικέτας δεδομένων ενός συγκεκριμένου γραφήματος. True εάν το κλειδί υπομνήματος της ετικέτας δεδομένων είναι ορατό. Ανάγνωση/Εγγραφή Boolean. |
| [ShowPercentage](../../aspose.slides.charts/idatalabelformat/showpercentage) { get; set; } | Αναπαριστά τη συμπεριφορά εμφάνισης της τιμής ποσοστού της ετικέτας δεδομένων ενός συγκεκριμένου γραφήματος. True εμφανίζει την τιμή ποσοστού. False για απόκρυψη. Ανάγνωση/Εγγραφή Boolean. |
| [ShowSeriesName](../../aspose.slides.charts/idatalabelformat/showseriesname) { get; set; } | Επιστρέφει ή ορίζει ένα Boolean που υποδεικνύει τη συμπεριφορά εμφάνισης του ονόματος σειράς για τις ετικέτες δεδομένων σε ένα γράφημα. True για εμφάνιση του ονόματος σειράς. False για απόκρυψη. Ανάγνωση/Εγγραφή Boolean. |
| [ShowValue](../../aspose.slides.charts/idatalabelformat/showvalue) { get; set; } | Αναπαριστά τη συμπεριφορά εμφάνισης της τιμής ποσοστού της ετικέτας δεδομένων ενός συγκεκριμένου γραφήματος. True εμφανίζει την τιμή ποσοστού. False για απόκρυψη. Ανάγνωση/Εγγραφή Boolean. |

### Δείτε επίσης

* διασύνδεση [IFormattedTextContainer](../iformattedtextcontainer)
* χώρο ονομάτων [Aspose.Slides.Charts](../../aspose.slides.charts)
* συναρμολόγηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->