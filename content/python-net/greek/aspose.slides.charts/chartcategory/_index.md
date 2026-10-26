---
title: ChartCategory class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.charts/chartcategory/
---
## ChartCategory κλάση

Αναπαριστά τις κατηγορίες διαγράμματος.

Ο τύπος ChartCategory εκθέτει τα παρακάτω μέλη:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`use_cell`](/slides/python-net/el/aspose.slides.charts/chartcategory/use_cell/) | Εάν είναι true, τότε η ιδιότητα AsCell είναι ενεργή. Σε άλλες λέξεις, το worksheet χρησιμοποιείται για <br/> αποθήκευση της κατηγορίας (αυτή η περίπτωση υποστηρίζει μια πολυεπίπεδη κατηγορία).<br/> Εάν είναι false, τότε η ιδιότητα AsLiteral είναι ενεργή. Σε άλλες λέξεις, το worksheet **ΔΕΝ** χρησιμοποιείται <br/> για αποθήκευση της κατηγορίας (και αυτή η περίπτωση δεν υποστηρίζει πολυεπίπεδες κατηγορίες).<br/> Μόνο-ανάγνωση **bool**. |
| [`as_cell`](/slides/python-net/el/aspose.slides.charts/chartcategory/as_cell/) | Επιστρέφει ή ορίζει το αντικείμενο IChartDataCell.<br/>            Εάν η κατηγορία είναι πολυεπίπεδη, τότε χρησιμοποιείται το αντικείμενο IChartDataCell για το επίπεδο "0".<br/>            Ανάγνωση/εγγραφή [`IChartDataCell`](/slides/python-net/el/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/el/aspose.slides.charts/chartcategory/as_literal/) | Επιστρέφει ή ορίζει το αντικείμενο AsLiteral.<br/>            Ανάγνωση/εγγραφή **any**. |
| [`value`](/slides/python-net/el/aspose.slides.charts/chartcategory/value/) | Εάν το UseCell είναι true, τότε αυτή η ιδιότητα αντιπροσωπεύει την ιδιότητα AsCell.Value.<br/>            Εάν το UseCell είναι false, τότε αυτή η ιδιότητα αντιπροσωπεύει την ιδιότητα AsLiteral.<br/>            Ανάγνωση/εγγραφή **any**. |
| [`grouping_levels`](/slides/python-net/el/aspose.slides.charts/chartcategory/grouping_levels/) | Διαχειριζόμενο container των τιμών των επιπέδων ομαδοποίησης της κατηγορίας διαγράμματος.<br/>            Η πολυεπίπεδη κατηγορία περιέχει περισσότερα από ένα επίπεδο ομαδοποίησης.<br/>            Η αρίθμηση των επιπέδων ομαδοποίησης είναι μηδενική.<br/>            Μόνο-ανάγνωση [`IChartCategoryLevelsManager`](/slides/python-net/el/aspose.slides.charts/ichartcategorylevelsmanager). |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`remove(self)`](/slides/python-net/el/aspose.slides.charts/chartcategory/remove/#) | Αφαιρεί την κατηγορία από το διάγραμμα. |

### Δείτε επίσης
* μονάδα [`aspose.slides.charts`](/slides/python-net/el/aspose.slides.charts)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)