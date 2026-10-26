---
title: ICell class
second_title: Aspose.Slides για Python μέσω .NET Αναφορά API
description: 
type: docs
url: /el/aspose.slides/icell/
---
## ICell κλάση

Αντιπροσωπεύει ένα κελί σε έναν πίνακα.

Ο τύπος ICell εκθέτει τα ακόλουθα μέλη:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`offset_x`](/slides/python-net/el/aspose.slides/icell/offset_x/) | Επιστρέφει μια απόσταση από την αριστερή πλευρά ενός πίνακα έως την αριστερή πλευρά ενός κελιού.<br/>            Μόνο ανάγνωση **float**. |
| [`offset_y`](/slides/python-net/el/aspose.slides/icell/offset_y/) | Επιστρέφει μια απόσταση από την επάνω πλευρά ενός πίνακα έως την επάνω πλευρά ενός κελιού.<br/>            Μόνο ανάγνωση **float**. |
| [`first_row_index`](/slides/python-net/el/aspose.slides/icell/first_row_index/) | Επιστρέφει το ευρετήριο της πρώτης γραμμής που καλύπτεται από το κελί.<br/>            Μόνο ανάγνωση **int**. |
| [`first_column_index`](/slides/python-net/el/aspose.slides/icell/first_column_index/) | Επιστρέφει το ευρετήριο της πρώτης στήλης που καλύπτεται από το κελί.<br/>            Μόνο ανάγνωση **int**. |
| [`width`](/slides/python-net/el/aspose.slides/icell/width/) | Επιστρέφει το πλάτος του κελιού.<br/>            Μόνο ανάγνωση **float**. |
| [`height`](/slides/python-net/el/aspose.slides/icell/height/) | Επιστρέφει το ύψος του κελιού.<br/>            Μόνο ανάγνωση **float**. |
| [`minimal_height`](/slides/python-net/el/aspose.slides/icell/minimal_height/) | Επιστρέφει το ελάχιστο ύψος ενός κελιού.<br/>            Αυτό είναι το άθροισμα των ελάχιστων ύψους όλων των γραμμών που καλύπτονται από το κελί.<br/>            Μόνο ανάγνωση **float**. |
| [`margin_left`](/slides/python-net/el/aspose.slides/icell/margin_left/) | Επιστρέφει ή ορίζει το αριστερό περιθώριο σε ένα TextFrame.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`margin_right`](/slides/python-net/el/aspose.slides/icell/margin_right/) | Επιστρέφει ή ορίζει το δεξί περιθώριο σε ένα TextFrame.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`margin_top`](/slides/python-net/el/aspose.slides/icell/margin_top/) | Επιστρέφει ή ορίζει το επάνω περιθώριο σε ένα TextFrame.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`margin_bottom`](/slides/python-net/el/aspose.slides/icell/margin_bottom/) | Επιστρέφει ή ορίζει το κάτω περιθώριο σε ένα TextFrame.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`text_vertical_type`](/slides/python-net/el/aspose.slides/icell/text_vertical_type/) | Επιστρέφει ή ορίζει τον τύπο του κατακόρυφου κειμένου.<br/>            Ανάγνωση/εγγραφή [`TextVerticalType`](/slides/python-net/el/aspose.slides/textverticaltype). |
| [`text_anchor_type`](/slides/python-net/el/aspose.slides/icell/text_anchor_type/) | Επιστρέφει ή ορίζει τον τύπο άγκυρας κειμένου.<br/>            Ανάγνωση/εγγραφή [`TextAnchorType`](/slides/python-net/el/aspose.slides/textanchortype). |
| [`anchor_center`](/slides/python-net/el/aspose.slides/icell/anchor_center/) | Καθορίζει αν το πλαίσιο κειμένου είναι κεντραρισμένο μέσα σε ένα κελί ή όχι.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`first_column`](/slides/python-net/el/aspose.slides/icell/first_column/) | Παίρνει την πρώτη στήλη του κελιού.<br/>            Μόνο ανάγνωση [`IColumn`](/slides/python-net/el/aspose.slides/icolumn). |
| [`first_row`](/slides/python-net/el/aspose.slides/icell/first_row/) | Παίρνει την πρώτη γραμμή του κελιού.<br/>            Μόνο ανάγνωση [`IRow`](/slides/python-net/el/aspose.slides/irow). |
| [`col_span`](/slides/python-net/el/aspose.slides/icell/col_span/) | Επιστρέφει τον αριθμό των στηλών πλέγματος στο γονικό Table grid που θα εκταθεί από το τρέχον κελί.<br/>            Αυτή η ιδιότητα επιτρέπει στα κελιά να έχουν την εμφάνιση του ότι έχουν συγχωνευτεί, καθώς εκτείνουν κάθετες περιορισμούς άλλων κελιών στον πίνακα.<br/>            Μόνο ανάγνωση **int**. |
| [`row_span`](/slides/python-net/el/aspose.slides/icell/row_span/) | Επιστρέφει τον αριθμό των γραμμών που εκτείνεται ένα συγχωνευμένο κελί. Αυτό χρησιμοποιείται σε συνδυασμό<br/>            με το χαρακτηριστικό vMerge σε άλλα κελιά για να καθορίσει το αρχικό κελί<br/>            μιας οριζοντιακής συγχώνευσης.<br/>            Μόνο ανάγνωση **int**. |
| [`text_frame`](/slides/python-net/el/aspose.slides/icell/text_frame/) | Επιστρέφει το πλαίσιο κειμένου ενός κελιού.<br/>            Μόνο ανάγνωση [`ITextFrame`](/slides/python-net/el/aspose.slides/itextframe). |
| [`table`](/slides/python-net/el/aspose.slides/icell/table/) | Επιστρέφει το γονικό αντικείμενο Table για ένα κελί.<br/>            Μόνο ανάγνωση [`ITable`](/slides/python-net/el/aspose.slides/itable). |
| [`is_merged_cell`](/slides/python-net/el/aspose.slides/icell/is_merged_cell/) | Επιστρέφει true αν το κελί είναι συγχωνευμένο με οποιοδήποτε προσαρμοσμένο κελί, false διαφορετικά.<br/>            Μόνο ανάγνωση **bool**. |
| [`cell_format`](/slides/python-net/el/aspose.slides/icell/cell_format/) | Επιστρέφει το αντικείμενο CellFormat που περιέχει ιδιότητες μορφοποίησης για αυτό το κελί.<br/>            Μόνο ανάγνωση [`ICellFormat`](/slides/python-net/el/aspose.slides/icellformat). |
| [`slide`](/slides/python-net/el/aspose.slides/icell/slide/) |  |
| [`presentation`](/slides/python-net/el/aspose.slides/icell/presentation/) |  |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`split_by_col_span(self, index)`](/slides/python-net/el/aspose.slides/icell/split_by_col_span/#int) | Διαιρεί το κελί σε δύο κελιά κατά τον δείκτη στήλης. |
| [`split_by_row_span(self, index)`](/slides/python-net/el/aspose.slides/icell/split_by_row_span/#int) | Διαιρεί το κελί σε δύο κελιά κατά τον δείκτη γραμμής. |
| [`split_by_height(self, height)`](/slides/python-net/el/aspose.slides/icell/split_by_height/#float) | Διαιρεί το κελί κατά ύψος. |
| [`split_by_width(self, width)`](/slides/python-net/el/aspose.slides/icell/split_by_width/#float) | Διαιρεί το κελί κατά πλάτος. |

### Δείτε επίσης
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)