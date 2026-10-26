---
title: ChartCategory
second_title: Aspose.Sildes για PHP μέσω Java API Αναφορά
description: 
type: docs

url: /el/aspose.slides/chartcategory/
---
## ChartCategory κλάση

 Αντιπροσωπεύει τις κατηγορίες γραφημάτων.
 
### getAsCell {#getAsCell}

| Όνομα | Περιγραφή |
| --- | --- |
| getAsCell () | Επιστρέφει ή ορίζει αντικείμενο IChartDataCell. Εάν η κατηγορία είναι πολυεπίπεδη, τότε χρησιμοποιείται το αντικείμενο IChartDataCell για το επίπεδο "0". Ανάγνωση/εγγραφή IChartDataCell. |

 **Επιστρέφει:**
[ChartDataCell](../chartdatacell)

---


### getAsLiteral {#getAsLiteral}

| Όνομα | Περιγραφή |
| --- | --- |
| getAsLiteral () | Επιστρέφει ή ορίζει αντικείμενο AsLiteral. Ανάγνωση/εγγραφή Object. |

 **Επιστρέφει:**
Object


---


### getGroupingLevels {#getGroupingLevels}

| Όνομα | Περιγραφή |
| --- | --- |
| getGroupingLevels () | Διαχειριζόμενο κοντέινερ των τιμών των επιπέδων ομαδοποίησης της κατηγορίας γραφήματος. Η πολυεπίπεδη κατηγορία περιέχει περισσότερα από ένα επίπεδο ομαδοποίησης. Η αρίθμηση των επιπέδων ομαδοποίησης ξεκινά από το μηδέν. Μόνο ανάγνωση IChartCategoryLevelsManager. |

 **Επιστρέφει:**
[ChartCategoryLevelsManager](../chartcategorylevelsmanager)

---


### getUseCell {#getUseCell}

| Όνομα | Περιγραφή |
| --- | --- |
| getUseCell () | Εάν είναι true τότε η ιδιότητα AsCell είναι ενεργή. Με άλλα λόγια, το φύλλο εργασίας χρησιμοποιείται για αποθήκευση της κατηγορίας (αυτή η περίπτωση υποστηρίζει πολυεπίπεδη κατηγορία). Εάν είναι false τότε η ιδιότητα AsLiteral είναι ενεργή. Με άλλα λόγια, το φύλλο εργασίας ΔΕΝ χρησιμοποιείται για αποθήκευση της κατηγορίας (και αυτή η περίπτωση δεν υποστηρίζει πολυεπίπεδες κατηγορίες). Μόνο ανάγνωση boolean. Για να αλλάξετε την τιμή αυτής της ιδιότητας (για όλες τις κατηγορίες στη συλλογή) ορίστε τη νέα τιμή στην ιδιότητα ChartCategoryCollection.UseCells. |

 **Επιστρέφει:**
boolean


---


### getValue {#getValue}

| Όνομα | Περιγραφή |
| --- | --- |
| getValue () | Εάν το UseCell είναι true τότε αυτή η ιδιότητα αντιπροσωπεύει την ιδιότητα AsCell.Value. Εάν το UseCell είναι false τότε αυτή η ιδιότητα αντιπροσωπεύει την ιδιότητα AsLiteral. Ανάγνωση/εγγραφή Object. |

 **Επιστρέφει:**
Object


---


### remove {#remove}

| Όνομα | Περιγραφή |
| --- | --- |
| remove () | Αφαιρεί την κατηγορία από το γράφημα. |

 **Επιστρέφει:**
void

 **Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| PptxEditException | Εκνέμεται εάν η κατηγορία έχει ήδη αφαιρεθεί από το γράφημα. |


---


### setAsCell {#setAsCell}

| Όνομα | Περιγραφή |
| --- | --- |
| setAsCell ([ChartDataCell](../chartdatacell)) | Επιστρέφει ή ορίζει αντικείμενο IChartDataCell. Εάν η κατηγορία είναι πολυεπίπεδη, τότε χρησιμοποιείται το αντικείμενο IChartDataCell για το επίπεδο "0". Ανάγνωση/εγγραφή IChartDataCell. |

 **Επιστρέφει:**
void


---


### setAsLiteral {#setAsLiteral}

| Όνομα | Περιγραφή |
| --- | --- |
| setAsLiteral (Object) | Επιστρέφει ή ορίζει αντικείμενο AsLiteral. Ανάγνωση/εγγραφή Object. |

 **Επιστρέφει:**
void


---


### setValue {#setValue}

| Όνομα | Περιγραφή |
| --- | --- |
| setValue (Object) | Εάν το UseCell είναι true τότε αυτή η ιδιότητα αντιπροσωπεύει την ιδιότητα AsCell.Value. Εάν το UseCell είναι false τότε αυτή η ιδιότητα αντιπροσωπεύει την ιδιότητα AsLiteral. Ανάγνωση/εγγραφή Object. |

 **Επιστρέφει:**
void


---