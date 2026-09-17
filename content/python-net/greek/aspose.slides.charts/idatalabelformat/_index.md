---
title: IDataLabelFormat class
second_title: Aspose.Slides για Python μέσω .NET Αναφορά API
description: 
type: docs
url: /el/aspose.slides.charts/idatalabelformat/
---
## IDataLabelFormat κλάση

Αναπαριστά τις επιλογές μορφοποίησης για DataLabel.

Ο τύπος IDataLabelFormat εκθέτει τα ακόλουθα μέλη:

## Ιδιότητες

| Property | Description |
| :- | :- |
| [`is_number_format_linked_to_source`](/slides/python-net/el/aspose.slides.charts/idatalabelformat/is_number_format_linked_to_source/) | Ανάγνωση/Εγγραφή **bool**. |
| [`number_format`](/slides/python-net/el/aspose.slides.charts/idatalabelformat/number_format/) | Αναπαριστά το string μορφής για το αντικείμενο DataLabels.<br/>            Ανάγνωση/Εγγραφή **str**. |
| [`format`](/slides/python-net/el/aspose.slides.charts/idatalabelformat/format/) | Αναπαριστά τη μορφή της ετικέτας δεδομένων.<br/>            Μόνο ανάγνωση [`IFormat`](/slides/python-net/el/aspose.slides.charts/iformat). |
| [`position`](/slides/python-net/el/aspose.slides.charts/idatalabelformat/position/) | Αναπαριστά τη θέση της ετικέτας δεδομένων.<br/>            Ανάγνωση/Εγγραφή [`LegendDataLabelPosition`](/slides/python-net/el/aspose.slides.charts/legenddatalabelposition). |
| [`show_legend_key`](/slides/python-net/el/aspose.slides.charts/idatalabelformat/show_legend_key/) | Αναπαριστά τη συμπεριφορά εμφάνισης του κλειδιού υπομνήματος ετικέτας δεδομένων ενός συγκεκριμένου διαγράμματος. <br/>            True εάν το κλειδί υπομνήματος ετικέτας δεδομένων είναι ορατό.<br/>            Ανάγνωση/Εγγραφή **bool**. |
| [`show_value`](/slides/python-net/el/aspose.slides.charts/idatalabelformat/show_value/) | Αναπαριστά τη συμπεριφορά εμφάνισης της τιμής ποσοστού ετικέτας δεδομένων ενός συγκεκριμένου διαγράμματος. <br/>            True εμφανίζει την τιμή ποσοστού. False για απόκρυψη.<br/>            Ανάγνωση/Εγγραφή **bool**. |
| [`show_category_name`](/slides/python-net/el/aspose.slides.charts/idatalabelformat/show_category_name/) | Αναπαριστά τη συμπεριφορά εμφάνισης του ονόματος κατηγορίας ετικέτας δεδομένων ενός συγκεκριμένου διαγράμματος.<br/>            True για εμφάνιση του ονόματος κατηγορίας για τις ετικέτες δεδομένων σε ένα διάγραμμα. False για απόκρυψη.<br/>            Ανάγνωση/Εγγραφή **bool**. |
| [`show_series_name`](/slides/python-net/el/aspose.slides.charts/idatalabelformat/show_series_name/) | Επιστρέφει ή θέτει ένα Boolean για να υποδείξει τη συμπεριφορά εμφάνισης του ονόματος σειράς για τις ετικέτες δεδομένων σε ένα διάγραμμα. <br/>            True για εμφάνιση του ονόματος σειράς. False για απόκρυψη.<br/>            Ανάγνωση/Εγγραφή **bool**. |
| [`show_percentage`](/slides/python-net/el/aspose.slides.charts/idatalabelformat/show_percentage/) | Αναπαριστά τη συμπεριφορά εμφάνισης της τιμής ποσοστού ετικέτας δεδομένων ενός συγκεκριμένου διαγράμματος. <br/>            True εμφανίζει την τιμή ποσοστού. False για απόκρυψη.<br/>            Ανάγνωση/Εγγραφή **bool**. |
| [`show_bubble_size`](/slides/python-net/el/aspose.slides.charts/idatalabelformat/show_bubble_size/) | Αναπαριστά τη συμπεριφορά εμφάνισης της τιμής μεγέθους φυσαλίδας ετικέτας δεδομένων ενός συγκεκριμένου διαγράμματος. <br/>            True εμφανίζει την τιμή μεγέθους φυσαλίδας. False για απόκρυψη.<br/>            Ανάγνωση/Εγγραφή **bool**. |
| [`show_leader_lines`](/slides/python-net/el/aspose.slides.charts/idatalabelformat/show_leader_lines/) | Αναπαριστά τη συμπεριφορά εμφάνισης των γραμμών οδηγού ετικέτας δεδομένων ενός συγκεκριμένου διαγράμματος. <br/>            True εμφανίζει τις γραμμές οδηγού. False για απόκρυψη.<br/>            Ανάγνωση/Εγγραφή **bool**. |
| [`show_label_as_data_callout`](/slides/python-net/el/aspose.slides.charts/idatalabelformat/show_label_as_data_callout/) | Καθορίζει εάν η ετικέτα δεδομένων ενός συγκεκριμένου διαγράμματος θα εμφανίζεται ως κλήση δεδομένων ή ως ετικέτα δεδομένων.<br/>            <br/>            Εάν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή<br/>            η ιδιότητα παίρνει ή θέτει την προεπιλεγμένη τιμή της ιδιότητας ShowLabelAsDataCallout για τις νέες ετικέτες δεδομένων <br/>            στη συλλογή DataLabelCollection.<br/>            Ορίζοντας αυτή την ιδιότητα με μια τιμή, θέτει επίσης αυτή την τιμή στην ιδιότητα ShowLabelAsDataCallout <br/>            για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection<br/>            (π.χ. "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" προκαλεί ώστε <br/>            όλες οι DataLabels[i].ShowLabelAsDataCallout να είναι ίσες με val). |
| [`show_label_value_from_cell`](/slides/python-net/el/aspose.slides.charts/idatalabelformat/show_label_value_from_cell/) | Αναπαριστά τη συμπεριφορά εμφάνισης της τιμής κελιού ετικέτας δεδομένων ενός συγκεκριμένου διαγράμματος. <br/>            True εμφανίζει την τιμή του κελιού. False για απόκρυψη.<br/>            Ανάγνωση/Εγγραφή **bool**. |
| [`separator`](/slides/python-net/el/aspose.slides.charts/idatalabelformat/separator/) | Ορίζει ή επιστρέφει ένα Variant που αντιπροσωπεύει το διαχωριστικό που χρησιμοποιείται για τις ετικέτες δεδομένων σε ένα διάγραμμα.<br/>            Ανάγνωση/Εγγραφή **str**. |
| [`text_format`](/slides/python-net/el/aspose.slides.charts/idatalabelformat/text_format/) |  |
| [`chart`](/slides/python-net/el/aspose.slides.charts/idatalabelformat/chart/) |  |
| [`slide`](/slides/python-net/el/aspose.slides.charts/idatalabelformat/slide/) |  |
| [`presentation`](/slides/python-net/el/aspose.slides.charts/idatalabelformat/presentation/) |  |

### Δείτε επίσης
* μονάδα [`aspose.slides.charts`](/slides/python-net/el/aspose.slides.charts)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)