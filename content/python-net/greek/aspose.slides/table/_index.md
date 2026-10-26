---
title: Table class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/table/
---
## Table κλάση

Αναπαριστά έναν πίνακα σε μια διαφάνεια.

**Κληρονομικότητα:**[`Table`](/slides/python-net/el/aspose.slides/table) → [`GraphicalObject`](/slides/python-net/el/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/el/aspose.slides/shape)

Ο τύπος Table εκθέτει τα εξής μέλη:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`is_text_holder`](/slides/python-net/el/aspose.slides/table/is_text_holder/) | Καθορίζει αν το σχήμα είναι TextHolder_PPT.<br/>            Μόνο ανάγνωση **bool**. |
| [`placeholder`](/slides/python-net/el/aspose.slides/table/placeholder/) | Επιστρέφει το σύμβολο θέση για ένα σχήμα. Επιστρέφει None αν το σχήμα δεν έχει σύμβολο θέση.<br/>            Μόνο ανάγνωση [`IPlaceholder`](/slides/python-net/el/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/el/aspose.slides/table/custom_data/) | Επιστρέφει τα προσαρμοσμένα δεδομένα του σχήματος.<br/>            Μόνο ανάγνωση [`ICustomData`](/slides/python-net/el/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/el/aspose.slides/table/raw_frame/) | Επιστρέφει ή ορίζει τις ακατέργαστες ιδιότητες του πλαισίου του σχήματος.<br/>            Ανάγνωση/Εγγραφή [`IShapeFrame`](/slides/python-net/el/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/el/aspose.slides/table/frame/) | Επιστρέφει ή ορίζει τις ιδιότητες του πλαισίου του σχήματος.<br/>            Ανάγνωση/Εγγραφή [`IShapeFrame`](/slides/python-net/el/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/el/aspose.slides/table/line_format/) | Επιστρέφει το αντικείμενο LineFormat που περιέχει τις ιδιότητες διαμόρφωσης γραμμής για ένα σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γραμμής.<br/>            Μόνο ανάγνωση [`ILineFormat`](/slides/python-net/el/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/el/aspose.slides/table/three_d_format/) | Επιστρέφει το αντικείμενο ThreeDFormat που περιέχει τις ιδιότητες 3d εφέ για ένα σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες 3d.<br/>            Μόνο ανάγνωση [`IThreeDFormat`](/slides/python-net/el/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/el/aspose.slides/table/effect_format/) | Επιστρέφει το αντικείμενο EffectFormat που περιέχει εφέ εικονοστοιχείων που εφαρμόζονται σε ένα σχήμα.<br/>            Σημείωση: μπορεί να επιστρέψει None για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες εφέ.<br/>            Μόνο ανάγνωση [`IEffectFormat`](/slides/python-net/el/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/el/aspose.slides/table/fill_format/) | Επιστρέφει ένα αντικείμενο TableFormat.FillFormat που περιέχει τη διαμόρφωση γεμίσματος για τον Πίνακα.<br/>            Μόνο ανάγνωση [`IFillFormat`](/slides/python-net/el/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/el/aspose.slides/table/hyperlink_click/) | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για κλικ ποντικιού.<br/>            Ανάγνωση/Εγγραφή [`IHyperlink`](/slides/python-net/el/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/el/aspose.slides/table/hyperlink_mouse_over/) | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για κίνηση ποντικιού πάνω.<br/>            Ανάγνωση/Εγγραφή [`IHyperlink`](/slides/python-net/el/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/el/aspose.slides/table/hyperlink_manager/) | Επιστρέφει τον διαχειριστή υπερσυνδέσμων.<br/>            Μόνο ανάγνωση [`IHyperlinkManager`](/slides/python-net/el/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/el/aspose.slides/table/hidden/) | Καθορίζει αν το σχήμα είναι κρυφό.<br/>            Ανάγνωση/Εγγραφή **bool**. |
| [`z_order_position`](/slides/python-net/el/aspose.slides/table/z_order_position/) | Επιστρέφει τη θέση ενός σχήματος στη σειρά z.<br/>            Shapes[0] επιστρέφει το σχήμα στο πίσω μέρος της σειράς z,<br/>            και Shapes[Shapes.Count - 1] επιστρέφει το σχήμα στο μπροστά μέρος της σειράς z.<br/>            Μόνο ανάγνωση **int**. |
| [`connection_site_count`](/slides/python-net/el/aspose.slides/table/connection_site_count/) | Επιστρέφει τον αριθμό των σημείων σύνδεσης στο σχήμα.<br/>            Μόνο ανάγνωση **int**. |
| [`rotation`](/slides/python-net/el/aspose.slides/table/rotation/) | Επιστρέφει ή ορίζει τον αριθμό των μοιρών κατά τις οποίες το σχήμα περιστρέφεται γύρω από τον άξονα z. Μία θετική τιμή υποδεικνύει δεξιόστροφη περιστροφή· μια αρνητική τιμή υποδεικνύει αριστερόστροφη περιστροφή.<br/>            Ανάγνωση/Εγγραφή **float**. |
| [`x`](/slides/python-net/el/aspose.slides/table/x/) | Λαμβάνει ή ορίζει τη συντεταγμένη x της επάνω-αριστερής γωνίας του σχήματος, μετρημένη σε points.<br/>            Ανάγνωση/Εγγραφή **float**. |
| [`y`](/slides/python-net/el/aspose.slides/table/y/) | Λαμβάνει ή ορίζει τη συντεταγμένη y της επάνω-αριστερής γωνίας του σχήματος, μετρημένη σε points.<br/>            Ανάγνωση/Εγγραφή **float**. |
| [`width`](/slides/python-net/el/aspose.slides/table/width/) | Λαμβάνει ή ορίζει το πλάτος του σχήματος, μετρημένο σε points.<br/>            Ανάγνωση/Εγγραφή **float**. |
| [`height`](/slides/python-net/el/aspose.slides/table/height/) | Λαμβάνει ή ορίζει το ύψος του σχήματος, μετρημένο σε points.<br/>            Ανάγνωση/Εγγραφή **float**. |
| [`black_white_mode`](/slides/python-net/el/aspose.slides/table/black_white_mode/) | Η ιδιότητα καθορίζει πώς θα αποδίδεται το σχήμα σε λειτουργία εμφάνισης ασπρόμαυρου.<br/>            Ανάγνωση/Εγγραφή [`BlackWhiteMode`](/slides/python-net/el/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/el/aspose.slides/table/unique_id/) | Επιστρέφει έναν εσωτερικό, περιορισμένο στην παρουσίατα αναγνωριστικό που προορίζεται για χρήση από προσθήκες ή άλλον κώδικα.<br/>            Επειδή αυτή η τιμή μπορεί να επαναχρωματιστεί από το χρήστη ή προγραμματιστικά, δεν πρέπει να αντιμετωπίζεται ως μόνιμο μοναδικό κλειδί.<br/>            Μόνο ανάγνωση **int**.<br/>            Δείτε επίσης [`Shape.office_interop_shape_id`](/slides/python-net/el/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/el/aspose.slides/table/office_interop_shape_id/) | Επιστρέφει ένα μοναδικό αναγνωριστικό περιορισμένο στη διαφάνεια που παραμένει σταθερό για τη διάρκεια ζωής του σχήματος και επιτρέπει στο PowerPoint ή σε κώδικα διασύνδεσης να αναφέρεται αξιόπιστα στο σχήμα από οπουδήποτε στο έγγραφο.<br/>            Μόνο ανάγνωση **int**.<br/>            Δείτε επίσης [`Shape.unique_id`](/slides/python-net/el/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/el/aspose.slides/table/alternative_text/) | Επιστρέφει ή ορίζει το εναλλακτικό κείμενο που σχετίζεται με ένα σχήμα.<br/>            Ανάγνωση/Εγγραφή **str**. |
| [`alternative_text_title`](/slides/python-net/el/aspose.slides/table/alternative_text_title/) | Επιστρέφει ή ορίζει τον τίτλο του εναλλακτικού κειμένου που σχετίζεται με ένα σχήμα.<br/>            Ανάγνωση/Εγγραφή **str**. |
| [`name`](/slides/python-net/el/aspose.slides/table/name/) | Επιστρέφει ή ορίζει το όνομα ενός σχήματος.<br/>            Πρέπει να μην είναι None. Χρησιμοποιήστε κενή συμβολοσειρά εάν χρειάζεται.<br/>            Ανάγνωση/Εγγραφή **str**. |
| [`is_decorative`](/slides/python-net/el/aspose.slides/table/is_decorative/) | Λαμβάνει ή ορίζει την επιλογή 'Σημείωση ως διακοσμητικό'<br/>            Ανάγνωση/Εγγραφή **bool**. |
| [`shape_lock`](/slides/python-net/el/aspose.slides/table/shape_lock/) | Επιστρέφει τις κλειδώσεις του σχήματος.<br/>            Μόνο ανάγνωση [`IGraphicalObjectLock`](/slides/python-net/el/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/el/aspose.slides/table/is_grouped/) | Καθορίζει αν το σχήμα είναι ομαδοποιημένο.<br/>            Μόνο ανάγνωση **bool**. |
| [`parent_group`](/slides/python-net/el/aspose.slides/table/parent_group/) | Επιστρέφει το γονικό αντικείμενο GroupShape εάν το σχήμα είναι ομαδοποιημένο. Αλλιώς επιστρέφει None.<br/>            Μόνο ανάγνωση [`IGroupShape`](/slides/python-net/el/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/el/aspose.slides/table/slide/) | Επιστρέφει τη γονική διαφάνεια ενός σχήματος.<br/>            Μόνο ανάγνωση [`IBaseSlide`](/slides/python-net/el/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/el/aspose.slides/table/presentation/) | Επιστρέφει την γονική παρουσίαση μιας διαφάνειας.<br/>            Μόνο ανάγνωση [`IPresentation`](/slides/python-net/el/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/el/aspose.slides/table/graphical_object_lock/) | Επιστρέφει τις κλειδώσεις του σχήματος.<br/>            Μόνο ανάγνωση [`IGraphicalObjectLock`](/slides/python-net/el/aspose.slides/igraphicalobjectlock). |
| [`rows`](/slides/python-net/el/aspose.slides/table/rows/) | Επιστρέφει τη συλλογή των γραμμών.<br/>            Μόνο ανάγνωση [`IRowCollection`](/slides/python-net/el/aspose.slides/irowcollection). |
| [`columns`](/slides/python-net/el/aspose.slides/table/columns/) | Επιστρέφει τη συλλογή των στηλών.<br/>            Μόνο ανάγνωση [`IColumnCollection`](/slides/python-net/el/aspose.slides/icolumncollection). |
| [`table_format`](/slides/python-net/el/aspose.slides/table/table_format/) | Επιστρέφει το αντικείμενο TableFormat που περιέχει τις ιδιότητες μορφοποίησης για αυτόν τον πίνακα.<br/>            Μόνο ανάγνωση [`ITableFormat`](/slides/python-net/el/aspose.slides/itableformat). |
| [`style_preset`](/slides/python-net/el/aspose.slides/table/style_preset/) | Λαμβάνει ή ορίζει το ενσωματωμένο στυλ πίνακα.<br/>            Ανάγνωση/Εγγραφή [`TableStylePreset`](/slides/python-net/el/aspose.slides/tablestylepreset). |
| [`right_to_left`](/slides/python-net/el/aspose.slides/table/right_to_left/) | Καθορίζει αν ο πίνακας έχει σειρά ανάγνωσης από δεξιά προς αριστερά.<br/>            Ανάγνωση/Εγγραφή **bool**. |
| [`first_row`](/slides/python-net/el/aspose.slides/table/first_row/) | Καθορίζει αν η πρώτη γραμμή ενός πίνακα πρέπει να σχεδιαστεί με ειδική μορφοποίηση.<br/>            Ανάγνωση/Εγγραφή **bool**. |
| [`first_col`](/slides/python-net/el/aspose.slides/table/first_col/) | Καθορίζει αν η πρώτη στήλη ενός πίνακα πρέπει να σχεδιαστεί με ειδική μορφοποίηση.<br/>            Ανάγνωση/Εγγραφή **bool**. |
| [`last_row`](/slides/python-net/el/aspose.slides/table/last_row/) | Καθορίζει αν η τελευταία γραμμή ενός πίνακα πρέπει να σχεδιαστεί με ειδική μορφοποίηση.<br/>            Ανάγνωση/Εγγραφή **bool**. |
| [`last_col`](/slides/python-net/el/aspose.slides/table/last_col/) | Καθορίζει αν η τελευταία στήλη ενός πίνακα πρέπει να σχεδιαστεί με ειδική μορφοποίηση.<br/>            Ανάγνωση/Εγγραφή **bool**. |
| [`horizontal_banding`](/slides/python-net/el/aspose.slides/table/horizontal_banding/) | Καθορίζει αν οι ζυγές γραμμές πρέπει να σχεδιαστούν με διαφορετική μορφοποίηση.<br/>            Ανάγνωση/Εγγραφή **bool**. |
| [`vertical_banding`](/slides/python-net/el/aspose.slides/table/vertical_banding/) | Καθορίζει αν οι ζυγές στήλες πρέπει να σχεδιαστούν με διαφορετική μορφοποίηση.<br/>            Ανάγνωση/Εγγραφή **bool**. |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`get_image(self)`](/slides/python-net/el/aspose.slides/table/get_image/#) | Επιστρέφει τη μικρογραφία του σχήματος.<br/>            Ο τύπος ShapeThumbnailBounds.Shape χρησιμοποιείται εξ ορισμού για τα όρια μικρογραφίας. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/el/aspose.slides/table/get_image/#shapethumbnailbounds-float-float) | Επιστρέφει τη μικρογραφία του σχήματος. |
| [`write_as_svg(self, stream)`](/slides/python-net/el/aspose.slides/table/write_as_svg/#iorawiobase) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/el/aspose.slides/table/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [`set_text_format(self, source)`](/slides/python-net/el/aspose.slides/table/set_text_format/#iportionformat) | Ορίζει τις καθορισμένες ιδιότητες μορφοποίησης τμήματος σε όλα τα τμήματα των κελιών του πίνακα. |
| [`set_text_format(self, source)`](/slides/python-net/el/aspose.slides/table/set_text_format/#iparagraphformat) | Ορίζει τις καθορισμένες ιδιότητες μορφοποίησης παραγράφου σε όλες τις παραγράφους των κελιών του πίνακα. |
| [`set_text_format(self, source)`](/slides/python-net/el/aspose.slides/table/set_text_format/#itextframeformat) | Ορίζει τις καθορισμένες ιδιότητες μορφοποίησης πλαισίου κειμένου σε όλα τα πλαίσια κειμένου των κελιών του πίνακα. |
| [`remove_placeholder(self)`](/slides/python-net/el/aspose.slides/table/remove_placeholder/#) | Καθορίζει ότι αυτό το σχήμα δεν είναι σύμβολο θέση. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/el/aspose.slides/table/add_placeholder/#iplaceholder) | Προσθέτει ένα νέο σύμβολο θέση εάν δεν υπάρχει και ορίζει τις ιδιότητες του σύμβολο θέση σε αυτό που έχει οριστεί. |
| [`get_base_placeholder(self)`](/slides/python-net/el/aspose.slides/table/get_base_placeholder/#) | Επιστρέφει ένα βασικό σχήμα σύμβολο θέση (σχήμα από τη διάταξη και/ή τη βασική διαφάνεια από την οποία κληρονομείται το τρέχον σχήμα).<br/>            Επιστρέφεται None εάν το τρέχον σχήμα δεν κληρονομείται. |
| [`get_visual_bounds(self)`](/slides/python-net/el/aspose.slides/table/get_visual_bounds/#) | Λαμβάνει τα οπτικά όρια του σχήματος που υπολογίζονται από το αποδιδόμενο περιεχόμενό του. |
| [`merge_cells(self, cell1, cell2, allow_splitting)`](/slides/python-net/el/aspose.slides/table/merge_cells/#icell-icell-bool) | Συγχωνεύει γειτονικά κελιά. |

### Δείτε επίσης
* κλάση [`GraphicalObject`](/slides/python-net/el/aspose.slides/graphicalobject)
* κλάση [`Shape`](/slides/python-net/el/aspose.slides/shape)
* κλάση [`Table`](/slides/python-net/el/aspose.slides/table)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)