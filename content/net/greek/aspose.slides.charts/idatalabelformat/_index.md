---
title: IDataLabelFormat
second_title: Aspose.Sildes για .NET Αναφορά API
description: Αναπαριστά επιλογές μορφοποίησης για το DataLabel.
type: docs
weight: 2040
url: /el/aspose.slides.charts/idatalabelformat/
---
## IDataLabelFormat διεπαφή

Αναπαριστά επιλογές μορφοποίησης για το DataLabel.

```csharp
public interface IDataLabelFormat : IFormattedTextContainer
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/idatalabelformat/asiformattedtextcontainer) { get; } | Επιτρέπει την πρόσβαση στη βασική διεπαφή IFormattedTextContainer. Μόνο για ανάγνωση [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [Format](../../aspose.slides.charts/idatalabelformat/format) { get; } | Αντιπροσωπεύει τη μορφή της ετικέτας δεδομένων. Μόνο για ανάγνωση [`IFormat`](../iformat). |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/idatalabelformat/isnumberformatlinkedtosource) { get; set; } | Ανάγνωση/εγγραφή Boolean. |
| [NumberFormat](../../aspose.slides.charts/idatalabelformat/numberformat) { get; set; } | Αντιπροσωπεύει τη συμβολοσειρά μορφής για το αντικείμενο DataLabels. Ανάγνωση/εγγραφή String. |
| [Position](../../aspose.slides.charts/idatalabelformat/position) { get; set; } | Αντιπροσωπεύει τη θέση της ετικέτας δεδομένων. Ανάγνωση/εγγραφή [`LegendDataLabelPosition`](../legenddatalabelposition). |
| [Separator](../../aspose.slides.charts/idatalabelformat/separator) { get; set; } | Ορίζει ή επιστρέφει μια Variant που αντιπροσωπεύει το διαχωριστικό που χρησιμοποιείται για τις ετικέτες δεδομένων σε ένα γράφημα. Ανάγνωση/εγγραφή String. |
| [ShowBubbleSize](../../aspose.slides.charts/idatalabelformat/showbubblesize) { get; set; } | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης της τιμής μεγέθους φούστας της ετικέτας δεδομένων ενός συγκεκριμένου διαγράμματος. True εμφανίζει την τιμή μεγέθους φούστας. False για απόκρυψη. Ανάγνωση/εγγραφή Boolean. |
| [ShowCategoryName](../../aspose.slides.charts/idatalabelformat/showcategoryname) { get; set; } | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης του ονόματος κατηγορίας της ετικέτας δεδομένων ενός συγκεκριμένου διαγράμματος. True για εμφάνιση του ονόματος κατηγορίας στις ετικέτες δεδομένων ενός διαγράμματος. False για απόκρυψη. Ανάγνωση/εγγραφή Boolean. |
| [ShowLabelAsDataCallout](../../aspose.slides.charts/idatalabelformat/showlabelasdatacallout) { get; set; } | Καθορίζει εάν η ετικέτα δεδομένων του συγκεκριμένου διαγράμματος θα εμφανίζεται ως κάλεσμα δεδομένων ή ως ετικέτα δεδομένων. Εάν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μία συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα παίρνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowLabelAsDataCallout για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection. Ο ορισμός αυτής της ιδιότητας με τιμή θέτει επίσης αυτήν την τιμή στην ιδιότητα ShowLabelAsDataCallout για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection (π.χ. "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" προκαλεί όλες οι DataLabels[i].ShowLabelAsDataCallout να είναι ίσες με val). |
| [ShowLabelValueFromCell](../../aspose.slides.charts/idatalabelformat/showlabelvaluefromcell) { get; set; } | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης της τιμής κελιού της ετικέτας δεδομένων ενός συγκεκριμένου διαγράμματος. True εμφανίζει την τιμή του κελιού. False για απόκρυψη. Ανάγνωση/εγγραφή Boolean. |
| [ShowLeaderLines](../../aspose.slides.charts/idatalabelformat/showleaderlines) { get; set; } | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης των γραμμών οδηγού της ετικέτας δεδομένων ενός συγκεκριμένου διαγράμματος. True εμφανίζει τις γραμμές οδηγού. False για απόκρυψη. Ανάγνωση/εγγραφή Boolean. |
| [ShowLegendKey](../../aspose.slides.charts/idatalabelformat/showlegendkey) { get; set; } | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης του κλειδιού υπόμνησης της ετικέτας δεδομένων ενός συγκεκριμένου διαγράμματος. True αν το κλειδί υπόμνησης ετικέτας δεδομένων είναι ορατό. Ανάγνωση/εγγραφή Boolean. |
| [ShowPercentage](../../aspose.slides.charts/idatalabelformat/showpercentage) { get; set; } | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης της ποσοστιαίας τιμής της ετικέτας δεδομένων ενός συγκεκριμένου διαγράμματος. True εμφανίζει την ποσοστιαία τιμή. False για απόκρυψη. Ανάγνωση/εγγραφή Boolean. |
| [ShowSeriesName](../../aspose.slides.charts/idatalabelformat/showseriesname) { get; set; } | Επιστρέφει ή ορίζει ένα Boolean για να υποδείξει τη συμπεριφορά εμφάνιση του ονόματος σειράς στις ετικέτες δεδομένων ενός διαγράμματος. True για εμφάνιση του ονόματος σειράς. False για απόκρυψη. Ανάγνωση/εγγραφή Boolean. |
| [ShowValue](../../aspose.slides.charts/idatalabelformat/showvalue) { get; set; } | Αντιπροσωπεύει τη συμπεριφορά εμφάνισης της ποσοστιαίας τιμής της ετικέτας δεδομένων ενός συγκεκριμένου διαγράμματος. True εμφανίζει την ποσοστιαία τιμή. False για απόκρυψη. Ανάγνωση/εγγραφή Boolean. |

### Δείτε επίσης

* διεπαφή [IFormattedTextContainer](../iformattedtextcontainer)
* χώρος ονομάτων [Aspose.Slides.Charts](../../aspose.slides.charts)
* συναρμολόγηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->