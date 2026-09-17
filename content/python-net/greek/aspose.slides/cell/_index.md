---
title: Cell class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/cell/
---
## Cell κλάση

Αναπαριστά ένα κελί ενός πίνακα.

Ο τύπος Cell εκθέτει τα ακόλουθα μέλη:

## Ιδιότητες

| Property | Description |
| :- | :- |
| [`offset_x`](/slides/python-net/el/aspose.slides/cell/offset_x/) | Επιστρέφει μια απόσταση από την αριστερή πλευρά ενός πίνακα έως την αριστερή πλευρά ενός κελιού.<br/>            Μόνο προς ανάγνωση **float**. |
| [`offset_y`](/slides/python-net/el/aspose.slides/cell/offset_y/) | Επιστρέφει μια απόσταση από την πάνω πλευρά ενός πίνακα έως την πάνω πλευρά ενός κελιού.<br/>            Μόνο προς ανάγνωση **float**. |
| [`first_row_index`](/slides/python-net/el/aspose.slides/cell/first_row_index/) | Επιστρέφει έναν δείκτη της πρώτης γραμμής που καλύπτεται από το κελί.<br/>            Μόνο προς ανάγνωση **int**. |
| [`first_column_index`](/slides/python-net/el/aspose.slides/cell/first_column_index/) | Επιστρέφει έναν δείκτη της πρώτης στήλης που καλύπτεται από το κελί.<br/>            Μόνο προς ανάγνωση **int**. |
| [`width`](/slides/python-net/el/aspose.slides/cell/width/) | Επιστρέφει το πλάτος του κελιού.<br/>            Μόνο προς ανάγνωση **float**. |
| [`height`](/slides/python-net/el/aspose.slides/cell/height/) | Επιστρέφει το ύψος του κελιού.<br/>            Μόνο προς ανάγνωση **float**. |
| [`minimal_height`](/slides/python-net/el/aspose.slides/cell/minimal_height/) | Επιστρέφει το ελάχιστο ύψος ενός κελιού.<br/>            Αυτό είναι το άθροισμα των ελάχιστων υψών όλων των γραμμών που καλύπτονται από το κελί.<br/>            Μόνο προς ανάγνωση **float**. |
| [`margin_left`](/slides/python-net/el/aspose.slides/cell/margin_left/) | Επιστρέφει ή ορίζει το αριστερό περιθώριο σε ένα TextFrame.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`margin_right`](/slides/python-net/el/aspose.slides/cell/margin_right/) | Επιστρέφει ή ορίζει το δεξιό περιθώριο σε ένα TextFrame.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`margin_top`](/slides/python-net/el/aspose.slides/cell/margin_top/) | Επιστρέφει ή ορίζει το πάνω περιθώριο σε ένα TextFrame.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`margin_bottom`](/slides/python-net/el/aspose.slides/cell/margin_bottom/) | Επιστρέφει ή ορίζει το κάτω περιθώριο σε ένα TextFrame.<br/>            Ανάγνωση/εγγραφή **float**. |
| [`text_vertical_type`](/slides/python-net/el/aspose.slides/cell/text_vertical_type/) | Επιστρέφει ή ορίζει τον τύπο κατακόρυφου κειμένου.<br/>            Ανάγνωση/εγγραφή [`TextVerticalType`](/slides/python-net/el/aspose.slides/textverticaltype). |
| [`text_anchor_type`](/slides/python-net/el/aspose.slides/cell/text_anchor_type/) | Επιστρέφει ή ορίζει τον τύπο αγκίστρωσης κειμένου.<br/>            Ανάγνωση/εγγραφή [`TextAnchorType`](/slides/python-net/el/aspose.slides/textanchortype). |
| [`anchor_center`](/slides/python-net/el/aspose.slides/cell/anchor_center/) | Καθορίζει αν το κουτί κειμένου είναι κεντραρισμένο μέσα σε ένα κελί.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`first_row`](/slides/python-net/el/aspose.slides/cell/first_row/) | Λαμβάνει την πρώτη γραμμή του κελιού.<br/>            Μόνο προς ανάγνωση [`IRow`](/slides/python-net/el/aspose.slides/irow). |
| [`first_column`](/slides/python-net/el/aspose.slides/cell/first_column/) | Λαμβάνει την πρώτη στήλη του κελιού.<br/>            Μόνο προς ανάγνωση [`IColumn`](/slides/python-net/el/aspose.slides/icolumn). |
| [`col_span`](/slides/python-net/el/aspose.slides/cell/col_span/) | Επιστρέφει τον αριθμό των στηλών του πλέγματος στον γονικό πίνακα που πρέπει να καλυφθούν από το τρέχον κελί. Αυτή η ιδιότητα επιτρέπει στα κελιά να έχουν την εμφάνιση συγχώνευσης, καθώς εκτείνονται κατά τις κάθετες όριες άλλων κελιών στον πίνακα.<br/>            Μόνο προς ανάγνωση **int**. |
| [`row_span`](/slides/python-net/el/aspose.slides/cell/row_span/) | Επιστρέφει τον αριθμό των γραμμών που εκτείνεται ένα συγχωνευμένο κελί. Αυτό χρησιμοποιείται σε συνδυασμό<br/>            με το χαρακτηριστικό vMerge σε άλλα κελιά για να καθορίσει το κελί έναρξης μιας οριζόντιας συγχώνευσης.<br/>            Μόνο προς ανάγνωση **int**. |
| [`text_frame`](/slides/python-net/el/aspose.slides/cell/text_frame/) | Επιστρέφει το πλαίσιο κειμένου ενός κελιού.<br/>            Μόνο προς ανάγνωση [`ITextFrame`](/slides/python-net/el/aspose.slides/itextframe). |
| [`table`](/slides/python-net/el/aspose.slides/cell/table/) | Επιστρέφει το γονικό αντικείμενο Table για ένα κελί.<br/>            Μόνο προς ανάγνωση [`ITable`](/slides/python-net/el/aspose.slides/itable). |
| [`is_merged_cell`](/slides/python-net/el/aspose.slides/cell/is_merged_cell/) | Επιστρέφει true εάν το κελί είναι συγχωνευμένο με οποιοδήποτε προσαρμοσμένο κελί, false διαφορετικά.<br/>            Μόνο προς ανάγνωση **bool**. |
| [`cell_format`](/slides/python-net/el/aspose.slides/cell/cell_format/) | Επιστρέφει το αντικείμενο CellFormat που περιέχει ιδιότητες μορφοποίησης για αυτό το κελί.<br/>            Μόνο προς ανάγνωση [`ICellFormat`](/slides/python-net/el/aspose.slides/icellformat). |
| [`slide`](/slides/python-net/el/aspose.slides/cell/slide/) | Επιστρέφει τη γονική διαφάνεια ενός κελιού.<br/>            Μόνο προς ανάγνωση [`IBaseSlide`](/slides/python-net/el/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/el/aspose.slides/cell/presentation/) | Επιστρέφει την γονική παρουσίαση ενός κελιού.<br/>            Μόνο προς ανάγνωση [`IPresentation`](/slides/python-net/el/aspose.slides/ipresentation). |

## Μέθοδοι

| Method | Description |
| :- | :- |
| [`split_by_col_span(self, index)`](/slides/python-net/el/aspose.slides/cell/split_by_col_span/#int) | Διαχωρίζει το κελί σε δύο κελιά με βάση τον δείκτη της στήλης. |
| [`split_by_row_span(self, index)`](/slides/python-net/el/aspose.slides/cell/split_by_row_span/#int) | Διαχωρίζει το κελί σε δύο κελιά με βάση τον δείκτη της γραμμής. |
| [`split_by_height(self, height)`](/slides/python-net/el/aspose.slides/cell/split_by_height/#float) | Διαχωρίζει το κελί κατά ύψος. |
| [`split_by_width(self, width)`](/slides/python-net/el/aspose.slides/cell/split_by_width/#float) | Διαχωρίζει το κελί κατά πλάτος. |

### Δείτε επίσης
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)